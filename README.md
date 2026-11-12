# Modularna mini pokretna rampa s I2C OLED prikazom i automatiziranim upravljanjem


## Opis sustava

Ideja projekta je izgradnja dvostrukog sustava mini pokretnih rampi temeljenih na Arduino mikrokontroleru koji simulira rad garažnih vrata ili parking rampi. Sustav koristi servo motore za pokretanje rampi, mehaničke senzore za sigurnost, OLED zaslon za prikaz statusa u stvarnom vremenu i ručno upravljanje putem tipki. Dodatno, sustav uključuje zvučne signale za potvrdu radnji i upozorenja.

## Razrada po točkama bodovanja

| Stavka bodovanja | Predložena komponenta | Napomena |
|---|---|---|
| Mikrokontroler (15 bodova) | Arduino Nano / Arduino Uno | Osnovna jedinica upravljanja cijelim sustavom |
| I2C komunikacija (20 bodova) | OLED 0.96" I2C zaslon (SSD1306) | Prikaz statusa rampi, pozicije i sustava u stvarnom vremenu |
| Motor + aktuator (10 bodova) | 2x servo motor (SG90) | Jedan servo po rampi za precizno podizanje/spuštanje |
| Senzori (15 bodova) | 4x limit switch (mehanički prekidači) | Sigurnosni senzori: 2 po rampi (gornja i donja granica) |
| Zaslon (15 bodova) | OLED 0.96" I2C (SSD1306) | Grafički prikaz: status rampi, pozicija, upute za uporabu |
| Audio (5 bodova) | Piezo zvučnik | Kratki ton za potvrdu radnje, dugi ton za upozorenje na blokadu |
| Ručno upravljanje | 4x tipka | Za podizanje/spuštanje svake rampe posebno |
| Vizualna indikacija | 4x LED dioda (2 zelene, 2 crvene) | Indikacija stanja: zelena = gore, crvena = dolje |
| Kućište i mehanika | 3D printana / drvena konstrukcija | Stabilno postolje za rampe i montažu komponenti |




