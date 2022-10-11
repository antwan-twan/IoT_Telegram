# Stap 1 - Begin
1. Maak een telegram account aan. 
2. Voor dat je begint, installeer je in Arduino IDE de library
>> Doe dat via deze [link](https://github.com/CasaJasmina/TelegramBot-Library)
    
    1. Vergeet niet de Library te installeren die ook wordt aangeraden door de TelegramBot Library. 

# Stap 2 - Code
Plak de onderstaande code naar je arduino en verander de WiFi-credentials naar jouw netwerk.
**LET OP!!** Include ook de andere library die je hebt geinstalleerd.

## Error
Op het moment dat ik mijn code wilde valideren, kwamen er zoveel errors naar voren dat ik niet wist waar ik moest beginnen. 

<img src="img\errors.png" width="375px" alt="error overload">

Ik heb verschillende zoekopdrachten gedaan en pogingen geprobeerd, die uiteindelijk niets opleverden. 
De error die onderaan staat: 'Compilation error: exit status 1'. 
Dit betekent dat er tijdens het compilen en het uploaden van de code naar het board, dat daar iets mis gaat. 

# Stap 3 - Begin opnieuw
Nadat de eerste poging is mislukt, heb ik een [andere guide](https://randomnerdtutorials.com/telegram-control-esp32-esp8266-nodemcu-outputs/) gepakt. 

Dit stappenplan is vrij makkelijk. 

**LET OP!** Je moet 2 libraries installeren. 

Vul op de juiste plaats je verschillende tokens in. 

Er mag wel **duidelijk** worden bijgezet dat je de gehele lange token vanuit de BotFather mag worden overgenomen. Deze ziet er ongeveer zo uit: XXXXXXXXX:XXXXXXXXXXXXXXXXXXXXXX

Het was niet duidelijk dat het gedeelte voor de dubbele punt ook mee deed. 

# Stap 4 - Success?
Het aansturen van het LEDje op de board is gelukt. Al is het bij dit specifieke board precies andersom; /led_on zet je LED uit en bij /led_off juist aan. 
>Dit kan je overigens aanpassen, maar had ik geen tijd voor. 

Ik begreep vrij weinig van de code die al voor mij geschreven was. Ik wilde de LEDstrip er aan verbinden, maar ik heb te weinig kennis van de LEDstrip en de library daarvan. 







# Bronnen
- https://www.hackster.io/coderscafe/telegram-bot-with-esp8266-dbada8
- https://core.telegram.org/bots/features
- https://support.arduino.cc/hc/en-us/articles/4402764401554-Compilation-errors-when-uploading
