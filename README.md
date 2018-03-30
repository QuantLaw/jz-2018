## JZ 2018

**DOI (Aufsatz): 10.1628/jz-2018-0020**

In diesem Online-Anhang sind weitere Informationen zu den im Aufsatz geschilderten Analysen 
und den ihnen zugrundeliegenden Daten zusammengestellt.

Das Zip-Archiv kann hier heruntergeladen werden: [Download des Zip-Archivs](https://github.com/QuantLaw/jz-2018/zipball/master)

Es hat folgende Struktur:

* `data`
  - `bgh_juris_trefferzahlen.csv` und `bgh_statistik_erledigungen.csv` als Grundlage der im
    Aufsatztext geschilderten Schätzungen
  - `bgh_internet_aktenzeichen.txt`, `bgh_juris_aktenzeichen.txt` und `bgh_versand_aktenzeichen.txt`
    als Datengrundlage von Abbildung 1

* `documentation`
  - `abbildung_1.txt`, `abbildung_2.txt` und `abbildung_3.txt` mit Erläuterungen zur Erstellung
    der einzelnen Abbildungen
  - `datengrundlage.txt` mit Erläuterungen zu den Schritten, die erforderlich waren, um die 
    zur Analyse verwendeten Daten in die benötigte Form zu bringen

* `graphics`
  - Abbildungen 1 und 2 als BMP-Dateien
  - Abbildung 3 als PNG-Datei und als SVG-Datei

* `notebooks`
  - `juristreffer_vs_erledigungen.ipynb` zur Erstellung der im Aufsatztext geschilderten Schätzungen
  - `convert_to_txt.ipynb`, `split_txt.ipynb` und `create_db.ipynb` zur Vorverarbeitung der Entscheidungsdaten
  - `prepare_venn.ipynb` zur Vorbereitung von Abbildung 1
  - `search_db.ipynb` als Grundlage von Abbildung 2 und Abbildung 3
  - PDF-Versionen aller vorgenannten Dateien

Der zur Analyse verwendete Code basiert auf der Anaconda-Distribution von Python 3.6
mit (Jupyter) Notebook 5.1.0, soweit in den einzelnen Dateien nichts anderes vermerkt ist. 
