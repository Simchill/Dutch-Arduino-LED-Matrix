# Dutch-Arduino-LED-Matrix
Met dit project laat ik zien hoe je een balletje kan besturen op een 8×8 led matrix.  Met de twee potentiometers kan je het balletje over de X en Y as van de matrix laten bewegen.   In dit project leer je hoe je een led matrix kan gebruiken en hoe je de waardes van een potentiometer kan aflezen.
Stap 1: Benodigheden
1X Arduino UNO

1X breadboard  - https://elektronicavoorjou.nl/product/breadboard-830-tie-points/

13X M/M jumper wires - https://elektronicavoorjou.nl/product/premium-jumper-wires-40stuks-20cm-m-m/

1X 8×8 led matrix - https://elektronicavoorjou.nl/product/max7219-8x8-matrix-display-module-rood/

2X 10K potentiometer - https://elektronicavoorjou.nl/product/panel-mount-10k-potentiometer-breadboard-vriendelijk/

Stap 2: Bouwen en Bedraden
Nu je alle onderdelen hebt kan je beginnen met het aansluiten van de onderdelen.

Als eerste ga je van de 5V op de UNO naar de plus op het breadboard en van de GND naar de min op het breadboard. Zodra je dat hebt gedaan zet je de potentiometers op het breadboard. Dan neem je de meest linker pin van beide potentiometers en sluit je aan op de plus, de meest rechter in de min en de middelste van een potentiometer sluit je aan op de A0 en bij de andere in de A1.

Nu gaan we de led matrix aansluiten, de led metrix zet je in het breadboard met de chip aan de onderkant. De VCC van de led matrix gaat naar de plus en de GND gaat naar de min. Dan sluiten we de I/O pinnen aan op de drie overige pinnen op de matrix. De DIN gaat naar pin 12, de CS  naar pin 10 en de CLK naar pin 11.

Zie afbeelding voor fritzing:
https://elektronicavoorjou.nl/wp-content/uploads/2019/07/led-matrix_bb-1-1200x1454.jpg
