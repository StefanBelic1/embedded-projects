# 🌡️ Meteo stanica (Arduino / Croduino)

**Vrsta projekta:** Ugradbeni sustav / sustav stvarnog vremena  
**Platforma:** Arduino / Croduino   
**Jezik:** C / Arduino  
**Senzori i periferija:** DHT11, I2C LCD, membranska tipkovnica  

## Opis projekta
Projekt predstavlja jednostavnu meteo stanicu za mjerenje temperature i vlage u stvarnom vremenu. Podaci se prikazuju na I2C LCD zaslonu, dok korisnik putem membranske tipkovnice može upravljati prikazom i postavljati temperaturne granice.

## Moj doprinos
- Integracija DHT11 senzora za očitavanje temperature i vlage
- Implementacija I2C komunikacije s 16x2 LCD zaslonom
- Obrada korisničkog unosa putem matrix membranske tipkovnice
- Razvoj firmwarea koji omogućuje:
  - prikaz trenutnih mjerenja
  - unos i spremanje temperaturnih granica
  - paljenje LED diode prema definiranim uvjetima

## Stečena znanja
- Rad sa senzorima i netočnim stvarnim podacima
- Implementacija jednostavne real-time logike
- Upravljanje više perifernih uređaja na ograničenim resursima
- Dizajn jednostavnog korisničkog sučelja za ugradbene sustave

## Moguća poboljšanja
- Zamjena DHT11 senzora preciznijim (npr. DHT22)
- Dodavanje pohrane podataka (data logging)
- Poboljšanje robusnosti i obrade grešaka

## Napomena
Detaljna dokumentacija projekta i izvorni kod nalaze se u priloženom PDF dokumentu.
