[Grįžti į pradžią](../../README.md)

# Nauji script'ai

1. Atsidarome terminalą (`` Ctrl + `  ``)
2. Susirandame `"script"` dalį `package.json` faile
3. Šiuo metu ji turėtų atrodyti štai taip:

```json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
},
```

4. Norint sukurti naujus script'us, reikia parašyti panašias eilutes kaip `"test"` script'o
5. Yra kelios taisyklės script'o pavadinimui:
    - turi būti vienas žodis
    - turi būti tik iš angliškų raidžių
    - turi būti tik iš mažųjų raidžių
6. Sukurkime 2 naujus script'us, kurie išspausdins kelis trumpus tekstus į terminalą
    - pirmasis: `"labas": "echo Labas rytas suraitytas"`
    - antrasis: `"knyga": "echo Ronja plesyko dukra"`
7. Sudėkime šiuo script'us į `package.json` failo `"script"` dalį. Nepamirškime eilutės pabaigoje padėti kablelio (,) ženklo.
8. Galutinis rezultatas turėtų atrodyti taip:

```json
"scripts": {
    "labas": "echo Labas rytas suraitytas",
    "knyga": "echo Ronja plesyko dukra",
    "test": "echo \"Error: no test specified\" && exit 1"
},
```

9. Išsaugome failą `Ctrl + s` ir išbandome šiuo 2 naujus script'us.

```
$ npm run labas

> js-for-kids@1.0.0 labas
> echo Labas rytas suraitytas

Labas rytas suraitytas
```

```
$ npm run knyga

> js-for-kids@1.0.0 knyga
> echo Ronja plesyko dukra

Ronja plesyko dukra
```
