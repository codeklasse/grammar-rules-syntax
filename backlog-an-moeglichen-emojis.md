# Wissenschaftliche Fragestellung:
- Welcher dieser Emojis ist für seine Funktion am beschreibendsten?
- Warum?

___

# Eingabe
- ⌨️ / 📝          // Text
- 🎤 / 🎙️         // Audio
- 📷 / 📸         // Kamera
- 🖼️              // Bildupload/ Auswahl aus Gallerie

# Ausgabe
- 💬              // Text
- 🔊              // Audio
- 📢              // Audio - anderer Effekt?
- 📡              // Broadcast: An alle senden

# Datenspeicherung
- 🗃️              // Variable
- 🗄️              // Variable

# Datenabfrage- /gleich
- ⚖️               // Vergleich ?
- 🟰              // "Heavy equals sign" emoji <- If approved in September 2021, this emoji will arrive on most platforms by the middle of 2022. 
- 🔍              // Vergleich ?
- 👀              // Vergleich ?
- ❔              // Vergleich ?
- 🔩              // Vergleich ?
- 🆗              // Erfolgsbedingung ?
- ❌              // "Trifft nicht zu" - Abbruchsbedingung ?

## ?
- 👍              // "Trifft zu" - Erfolgsbedingung ?
- 👎              // "Trifft nicht zu" - Abbruchsbedingung ?
- 🤏              // "Trifft ein bisschen nicht zu" 😂
- 🌡️              // Vergleich ?
- 🔒 🔑 🔓 ??     // "Trifft zu" 😂 ? - Vergleich ?
- 🎚️              // Vergleich ?
- 🔭              // Vergleich ?


# Wiederholung
- ⏰              // For loop ?
- ⏳              // While loop ?

- 🔁 / 🔄         // Keine Ahnung - Einfach eine Schleife mit Bedingung
- ♾️               // Infinite loop

# Bedingung
- ✅ / 🚩 / ▶️     // Erfolgsbedingung ?
- 🎯              // Erfolgsbedingung ?

- ❎ / 🛑 / ⏹️    // Abbruchsbedingung ? 

# "Coole/ Spaßige" Emojis
"Einfach nur wenn man nen geilen Effekt irgendwo draufklatschen will."

- 💩               // "💩"
- 🆒               // "Cool!!11 🆒" 😎 
- 💥               // "Bäm!! Peng peng!! 💥" 
- 🎊               // "Hooorraaay 🥳 taaadaaa 🥳"

# Beispielcoede
Sorg dafür, dass du deinem Roboter den Namen eines Klassenkameraden und eine Grußformel geben kannst. Wenn der Name in der Klassenliste steht, soll der Roboter dem Klassenkameraden einen Gruß schicken.

```
📝➡️🗃️ //Input: "Guten Tag"
📝➡️🗃️ // Input: "Jason"
📷➡️🗃️ // Bild für Jason aufnehmen 

🗃️🔍 KlassenlisteVariable ❓ // "Ist Kisteninhalt(Name) auffindbar in KlassenlisteVariable?"

    👍: 
        🗃️+🗃️🖼️ ➡️ 📡

    👎:
        🔤 ➡️ 💬 // ("Dieser Name ist nicht in der Klassenliste")
```