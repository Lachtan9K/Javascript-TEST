# Část otázek

## Jaké jsou datové typy v Javascriptu?

- number, string, boolean, undefined, object, null.

## Jaký je rozdíl v porovnání pomocí `!=` a `!==`?

- oba vyjadřují, že nejsou rovni, avšak !== znamená podle datového typu. 

## Kde se používá klíčové slovo `const`?

- const se používá pro vytvoření proměnné, kterou není potřeba měnit, jelikož je to konstanta. Např. číslo pí (je přímo daná)

## Jak se používá a k čemu slouží funkce `map()` nad polem (array)?

- map() metoda, slouží k vytvoření nové arraye na bázy výsledků volané funkce, doplní na každý prvek pole.

  př.
  
      const array0 = [1, 6, 7];

      const map0 = array0.map((x) => x * 2);

      předpokládaný výsledek je: map0 = [2, 12, 14]

## Jaké jsou rozdíli mezi polem (array) a Map kolekcí?

- Array je skupina věcí a map je kolekce, ve které můžete přidat novou hodnotu a rovnou kní přidat další. např. pizzaMenu.set("Pepperoni", 250);

název pizzy: pepperoni

cena: 250
