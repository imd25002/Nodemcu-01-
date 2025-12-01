# Nodemcu-01-
# introdition
Det här projektet man får en led att blinka med arduino och använder denna kitten. 

<img width="452" height="318" alt="Skärmavbild 2025-12-01 kl  11 28 40" src="https://github.com/user-attachments/assets/120faeb1-d42b-43b1-86f6-a57c398211f8" />


# Mikroprocessor 
En mikroprocessor som ESP8266 är en minidator man kan programmera med Arunio IDE för att styra saker och koppla till WIFI.

## installera Arduino 
1. Ladda ner Arduino IDE från arduino.cc
2. installera programmet 
3. lägg till ESP8266 
4. installera tools --> board -->  boards manager
 <img width="203" height="190" alt="Skärmavbild 2025-12-01 kl  13 03 22" src="https://github.com/user-attachments/assets/5e13d9a0-78a6-474f-8c2f-e0ae7665f684" />

   


# I Arduino finns det två viktiga delar i programmet och portinitialisering.


portinitialisering
innebär att man ställer in en pinne som ingång eller utgång.

<img width="268" height="20" alt="Skärmavbild 2025-12-01 kl  12 25 17" src="https://github.com/user-attachments/assets/101bd23a-c670-4f72-9b87-76415eab828f" />



## setup
<img width="350" height="35" alt="Skärmavbild 2025-12-01 kl  11 23 36 1" src="https://github.com/user-attachments/assets/333d9582-c849-4fbd-b031-44562c182cc8" />


Det som startar programmet och körs en gång , den ställer in allt innan Aruino börjar jobba.

## loop
<img width="393" height="52" alt="Skärmavbild 2025-12-01 kl  11 31 10" src="https://github.com/user-attachments/assets/50d9230c-88fb-40d4-a48c-879fb32a3366" />


Körs om flera gånger och man skriver det som händer hela tiden, som att läsa sensorer eller styra lampor. 
