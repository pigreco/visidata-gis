# visidata-gis

![](./imgs/visidata-bn.png)

Come pulire e filtrare un CSV di 3M di righe per uso GIS

<!-- TOC -->

- [visidata-gis](#visidata-gis)
  - [Come nasce il tutto](#come-nasce-il-tutto)
  - [Link alle risorse](#link-alle-risorse)
  - [Esempi proposti](#esempi-proposti)
  - [Soluzione adottata](#soluzione-adottata)
  - [Relatori](#relatori)
  - [Live su OpenDataSicilia](#live-su-opendatasicilia)
  - [Programma](#programma)
  - [Riferimenti utili](#riferimenti-utili)

<!-- /TOC -->

## Come nasce il tutto

1. Domanda sul [Gruppo Telegram di QGIS Italia](https://t.me/qgis_it)

![](./imgs/screenshot.png)

2. Domanda su Facebook Gruppo [GIS Italia](https://www.facebook.com/groups/GisItalia/posts/10160017122146385/)

![](./imgs/facebook.png)

## Link alle risorse

- shapefile ISTAT : <https://www.istat.it/storage/cartografia/confini_amministrativi/generalizzati/Limiti01012022_g.zip>
- matrice distanze Calabria : <https://www.istat.it/storage/cartografia/matrici_distanze/Calabria.zip>
- GeoPackage con dati esempio, cartella [risorse](./risorse/prova_chart_atlas.gpkg).

## Esempi proposti

1. File della `matrice delle distanze` della Regione Calabria (Calabria.txt), ha quasi 3.000.000 di righe e risulta ingestibile sia da QGIS che da altri software (excel, NotePad++): filtrare e pulire i dati → fare una JOIN tabellare con lo shapefile ISTAT
2. Tabella degli attributi con molti campi: creare una tabella con solo due campi, tabella Melt → creare atlas con grafico

## Soluzione adottata

![](./imgs/visidata.png)

[VisiData](https://www.visidata.org/) è un fantastico strumento open source per esplorare e manipolare dati. Mette insieme la chiarezza di un foglio di calcolo, con l'efficienza del terminale e la potenza di Python, in una utility leggera in grado di gestire milioni di righe con facilità.

## Relatori

- 🧔 [Andrea Borruso](https://twitter.com/aborruso)
- 👨‍🦲 [Totò Fiandaca](https://twitter.com/totofiandaca)

## Live su OpenDataSicilia

- 📅 data: 11 marzo 2022
- 🕞 ore: 17:30 - 18:30
- 📽 piattaforma YouTube canale Open Data Sicilia - [ISCRIVITI](https://www.youtube.com/channel/UCyojAonwV6vNNJYAqw4JkTQ)
- 🔗 link diretta : <https://youtu.be/k1AOK3rz8PQ>

![](./imgs/locandina.jpg)

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



