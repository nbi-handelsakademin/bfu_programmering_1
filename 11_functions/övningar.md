# Övningar – funktioner i Python

Skriv funktioner som du kan återanvända. Testa varje funktion genom att anropa den med olika värden.

## Uppgift 1 – räkna ord

Skriv en funktion `count_words(text)` som tar emot en text och returnerar antalet ord.

Exempel:

```python
count_words("Hej på dig")  # ska returnera 3
```

**Tips:** Metoden `split()` kan dela upp en sträng i ord.

## Uppgift 2 – räkna tecken

Skriv en funktion `count_characters(text)` som returnerar antalet tecken i en text.

Testa även vad som händer med mellanslag.

## Uppgift 3 – omvandla deciliter

Skriv en funktion `dl_to_ml(dl)` som omvandlar deciliter till milliliter.

Exempel: `2 dl` ska bli `200 ml`.

## Uppgift 4 – omvandla till deciliter

Skriv en funktion `dl_to_liters(dl)` som omvandlar deciliter till liter.

Exempel: `5 dl` ska bli `0.5 liter`.

## Uppgift 5 – pris med rabatt

Skriv en funktion `price_after_discount(price, discount_percent)` som räknar ut priset efter rabatt.

Exempel: Om priset är 200 kr och rabatten är 25 %, ska funktionen returnera 150 kr.

## Uppgift 6 – hälsa användaren

Skriv en funktion `greet(name)` som tar emot ett namn och returnerar en hälsning.

Exempel:

```python
greet("Alex")  # ska returnera "Hej Alex!"
```

## Uppgift 7 – jämför medeltemperaturer

Skriv en funktion `average_temperature(temperatures)` som tar emot en lista med temperaturer och returnerar medeltemperaturen.

Exempel:

```python
average_temperature([10, 15, 20])  # ska returnera 15
```

**Tips:** Använd `sum()` och `len()`.

## Uppgift 8 – använd funktioner tillsammans

Fråga användaren efter en mening. Använd dina funktioner för att skriva ut:

- antalet ord
- antalet tecken
- meningen med stora bokstäver

**Tips:** Strängmetoden `upper()` gör texten till stora bokstäver

## Glosor 

| Glosa         | Betydelse |
| ------------- | --------- |
| Funktion      |           |
| `def`         |           |
| Funktionsnamn |           |
| Parameter     |           |
| Argument      |           |
| Anropa        |           |
| `return`      |           |
| Returvärde    |           |
