## Game-zero
Jednoduchá hra vytvářená společně s dětmi na kroužku programování DDM Tábor.
* [Hrát hru](https://triskill.github.io/Game-Zero/)
* [Stáhnout si zdrojové soubory](https://github.com/triskill/Game-Zero/archive/master.zip)
## základní syntaxe JavaScriptu

Doporučuji tento video tutoriál:

[JavaScript Tutorial](https://www.youtube.com/playlist?list=PLYWX-sH544Qj9MxhG4IOlk_vOCnSGiqpj)

Nenásilnou formou podává úplné základy JavaScriptu.

### proměnné a datové typy

deklarace proměnné a přiřazení hodnoty:
```javascript
var jmeno = "Robert";
```
#### datové typy
```javascript
/// logické:
var jablkoJeOvoce = true;
var zebraJeOvoce = false;
// celočíselné:
var x = 42;
// s plovoucí desetinou čárkou:
var dvaAPul = 2.5;
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

// nebo

if(vek >= 18){
  console.log("jsem plnoletý");
}else{
  console.log("nejsem plnoletý");
}
```
### cykly
#### while cyklus
```javascript
var i = 0;
while(i < 5){
  console.log("i = " + i++);
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

#### for cyklus
```javascript
for(var i = 0; i < 5; i++){
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
