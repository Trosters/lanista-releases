# Lanista-tillägg

Webbläsartillägg för [Lanista](https://lanista.se). Varje tillägg installeras
för sig - ta ett eller båda.

| Tillägg | Vad det gör | Ladda ner |
| --- | --- | --- |
| **Lanista Improvements** | Rullgardinsmenyer på utrustningssidan, läsbara slutspelsträd i turneringar och dagliga bataljer, en kortare lagspelslayout, köpslagna priser hos handlare, förrådet i en ruta över utrustningssidan, total skada på vidundrens sidor, ett extra mörkt tema med mera. | [Versioner](https://github.com/Trosters/lanista-releases/releases?q=improvements-v&expanded=true) |
| **Lanista Planner Integration** | En knapp på utrustningssidan som öppnar hela bygget i Lanista-planeraren: gladiatorns utplacerade egenskapspoäng, grad och ras, plus utrustningen som sitter på. | [Versioner](https://github.com/Trosters/lanista-releases/releases?q=planner-v&expanded=true) |

Klicka på **Versioner** för tillägget du vill ha. Den översta är den senaste.

## Installera

Filerna heter `lanista-<tillägg>-firefox.xpi` och `lanista-<tillägg>-chrome.zip`,
t.ex. `lanista-improvements-firefox.xpi`.

### Firefox

Klicka på filen som slutar på `-firefox.xpi` och godkänn installationen.

Tillägget uppdaterar sig självt när en ny version släpps.

### Chrome, Edge, Brave

1. Ladda ner filen som slutar på `-chrome.zip` och packa upp den till en mapp
   du behåller (tillägget läses från mappen, så radera den inte).
2. Gå till `chrome://extensions` och slå på **Utvecklarläge** uppe till höger.
3. Klicka på **Läs in okomprimerat** och välj den uppackade mappen.

Chrome uppdaterar inte tillägg som installerats så här. Vid en ny version:
packa upp den nya zippen över den gamla mappen och klicka på uppdatera-pilen
på tillägget i `chrome://extensions`.

---

`updates.json` används av Firefox för automatiska uppdateringar och skrivs av
release-workflowen. Redigera den inte för hand.
