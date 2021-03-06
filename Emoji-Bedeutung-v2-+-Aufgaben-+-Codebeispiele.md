# Eingabe
- β¨οΈ / π          // Texteingabe
- π€ / ποΈ         // Audioaufzeichnung
- π· / πΈ         // Kameraaufnahme
- πΌοΈ              // Bildupload/ Auswahl aus Gallerie

## Codebeispiel
X in Variable speichern.

```
π β‘οΈ ποΈ // Eine Eingabeaufforderung
πππ β‘οΈ ποΈ // Mehrere Eingabeaufforderung
π· β‘οΈ ποΈ
π€ β‘οΈ ποΈ
ποΈ β‘οΈ ποΈ
πΌοΈ β‘οΈ ποΈ
```

# Ausgabe
- π¬              // Textausgabe
- π / π’         // Tonausgabe - was heiΓt "Tonausgabe"?
- π€           // Text2Speech 
- π‘              // Broadcast: Nachricht an alle senden

## Codebeispiel
X aus Variable auf unterschiedliche Art ausgeben.

```
ποΈ β‘οΈ π¬
ποΈ β‘οΈ π
ποΈ β‘οΈ π€
ποΈ β‘οΈ π’
ποΈ β‘οΈ π‘
```
# Datenspeicherung
Ein Typ von Variable.
Keine Unterscheidung zwischen Datentypen & Anzahl der gespeicherten Elemente.

- ποΈ / ποΈ         

## Codebeispiel
X in Variable speichern.

```
π β‘οΈ ποΈ
π· β‘οΈ ποΈ
π€ β‘οΈ ποΈ
ποΈ β‘οΈ ποΈ
πΌοΈ β‘οΈ ποΈ
```

# Datenabfrage- /gleich
- π              // Ist X eine Teilmenge von Y?

## Codebeispiel
EnthΓ€lt die Variable den gesuchten Namen?

```
ποΈπ [Name] β 
```

# Bedingung
- β              // Initiiert eine IF Klausel indem es am Ende steht

- βοΈ               // Ist x = y ?
- π / β / π    // "Trifft zu" - Erfolgsbedingung
- π / β / β    // "Trifft nicht zu" - Abbruchsbedingung
- π€              // "Trifft ein bisschen zu/ nicht zu" π

## Codebeispiel
`if` .. `do` X `else` Y
Es sind nicht nΓΆtig immer beide Bedingung anzugeben

```
<Bedingung> β
    π
        <code>
    π
        <code>
```

Volle Batterie vs leere Batterie fΓΌr "nicht leer" & "leer"
π 
β€οΈ

π

```
ποΈ βοΈ ποΈ β 
    π
        <code>
    π
        <code>
```

# Wiederholung
Idee: Es gibt nur ein Schleifenobjekt.
Keine Unterscheidung zwischen `for` und `while`.

- β° / β³ / π / π    // Initiiert eine Schleife
- βΎοΈ                    // Unendliche Schleife


## Codebeispiel
Aufgabe: Entferne das letzte Element der Variable solange, bis die Variable leer ist. 
`for` .. `do` 

Wir haben die Variable im Blick & stellen sicher das sie nicht leer ist. 
Solange das nicht der Fall ist, wird etwas wiederholt.
    Wir zerhacken bzw. entfernen das letzte Element aus der Variable.
    (Wenn wir bei der Variable an eine Liste denken, wird sie also kleiner.)

Vlt. kann das Element mit einem Dropdown ausgewΓ€hlt werden, um den Kindern zu helfen.

```
π  ποΈ π [nicht leer] β
    ποΈ [letzte] πͺ
```

[erstes] | [mittleres] | [letztes] | [Nummer X]

```
π  ποΈ βοΈ [nicht leer] β
    ποΈ [letzte] πͺ
```


Element entfernen:
- πͺ / π₯ / β°οΈ / π₯ / π£


# Coole For Schleifen

```
ποΈ βοΈ π€ β 
 π : π  ποΈ β‘οΈ π¬
 π : 


ποΈ βοΈ π€ β β‘οΈ π 
 π :  ποΈ  π¬
 π :

x == string ? {
    if true: loop: mach irgendwas
    else: mach irgendwas  
}

x == string ? if true: loop: {
    if true: mach irgendwas
    else: mach was anderes
}

ποΈ βοΈ π€ β 
 π : π 
         ποΈ  π¬
 π :
```

π
    <Bedingung> β
        π mach was
        π mach was anderes

π <Bedingung> β
        π mach was
        π mach was anderes

- Indendation macht viel her!
- Das Repeat Element sollte stets oben sein, da es signifikant fΓΌr den LesefluΓ ist


---
Wenn π€ leer ist, dann hat die Ausgabe ein beispielsweise leeres Blatt Papier.
ABER es gibt eine Ausgabe!


