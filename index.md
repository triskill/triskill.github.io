## Game-zero
Jednoduchá hra vytvářená společně s dětmi na kroužku programování DDM Tábor.
* [Hrát rhu](https://triskill.github.io/Game-Zero/)
* [Stáhnout si zdrojové soubory](https://github.com/triskill/Game-Zero/archive/master.zip)

## základní syntaxe

### proměnné a datové tipy

deklarace proměnné a přiřazení hodnoty:
```javascript
var jmeno = "Robert";
```
#### datové typy
```javascript
/// logické:
var jablkoJeOvoce = true;
var zebraJeOvoce = false;
// číselné:
var x = 42;
// řetězce:
var jmeno = "Mnislav Zelený";
// pole:
var zoo = ["lev", "sova", "žirafa", "lachtan"];
// objekt:
var auto = {
  nazev : "trabant",
  pocetKol : 4,
  nitro : false,
};
````
### podmínky

```javascript
if(x > 10){
  console.log("x je vetsi nez 10");
}
```
### cykly
#### for cyklus
```javascript
for(var i = 0; i<5; i++){
  console.log("i = " + i);
}
```
Cyklus vypíše do console:
```
i = 0
i = 1
i = 2
i = 3
i = 4
```

## užitečné odkazy

* [Phaser](https://phaser.io/) - herní engine pro 2D webové hry
* [w3 js tutorial](https://www.w3schools.com/js/default.asp) - příklady použití JavaScriptu encyklopedickou formou
* [CodePen](https://codepen.io/) - online editor kódu a knihovna zajímavých projektů v html, js a css
* [Atom](https://atom.io/) - editor který používáme
