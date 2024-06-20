[Grįžti į pradžią](../../README.md)

# Kaip naudotis terminalu?

1. Atsidarome terminalą (`` Ctrl + `  ``)
2. Visų pirma galime išsibandyti ar terminalas veikia taip kaip reikia:
    - palaukiame kol terminalas pilnai užsikraus
    - kai pilnai užsikrauna, paskutinė naujausia eilutė turėtų būti tik su dolerio ($) simboliu
    - tada, parašome tekstą `pomidoras` ir spaudžiame ENTER
    - terminalas turėtų išmesti klaidos pranešimą tokiu tekstu:
    ```
    $ pomidoras
    bash: pomidoras: command not found
    ```
    - jei toks klaidos pranešimas matomas - viskas labai gerai 👍
3. Sekantis bandymas būtų patikrinti, ar turime reikalingas programas
4. Terminale parašome `npm -v`
5. Turėtume pamatyti kažkokius skaičius, kažką panašaus į:

```
$ npm -v
8.1.3
```

6. Jei skaičiai kitokie - viskas gerai 👍 svarbiausia negauti `bash: command not found` klaidos pranešimo
7. Dar galima patikrinti, ką daro kita komanda
8. Terminale parašome `node -v`
9. Turėtume pamatyti kažkokius skaičius, kažką panašaus į:

```
$ node -v
v18.16.1
```

10. Jei skaičiai kitokie - viskas gerai 👍 svarbiausia negauti `bash: command not found` klaidos pranešimo
