# visidata-gis

![](./imgs/visidata-bn.png)

Come pulire e filtrare un CSV di 3M di righe per uso GIS

<!-- TOC -->

- [visidata-gis](#visidata-gis)
  - [Come nasce il tutto](#come-nasce-il-tutto)
  - [Link alle risorse](#link-alle-risorse)
  - [Descrizione problema](#descrizione-problema)
  - [Soluzione adottata](#soluzione-adottata)
  - [Relatori](#relatori)
  - [Live su onData](#live-su-ondata)
  - [Programma](#programma)
  - [Riferimenti utili](#riferimenti-utili)

<!-- /TOC -->

## Come nasce il tutto

Nasce da una domanda sul [Gruppo Telegram di QGIS Italia](https://t.me/qgis_it)

![](./imgs/screenshot.png)

## Link alle risorse

- shapefile ISTAT : <https://www.istat.it/storage/cartografia/confini_amministrativi/generalizzati/Limiti01012022_g.zip>
- matrice distanze Calabria : <https://www.istat.it/storage/cartografia/matrici_distanze/Calabria.zip>

## Descrizione problema

Il file della `matrice delle distanze` della Calabria (calabria.txt) ha quasi 3.000.000 di righe e risulta ingestibile sia da QGIS che da altri software (excel, NotePad++). 

Il File ha dei problemi da risolvere come:

1. pulizia;
2. filtro. 

## Soluzione adottata

![](./imgs/visidata.png)

## Relatori

- 🧔 [Andrea Borruso](https://twitter.com/aborruso)
- 👨‍🦲 [Totò Fiandaca](https://twitter.com/totofiandaca)

## Live su onData

- 📅 data: 4 o 11 marzo 2022
- 🕞 ore: 17:30 - 18:30
- 📽 piattaforma YouTube : 
- 🔗 link diretta : 

## Programma

1. Introduzione a **VisiData** (Andrea Borruso);
2. Esempio d'uso di **VisiData** su dati Calabria (Totò Fiandaca):
   1. apertura file con **VisiData**;
   2. pulizia (togliere `,00` e da `,` a `.`);
   3. filtro usando il campo **origine** (`Origine >= 78000`);
3. Domande/risposte (Totò Fiandaca, Andrea Borruso);
4. Chiusura (Andrea Borruso);

## Riferimenti utili

- **VisiData**: <https://github.com/saulpw/visidata>
- **Guida italiana VisiData**: <https://ondata.github.io/guidaVisiData>
- **ISTAT shapefile**: <https://www.istat.it/it/archivio/222527> 
- **ISTAT matrice distanze**: <https://www.istat.it/it/archivio/157423>



