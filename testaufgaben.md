# Programmieraufgaben (zum Testen)

## 1.
Frag nach einer Texteingabe.
Gib den Text 10x aus.

```
π¬ "Gib einen Text ein"
π β‘οΈ ποΈ

π 10
    ποΈ β‘οΈ π¬ 
```

### Ideen

```
π¬ "Gib einen Text ein"
π β‘οΈ ποΈ
```

oder 
```

π "Gib einen Text ein" β‘οΈ ποΈ
```

### b.
Gib den Text so lange aus bis eine beliebige Taste gedrΓΌckt wird.

```
π "Gib einen Text ein" β‘οΈ ποΈ

π 
    β¨οΈ β¬οΈ π
        ποΈ β‘οΈ π¬ 
```

Die Augen behalten die Tastatur/ den Bildschirm im Blick und reagieren auf Mausclick oder Tastenanschlag

```
β¨οΈ β¬οΈ π  
```

## 2.
Frag nach 3 Namen (Texteingabe).
Sortier die Namen nach ZeichenlΓ€nge & gib sie mit Text2Speech aus.

```
πππ β‘οΈ ποΈ

π ποΈ
    π π π 
    π β‘οΈ  


ποΈ β‘οΈ π€ 
```

a.
```
ποΈ
    π π π π β‘οΈ ποΈ 
```

b.
```
π ποΈ
    π π π β‘οΈ ποΈ 
```


### Alternativ

```
π"Erster Name" π"Zweiter Name" π"Dritter Name" β‘οΈ ποΈ

π 10
    ποΈ β‘οΈ π€ 
```

## 3.
Erstell eine Variable.
PrΓΌfe ob die Variable leer ist.
Falls ja, schreib deinen Namen darein.

```
ποΈ

ποΈ βοΈ [EMPTY] β
    π
        π β‘οΈ ποΈ 
```

## 4.
Frag nach 2 Zahlen.
PrΓΌfe ob die Eingaben wirklich zahlen sind.
Wenn es keine Zahlen sind, sag dem Nutzer das nur Zahlen erlaubt sind.
Wenn die Eingaben valide sind, berechne & gib die Summe aus.

- Was noch fehlt: Eine Option wie man bei Aufforderung zur Texteingabe einen ErklΓ€rungstext beifΓΌgen kann.

```
ππ’ ππ’ β‘οΈ ποΈ

π
    ποΈ βοΈ βπ’ β
    π
        π¬ "Nur Zahlen erlaubt"
        ππ’ ππ’ β‘οΈ ποΈ

π
    ποΈ β ποΈ 

        π¬ "Nur Zahlen erlaubt" 
```

"Nach dem Schema" "mΓΌsste" es folgendermaΓen sein, aber es sieht nicht sehr schΓΆn aus.
```
        "Nur Zahlen erlaubt" β‘οΈ π¬  
```

### b.
Wenn beide Zahlen gerade sind, berechne die Summe.
Wenn nicht, subtrahiere die beiden.

```
ποΈ βοΈ (ποΈ β 2 = 0)β
    π
        ποΈ β ποΈ β‘οΈ ποΈ
    π
        ποΈ β ποΈ β‘οΈ ποΈ

```

### c.
Wenn das Ergebnis der Subtraktion negativ ist, multipliziere mit 100.

```
ποΈ βοΈ π β
    π
        ποΈ βοΈ 100 β‘οΈ ποΈ
```

## 5.
Frag nach 2 gleichen Zahlen.
Wenn die Eingaben gleich sind, zeig ein Bild von einem glΓΌcklichen Hund aus der Gallerie.
Wenn nicht, zeig ein Bild von einem traurigen Welpen.

```
ππ’ ππ’ β‘οΈ ποΈ

β
    π
        πΌοΈπΆ
    π
        πΌοΈπ
```

Mit Hilfe von πΌοΈ & einem Argument dahinter kΓΆnnen Bilder aus einer vordefinierten Gallerie ausgegeben werden.
Gibt Bild eines Hundes aus.

```
πΌοΈπ
πΌοΈπ±
πΌοΈπΌ
```

Es kΓΆnnte eingestellt werden das es z.B. drei Slots gibt in denen eigen angelegte Bilder gespeichert werden.
Damit kΓΆnnte der Nutzerspeicher dynamisch referenziert werden.

```
πΌοΈπ₯οΈ1
πΌοΈπ₯οΈ2
πΌοΈπ₯οΈ3
```

## 6.
Frag nach 2 Zahlen (& validiere die Eingabe).
Gib eine zufΓ€llige Zahl zwischen den beiden genannten Werten aus.

```
ππ’β ππ’β β‘οΈ ποΈ

π π’ β‘οΈ ποΈ

ποΈ β‘οΈ π¬ 
```

ZufΓ€lligen Wert aus Variable ausgeben?
```
π ποΈ β‘οΈ π¬ 
```

ZufΓ€lligen Wert, der zwischen Werten der Variable liegt, ausgeben?
```
π       β‘οΈ π¬
ποΈ[#1]  ποΈ[#2] 
```

### Beobachtungen/ Notizen/ Fragen
Γquivalent?
```
ποΈ β¬οΈ π π’
π π’ β‘οΈ ποΈ
```

"Eingabe muss zwingend eine Zahl sein!"
```
ππ’β
```

"Eingabe muss zwingend ein String/ Wort (?) sein!"

```
ππ€β
```

## 7.
Erzeuge eine zufΓ€llige Zahl.
Frag den Nutzer nach einer Zahl.
Sag anschlieΓend, ob die Zahl erraten wurde.
Wenn nicht, sag, ob die geratene Zahl zu groΓ oder zu klein ist.

```
ππ’ β‘οΈ ποΈ
ππ’ β‘οΈ ποΈ

π
    ποΈ βοΈ ποΈ β
    π
        π¬ "Richtig geraten!"
    π
        ποΈ π ποΈ β
            π
                π¬ "Geratene Zahl zu groΓ"
            π
                π¬ "Geratene Zahl zu klein"
```

### Beobachtungen/ Notizen/ Fragen
- Gesucht: Emoji fΓΌr "grΓΆΓer als"
- Damit gemeint: Wert steigt?

```
ποΈ π ποΈ β
```


### b.
ZΓ€hle die Anzahl der Versuche.

```

```

#### Idee:
Aus einer Variable ποΈ wird ein π entnommen

```
ποΈ π 1
ποΈ π erstes | mittleres | letztes | nr. x
```

### c.
Sag wie viele Versuche erlaubt sind & beende das Spiel, wenn die Anzahl ΓΌberschritten ist.

```
```

## 8.
Emojis raten!
Tiere erraten beispielweise.
Man nehme eine vordefinierte Liste an Emojis (z.B. Tiere, FrΓΌchte) oder man erstellt die Liste selber.
Frag den Nutzer nach einer Eingabe.
Erstelle die jeweiligen FΓ€lle mit jeweiligen Ausgaben.

```
```
