# arduino-tugas-cc
85_11_Francis matthew

kode :

int buzzer = 8;

void setup(){

pinMode(buzzer, OUTPUT);

}

void loop(){
int count = 0;

  do{
  
    tone(buzzer, 500);
    delay(500);
    noTone(buzzer);
    delay(500);
    count = count + 1;
  } while (count < 3);
  
   delay(1000);


  do{

    tone(buzzer, 500);
    delay(250);
    noTone(buzzer);
    delay(250);

   count = count + 1;

  
  }while (count <9);
  delay(1000);

}
