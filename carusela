// C++ code
#include <Adafruit_NeoPixel.h>
#define LED_PIN 11
#define LED_COUNT 24
Adafruit_NeoPixel strip(LED_COUNT, LED_PIN, NEO_GRB + NEO_KHZ800);
void setup(){
  strip.begin();
  strip.show();
}

void loop(){
  float po = 0;
  strip.fill(67, 0, 24);
  strip.show();
  while (free){
    if (po > 23){
      po = 0;
    }
    else{
      po = po+1;
    }
  	strip.setPixelColor(po,255,0,0);
    strip.show();
    strip.setPixelColor((po-1),0,0,255);
    strip.show();
    delay(5);
   }
}
