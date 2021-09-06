# Eingabe
- ⌨️ / 📝          // Texteingabe
- 🎤 / 🎙️         // Audioaufzeichnung
- 📷 / 📸         // Kameraaufnahme
- 🖼️              // Bildupload/ Auswahl aus Gallerie

## Codebeispiel
X in Variable speichern.

```
📝 ➡️ 🗃️ // Eine Eingabeaufforderung
📝📝📝 ➡️ 🗃️ // Mehrere Eingabeaufforderung
📷 ➡️ 🗃️
🎤 ➡️ 🗃️
🎙️ ➡️ 🗃️
🖼️ ➡️ 🗃️
```

# Ausgabe
- 💬              // Textausgabe
- 🔊 / 📢         // Tonausgabe
- 🤖 🔊           // Text2Speech 
- 📡              // Broadcast: Nachricht an alle senden

## Codebeispiel
X aus Variable auf unterschiedliche Art ausgeben.

```
🗃️ ➡️ 💬
🗃️ ➡️ 🔊
🗃️ ➡️ 🤖 🔊
🗃️ ➡️ 📢
🗃️ ➡️ 📡
```

# Datenspeicherung
Ein Typ von Variable.
Keine Unterscheidung zwischen Datentypen & Anzahl der gespeicherten Elemente.

- 🗃️ / 🗄️         

## Codebeispiel
X in Variable speichern.

```
📝 ➡️ 🗃️
📷 ➡️ 🗃️
🎤 ➡️ 🗃️
🎙️ ➡️ 🗃️
🖼️ ➡️ 🗃️
```

# Datenabfrage- /gleich
- 🔍              // Ist X eine Teilmenge von Y?

## Codebeispiel
Enthält die Variable den gesuchten Namen?

```
🗃️🔍 [Name] ❓ 
```

# Bedingung
- ❓              // Initiiert eine IF Klausel indem es am Ende steht

- ⚖️               // Ist x = y ?
- 👍 / ✅ / 🆗    // "Trifft zu" - Erfolgsbedingung
- 👎 / ❎ / ❌    // "Trifft nicht zu" - Abbruchsbedingung
- 🤏              // "Trifft ein bisschen zu/ nicht zu" 😂

## Codebeispiel
`if` .. `do` X `else` Y
Es sind nicht nötig immer beide Bedingung anzugeben

```
<Bedingung> ❓
    👍
        <code>
    👎
        <code>
```

Volle Batterie vs leere Batterie für "nicht leer" & "leer"
🔋 
❤️

💔

```
🗃️ ⚖️ 🗃️ ❓ 
    👍
        <code>
    👎
        <code>
```

# Wiederholung
Idee: Es gibt nur ein Schleifenobjekt.
Keine Unterscheidung zwischen `for` und `while`.

- ⏰ / ⏳ / 🔁 / 🔄    // Initiiert eine Schleife
- ♾️                    // Unendliche Schleife


## Codebeispiel
Aufgabe: Entferne das letzte Element der Variable solange, bis die Variable leer ist. 
`for` .. `do` 

Wir haben die Variable im Blick & stellen sicher das sie nicht leer ist. 
Solange das nicht der Fall ist, wird etwas wiederholt.
    Wir zerhacken bzw. entfernen das letzte Element aus der Variable.
    (Wenn wir bei der Variable an eine Liste denken, wird sie also kleiner.)

Vlt. kann das Element mit einem Dropdown ausgewählt werden, um den Kindern zu helfen.

```
🔁  🗃️ 👀 [nicht leer] ❓
    🗃️ [letzte] 🪓
```

[erstes] | [mittleres] | [letztes] | [Nummer X]

```
🔁  🗃️ ⚖️ [nicht leer] ❓
    🗃️ [letzte] 🪓
```


Element entfernen:
- 🪓 / 💥 / ⚰️ / 🔥 / 💣


# Coole For Schleifen

```
🗃️ ⚖️ 🔤 ❓ 
 👍 : 🔁  🗃️ ➡️ 💬
 👎 : 


🗃️ ⚖️ 🔤 ❓ ➡️ 🔁 
 👍 :  🗃️  💬
 👎 :

x == string ? {
    if true: loop: mach irgendwas
    else: mach irgendwas  
}

x == string ? if true: loop: {
    if true: mach irgendwas
    else: mach was anderes
}

🗃️ ⚖️ 🔤 ❓ 
 👍 : 🔁 
         🗃️  💬
 👎 :
```

🔁
    <Bedingung> ❓
        👍 mach was
        👎 mach was anderes

🔁 <Bedingung> ❓
        👍 mach was
        👎 mach was anderes

- Indendation macht viel her!
- Das Repeat Element sollte stets oben sein, da es signifikant für den Lesefluß ist


---
Wenn 🔤 leer ist, dann hat die Ausgabe ein beispielsweise leeres Blatt Papier.
ABER es gibt eine Ausgabe!