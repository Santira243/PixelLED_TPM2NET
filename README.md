# PixelLED_TPM2NET
With Gonzalo Mastricola, Baltazar Villanueva and Me (Santiago Romero Ayala)!

This is a projet to control Neo Pixel LED (Ws2812b) with only this firmware over the NODE MCU AMICA ESP8266.

This connects to the Wifi Network:
const char* ssid     = "Prueba";  //nombre del wifi
const char* password = "prueba123"; //clave router

And you can specify the ip adress:

IPAddress ip(192,168,0,120);
IPAddress gateway(192,168,0,1);
IPAddress subnet(255,255,255,0);
unsigned int localPort = 65506;      // local port to listen for UDP packets

Then using a controller software like Jinx you can send via TPM2NET any effect you like!
It supports over 1500 pixel led tested!!. 
