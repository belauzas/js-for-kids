[Grįžti į pradžią](../../README.md)

# Mokomės naudotis script'ais

1. Atsidarome terminalą (`` Ctrl + `  ``)
2. Atsidarome `package.json` failą
3. Susirande dalį, kur yra parašyti script'ai, ji šiuo metu turėtų atrodytu maždaug taip:

```json
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```

    - prieš dvitaškį (:) yra script'o pavadinimas
    - už dvitaškio (:) yra parašyta ką šis script'as daro? koks jo darbas?

4. Terminale parašome komandą, kuri yra iš 3 žodžių:

-   npm
-   run
-   ir norimo script'o pavadinimas

Mūsų atveju, mes galime paleisti tik tokį script'ą:

```
npm run test
```

5. Turėtume pamatyti tokį rezultatą:

```
$ npm run test

> js-for-kids@1.0.0 test
> echo "Error: no test specified" && exit 1

"Error: no test specified"
```

6. `package.json` faile pakeiskime script'o, kurio pavadinimas šiuo metu yra `"test"` pavadinimą į `"agurkas"`
7. Galiausiai turėtume matyti tokį rezultatą:

```json
 "scripts": {
    "agurkas": "echo \"Error: no test specified\" && exit 1"
  },
```

8. Išsaugome failą `Crtl + s`
9. Terminale parašome senesnę komandą

```
npm run test
```

10. Turėtume pamatyti tokį klaidos rezultatą, nes norimas script'o pavadinimas `"test"` nebeegzistuoja:

```
$ npm run test
npm ERR! Missing script: "test"
npm ERR!
npm ERR! To see a list of scripts, run:
npm ERR!   npm run

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\belau\AppData\Local\npm-cache\_logs\2024-06-20T17_16_53_435Z-debug.log
```

11. Tada terminale parašome naujają komandą

```
npm run agurkas
```

12. Turėtume pamatyti tokį rezultatą:

```
$ npm run agurkas

> js-for-kids@1.0.0 agurkas
> echo "Error: no test specified" && exit 1

"Error: no test specified"
```

13. Grąžinkime script'o pavadinimą į originalu `"test"` ir išsaugome failą

```json
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```
