[Grįžti į pradžią](../../README.md)

# Skaičiai

## Pasiruošimas

1. Pasiruošiame naujam darbui:
    - susikuriame naują projektą pavadinimu `skaiciai`
    - susikuriame naują failą, pavadinimu `index.js`
    - pasigaminame `package.json` failą
    - susikuriame naują script'ą: `"kodas": "node ./index.js"`
2. Išbandome abu turimus script'us:
    - `npm run test`
    - `npm run kodas`

## Nauja informacija

Tam, kad kompiuteriai galėtų padaryti tai ką mes norime, mums reikia kompiuteriui duoti informacijos.

Informacija būna kelių skirtingų tipų:

-   skaičiai
-   tekstas
-   sąrašai
-   ir dar keletas kitų variantų

Kol kas mes dirbsime tik su **skaičiais**.

Norint, jog kompiuteris prisimintų mūsų duotus skaičius, reikia sukurti `kintamuosius`, pvz.:

```js
const duonosKaina = 2;
const agurkoKaina = 1;
const pomidoroKaina = 2.5;
const braskiuKaina = 5.7;
```

Kai taip parašome, kompiuteris dabar prisimena keturias reikšmes.

Norint, paprašyti, jog kompiuteris mums išspausdintų tas reikšmes, galime panaudoti `console.log()` komandą, pvz.:

```js
console.log(duonosKaina);
console.log(agurkoKaina);
console.log(pomidoroKaina);
console.log(braskiuKaina);
```

## Užduotis

1. Į `index.js` failą parašyk prieš tai pateiktą kodą
2. Visų pirma sukuriame `kintamuosius`
3. Po to parašome, jog juos išspaudintų
4. Galutinis rezultatas turėtų atrodytu maždaug taip

```js
const duonosKaina = 2;
const agurkoKaina = 1;
const pomidoroKaina = 2.5;
const braskiuKaina = 5.7;

console.log(duonosKaina);
console.log(agurkoKaina);
console.log(pomidoroKaina);
console.log(braskiuKaina);
```

5. Terminale paleidžiame komandą, kuri turėtų parodyti kaip veikia JavaScript kodas

```
npm run kodas
```

6. Jei viską gerai padarei, turėtum pamatyti keturis skaičius atskirose eilutėse
