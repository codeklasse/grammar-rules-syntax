# Programmieraufgaben (zum Testen)

## 1.
Frag nach einer Texteingabe.
Gib den Text 10x aus.

```
📝 ➡️ 🗃️

🔁 10
    🗃️ ➡️ 💬 
```

### b.
Gib den Text so lange aus bis eine beliebige Taste gedrückt wird.
- Keine Ahnung wie so etwas funktionieren würde.

```
⌨️ ⬇️ 👀
```

## 2.
Frag nach 3 Namen (Texteingabe).
Sortier die Namen nach Zeichenlänge & gib sie mit Text2Speech aus.

```
📝📝📝 ➡️ 🗃️

🔁 10
    🗃️ ➡️ 🤖 🔊 
```

## 3.
Erstell eine Variable.
Prüfe ob die Variable leer ist.
Falls ja, schreib deinen Namen darein.

```
🗃️

🗃️ ⚖️ [leer] ❓
    👍
        📝 ➡️ 🗃️ 
```

## 4.
Frag nach 2 Zahlen.
Prüfe ob die Eingaben wirklich zahlen sind.
Wenn es keine Zahlen sind, sag dem Nutzer das nur Zahlen erlaubt sind.
Wenn die Eingaben valide sind, berechne & gib die Summe aus.

- Was noch fehlt: Eine Option wie man bei Aufforderung zur Texteingabe einen Erklärungstext beifügen kann.

```
📝🔢 📝🔢 ➡️ 🗃️

🔁
    🗃️ ⚖️ ❎🔢 ❓
    👍
        💬 "Nur Zahlen erlaubt"
        📝🔢 📝🔢 ➡️ 🗃️

🔁
    🗃️ ➕ 🗃️ 

        💬 "Nur Zahlen erlaubt" 
```

"Nach dem Schema" "müsste" es folgendermaßen sein, aber es sieht nicht sehr schön aus.
```
        "Nur Zahlen erlaubt" ➡️ 💬  
```

### b.
Wenn beide Zahlen gerade sind, berechne die Summe.
Wenn nicht, subtrahiere die beiden.

```
🗃️ ⚖️ (🗃️ ➗ 2 = 0)❓
    👍
        🗃️ ➕ 🗃️ ➡️ 🗃️
    👎
        🗃️ ➖ 🗃️ ➡️ 🗃️

```

### c.
Wenn das Ergebnis der Subtraktion negativ ist, multipliziere mit 100.

```
🗃️ ⚖️ 📉 ❓
    👍
        🗃️ ✖️ 100 ➡️ 🗃️
```

## 5.
Frag nach 2 gleichen Zahlen.
Wenn die Eingaben gleich sind, zeig ein Bild von einem glücklichen Hund aus der Gallerie.
Wenn nicht, zeig ein Bild von einem traurigen Welpen.

```
📝🔢 📝🔢 ➡️ 🗃️

```

## 6.
Frag nach 2 Zahlen (& validiere die Eingabe).
Gib eine zufällige Zahl zwischen den beiden genannten Werten aus.

```
📝🔢❗ 📝🔢❗ ➡️ 🗃️

🔀 🔢 ➡️ 🗃️

🗃️ ➡️ 💬 
```

Zufälligen Wert aus Variable ausgeben?
```
🔀 🗃️ ➡️ 💬 
```

Zufälligen Wert, der zwischen Werten der Variable liegt, ausgeben?
```
      🔀       ➡️ 💬
🗃️[#1]  🗃️[#2] 
```

### Beobachtungen/ Notizen/ Fragen
Äquivalent?
```
🗃️ ⬅️ 🔀 🔢
🔀 🔢 ➡️ 🗃️
```

"Eingabe muss zwingend eine Zahl sein!"
```
📝🔢❗
```

"Eingabe muss zwingend ein String/ Wort (?) sein!"

```
📝🔤❗
```

## 7.
Erzeuge eine zufällige Zahl.
Frag den Nutzer nach einer Zahl.
Sag anschließend, ob die Zahl erraten wurde.
Wenn nicht, sag, ob die geratene Zahl zu groß oder zu klein ist.

```
🔀🔢 ➡️ 🗃️
📝🔢 ➡️ 🗃️

🔁
    🗃️ ⚖️ 🗃️ ❓
    👍
        💬 "Richtig geraten!"
    👎
        🗃️ 📈 🗃️ ❓
            👍
                💬 "Geratene Zahl zu groß"
            👎
                💬 "Geratene Zahl zu klein"
```

### Beobachtungen/ Notizen/ Fragen
- Gesucht: Emoji für "größer als"
- Damit gemeint: Wert steigt?

```
🗃️ 📈 🗃️ ❓
```


### b.
Zähle die Anzahl der Versuche.

```

```

#### Idee:
Aus einer Variable 🗃️ wird ein 📁 entnommen

```
🗃️ 📁 1
🗃️ 📁 erstes | mittleres | letztes | nr. x
```

### c.
Sag wie viele Versuche erlaubt sind & beende das Spiel, wenn die Anzahl überschritten ist.

```
```

## 8.
Emojis raten!
Tiere erraten beispielweise.
Man nehme eine vordefinierte Liste an Emojis (z.B. Tiere, Früchte) oder man erstellt die Liste selber.
Frag den Nutzer nach einer Eingabe.
Erstelle die jeweiligen Fälle mit jeweiligen Ausgaben.

```
```
