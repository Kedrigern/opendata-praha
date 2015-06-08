
## OpenData Praha - metodika

### Cíle

Srozumitelnost, strojová zpracovatelnost

### Postup

### Typy polí

|   Typ        |   Příklad           |   Popis                                                       |
|--------------|---------------------|---------------------------------------------------------------|
| Číslo        | 1234                | Číslo skladající se pouze z číslic, popř. znaménka.           |
| Realné číslo | -1234.15            | Oproti prostému číslu přibývá desetinná tečka (nikoliv čárka! |
| Text         | Ahoj světe širý     | Libovolný text (kodóvání unicode).                            |
| Odkaz        | http://www.praha.eu | Celý odkaz (url), lze uvádět i jiné protokoly než `http`.     |
| Datum        | 2015-12-01          | Datum ve formátu `YYYY-MM-DD`       |
| Výčet        | Ano                 | Hodnoty z předem daného výčtu.      |
| Katastr      | 123/1, 456/2        | Čísla parcel oddělena čárkou. Může být i číslo bez lomítka.   |

#### Používané výčty

| Název(y)                      | Výčet (oddělení `,`) |
|-------------------------------|----------------------|
| Boolovská hodnota             | ano, ne              |
| Jídelna, Zahrada, Sportoviště | areal, externí, není |
| Typ školy                     | MŠ, ZŠ, SŠ, VŠ       |
| Typ školy                     | Gymnázium, VOŠ       |


