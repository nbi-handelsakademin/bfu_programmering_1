# Övningar – felhantering i Python

Gör övningarna och försök lösa dem själv först. Använd `try` och `except` för att fånga fel och hjälpa användaren vidare.

## Uppgift 1 – fixa logiska fel

Den här koden innehåller 2 logiska fel, fixa dem

```py
temperatures = [12, 15, 18, 20]

average_temperature = sum(temperatures) / (len(temperatures) + 1)

print("Average temperature:", average_temperature)

if average_temperature > 15:
    print("The average temperature is 15 degrees or lower.")
else:
    print("The average temperature is above 15 degrees.")
```

## Uppgift 2 – guida användaren till rätt inmatning

Fråga efter användarens ålder. Användaren ska skriva ett heltal mellan 0 och 125.

- Om svaret inte är ett heltal, förklara att användaren ska skriva siffror.
- Om talet är mindre än 0 eller större än 125, förklara vilket intervall som gäller.
- Fortsätt fråga tills användaren skriver ett giltigt svar.

**Tips:** Kombinera `while`, `try`, `except` och `if`.

## Uppgift 3 – division utan krasch

Fråga efter två tal och dela det första talet med det andra.

- Hantera om användaren skriver något som inte är ett tal.
- Hantera om det andra talet är 0.
- Skriv ut resultatet när inmatningen är giltig.

**Tips:** Du kan fånga `ValueError` och `ZeroDivisionError`.

## Uppgift 4 - spårvagn

Boda är en klumpig datoranvändare som inte åker spårvagn så ofta. Skriv ett program som frågar användaren efter:

hur många gånger hen planerar att åka spårvagn under en månad
vad en enkelbiljett kostar
vad ett månadskort kostar

Programmet ska räkna ut om det lönar sig att köpa ett månadskort eller inte. Gör programmet användarvänligt med tydliga felmeddelanden, och låt användaren försöka igen om hen skriver in något fel.

## Glosor

| Glosa               | Betydelse |
| ------------------- | --------- |
| `try`               |           |
| `except`            |           |
| `ValueError`        |           |
| `ZeroDivisionError` |           |
| felhantering        |           |
| logiska fel         |           |
| syntaxfel           |           |
| exceptionfel        |           |
|                     |           |
