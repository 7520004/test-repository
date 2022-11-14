//2022/05/21
/* 
   servoサンプルコード
   参考URL：https://burariweb.info/electronic-work/arduino-learning/aruduino-servomotor-control.html
 */

//servo
#include <Servo.h>
  Servo myservo;
#define SV_PIN 7


void setup() {
  //set_servo
  myservo.attach(SV_PIN,400,2500); //servo age_range 0~180
  
  //else
  myservo.write(0);//初期位置（任意）
}

void loop() {
  //move_servo_by_age
  for (int i=0;i<180;i++){
    myservo.write(i); //servo age '0'
    delayMicroseconds(5277);
  }
  
  delay(1000);

  //move_servo_by_palse
  for (int i=2500;i>400;i--){
    myservo.writeMicroseconds(i); //servo palse ''
    delayMicroseconds(500);
  }  
  delay(1000);
}
