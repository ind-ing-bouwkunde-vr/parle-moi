# Parle-moi

Je eigen app om Frans te leren spreken met muziek, series en gesprekken. Hij werkt zonder account en zonder Claude, en ook offline. Wil je het vrije gesprek met Léa gebruiken, dan heb je een eigen API-sleutel nodig.

## Bestanden

| Bestand | Wat het is |
|---|---|
| `index.html` | de volledige app |
| `manifest.webmanifest` | naam en icoon voor je beginscherm |
| `sw.js` | zorgt dat de app ook offline opent |
| `icon-*.png` | app-iconen |

## Online zetten met GitHub Pages (gratis)

1. Maak een account op [github.com](https://github.com) als je er nog geen hebt.
2. Klik rechtsboven op **+ → New repository**. Geef hem de naam `parle-moi`, zet hem op **Public** en klik **Create repository**.
3. Klik op **uploading an existing file** en sleep alle bestanden uit deze map erin, dus niet de map zelf. Klik **Commit changes**.
4. Ga naar **Settings → Pages**. Kies bij *Source*: **Deploy from a branch**, bij *Branch*: **main** en **/(root)**, en klik **Save**.
5. Na een minuutje staat je app op `https://<jouw-gebruikersnaam>.github.io/parle-moi/`.

Let op: de repository is openbaar, dus iedereen met de link kan de app openen. Je voortgang, woorden, liedjes en je API-sleutel zitten **niet** in de repository. Die blijven alleen op je eigen toestel.

## Op je iPhone zetten

1. Open de link in **Safari**.
2. Tik op **Deel** → **Zet op beginscherm**.
3. Zet een Frans toetsenbord aan: Instellingen → Algemeen → Toetsenbord → Toetsenborden → Nieuw toetsenbord → **Frans**. Met 🌐 wissel je van toetsenbord, met 🎤 spreek je in het Frans in.

## Léa aanzetten (optioneel)

1. Maak een API-sleutel aan, bijvoorbeeld bij Google Gemini via [aistudio.google.com/apikey](https://aistudio.google.com/apikey). Je kunt ook OpenAI of Anthropic gebruiken.
2. Open in de app het tandwiel rechtsboven, kies de aanbieder, plak je sleutel en tik op **Test**.
3. Krijg je een foutmelding over het model? Vul bij *Model* de naam in van een actueel, goedkoop model van je aanbieder.

Zonder sleutel werkt al de rest: het dagplan, de aanbevelingen, de voorbereidingen, de geleide rollenspellen, de spelletjes, de woordenlijst en de liedjes. Alleen het vrije gesprek, automatische vertalingen en de extra AI-checks heb je dan niet.

## Updates

Pas je later iets aan, upload dan het gewijzigde bestand opnieuw in je repository. Open daarna de app opnieuw, met internet, en hij werkt zichzelf bij.

## Back-up

Alles staat alleen op je toestel. Via het tandwiel → **Download back-up** bewaar je je voortgang. Met **Zet terug** zet je hem op een nieuw toestel.
