<p align="center">
  <img src="img/schakeling_eind.png" width="100%">
</p>

#define VIBRATIEMOTOR_L 2
#define VIBRATIEMOTOR_R 3
#define VIBRATIEMOTOR_M 4
#define BTN_ROOD_R  5
#define BTN_ROOD_L  6
#define BTN_ZWART_A 7
#define BTN_ZWART_B 8
#define BTN_ZWART_A 9
#define BTN_ZWART_B 10

bool systeemActief = false;
bool motorAan = false;

bool vorigeRood = HIGH;
bool vorigeZwart = HIGH;

unsigned long vorigeTijd = 0;
const unsigned long interval = 500;

void setup() {
  Serial.begin(9600);
  while (!Serial);

  pinMode(VIBRATIEMOTOR, OUTPUT);
  pinMode(BTN_ROOD, INPUT_PULLUP);
  pinMode(BTN_ZWART, INPUT_PULLUP);

  digitalWrite(VIBRATIEMOTOR, LOW);
}

void loop() {

  bool rood = digitalRead(BTN_ROOD);
  bool zwart = digitalRead(BTN_ZWART);


  // Rode knop: systeem aan/uit
  if (vorigeRood == HIGH && rood == LOW) {
    systeemActief = !systeemActief;

    if (!systeemActief) {
      motorAan = false;
      digitalWrite(VIBRATIEMOTOR, LOW);
    }

    delay(50);
  }


  // Zwarte knop indrukken: starten
  if (systeemActief && vorigeZwart == HIGH && zwart == LOW) {
    motorAan= true;
    delay(50);
  }


  // Zwarte knop loslaten: stoppen
  if (zwart == HIGH) {
    motorAan = false;
    digitalWrite(VIBRATIEMOTOR, LOW);
    
  }


  // 
  if (motorAan) {
    if (millis() - vorigeTijd >= interval) {
      vorigeTijd = millis();

      digitalWrite(VIBRATIEMOTOR, !digitalRead(VIBRATIEMOTOR));
    }
  }

  if (rood == LOW){
    Serial.println("rode knop ingedrukt");
  }
  if (zwart == LOW){
    Serial.println("zwarte knop ingedrukt");
  }
  vorigeRood = rood;
  vorigeZwart = zwart;
}