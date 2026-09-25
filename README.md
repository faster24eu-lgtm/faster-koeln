# Faster – Fahrzeugtransport Köln (deutsche Website)

Statische deutsche Website (reines HTML/CSS, kein Build-Schritt), die Kunden in **Köln und dem Rheinland** anspricht, deren Fahrzeug nach **Belgien** oder in den **Hafen Antwerpen** muss (oder zurück).

Ableger von [takeldienstfaster.be](https://takeldienstfaster.be) (Faster Depannage Takeldienst, Antwerpen).

## Positionierung (bewusst so gewählt)

Faster hat seinen Sitz in Antwerpen. Die Seite behauptet deshalb **keinen Abschleppdienst vor Ort in Köln** und keine lokale 24/7-Pannenhilfe dort. Sie bewirbt das, was Faster tatsächlich macht und auf der niederländischen Hauptseite belegt: Fahrzeugtransport und Rückführung zwischen Deutschland und Belgien, Export über den Hafen Antwerpen, Tieflader-Transporte mit festem Partner. Keine Preise, keine Kapazitäten außer den auf der Hauptseite genannten (Fahrzeuge bis 3,5 t selbst, Schweres per Partner-Tieflader).

## Seiten

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite (Leistungen, Ablauf, Beispiel, FAQ) |
| `fahrzeugtransport-koeln-belgien.html` | Hauptseite Fahrzeugtransport Köln–Belgien |
| `fahrzeugexport-antwerpen-hafen.html` | Export über den Hafen Antwerpen |
| `tieflader-transport.html` | Bus-Geschichte (wörtliche Übersetzung des niederländischen Artikels) |
| `kontakt.html` | Kontakt und Formular (FormSubmit.co → faster24eu@gmail.com) |
| `impressum.html`, `datenschutz.html` | Rechtstexte, **Entwurf** |
| `danke.html` | Dankeseite (noindex) |

## Vor der Veröffentlichung erledigen (Pflicht)

1. **Impressum ausfüllen** (§ 5 DDG): Firmenname und Rechtsform, Unternehmensnummer (KBO), USt-IdNr., Vertretungsberechtigter. Diese Angaben stehen nirgends auf der Hauptseite und sind gelb markiert.
2. **Datenschutzerklärung prüfen lassen** und den Hosting-Anbieter eintragen.
3. **Sprachen bestätigen:** Die Hauptseite nennt Niederländisch, Französisch, Englisch (kein Deutsch). Die Seite sagt das offen. Falls Deutsch möglich ist, FAQ und Kontaktseite anpassen.
4. **Texte gegenlesen lassen** (idealerweise Muttersprachler): Alles außer der Bus-Geschichte ist neu formulierter Entwurfstext.
5. **Abholung in Köln:** Bestätigen, dass Abholung in Köln und Umgebung tatsächlich angeboten wird (FAQ „Holen Sie Fahrzeuge in Köln ab?“).
6. **Formular aktivieren:** Beim ersten Absenden schickt FormSubmit eine Aktivierungs-E-Mail an faster24eu@gmail.com.
7. **Domain festlegen**, dann `canonical`-Tags, `sitemap.xml` und Open-Graph-Angaben mit der echten Adresse ergänzen (bewusst noch nicht enthalten).

## Tracking

Es ist **kein** Google-Tag und kein Cookie eingebunden. Für Google Ads in Deutschland wäre vorher eine Einwilligungsabfrage (Cookie-Banner) nötig.

## Veröffentlichen

Reines Static-Hosting genügt, zum Beispiel GitHub Pages (Repository-Einstellungen → Pages → Branch `main`, Ordner `/`). Kostenlose GitHub Pages benötigen ein **öffentliches** Repository.
