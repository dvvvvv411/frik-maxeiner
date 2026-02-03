
## Rebranding-Plan: MERiTS → FRIK MAXEINER

Ich werde ein vollständiges Rebranding der Website durchführen, um alle Referenzen von MERiTS auf FRIK MAXEINER zu aktualisieren. Hier ist der Überblick:

### 📋 Zu ändernde Informationen

**Alte Daten (MERiTS):**
- MERiTS Kanzlei / MERiTS Partnerschaft von Rechtsanwälten mbB PartG
- Wolfsgangstr. 35, 60322 Frankfurt a. Main
- Telefon: (069) 870038470 / FAX: (069) 870038471
- info@merits-partner.de / merits-partner.de
- Partner: Christian Albert Ehlenz, Damaris Kosack, Nils H. Kutter

**Neue Daten (FRIK MAXEINER):**
- FRIK MAXEINER Rechtsanwälte PartG mbB
- Löffelstr. 22-24, 70597 Stuttgart
- Telefon: (0711) 92536420 / FAX: (0711) 92536421
- info@frik-maxeiner.de / frik-maxeiner.de
- Amtsgericht Stuttgart, PR 721285
- Partner: Julian Maxeiner, Roman Frik
- Sekretärin: Anna Weber

---

### 📁 Dateien, die geändert werden

**1. Meta-Daten & Konfiguration**
- `index.html` - Seitentitel, Meta-Beschreibungen, OG-Tags

**2. Header & Footer**
- `src/components/Header.tsx` - Logo-Bild-Pfad
- `src/components/Footer.tsx` - Logo-Bild-Pfad

**3. Kontaktseiten**
- `src/pages/Kontakt.tsx` - Telefonnummern korrigieren (089 → 0711)
- `src/pages/Impressum.tsx` - Telefonnummern korrigieren (089 → 0711)
- `src/pages/Datenschutz.tsx` - Telefonnummer korrigieren (089 → 0711)

**4. Testimonials**
- `src/components/TestimonialsSection.tsx` - "MERiTS Kanzlei" → "FRIK MAXEINER"

**5. Rechtsgebiet-Seiten**
- `src/pages/RechtsgebieteVertragsrecht.tsx` - MERiTS → FRIK MAXEINER
- `src/pages/RechtsgebieteGrundstuecksrecht.tsx` - "Frankfurter Immobilienlandschaft" → "Stuttgarter Immobilienlandschaft"
- `src/pages/Privatinsolvenz.tsx` - MERiTS Kanzlei → FRIK MAXEINER
- `src/pages/Insolvenzantrag.tsx` - MERiTS Kanzlei → FRIK MAXEINER

**6. Sozialrecht-Seiten**
- `src/pages/SozialrechtSchwerbehinderung.tsx` - MERiTS Kanzlei → FRIK MAXEINER
- `src/pages/SozialrechtRechtsschutz.tsx` - MERiTS Kanzlei → FRIK MAXEINER
- `src/pages/SozialrechtUnfallversicherung.tsx` - MERiTS Kanzlei → FRIK MAXEINER

**7. News & Verwaltungsrecht**
- `src/pages/NewsArticle2.tsx` - E-Mail-Adresse aktualisieren
- `src/pages/VerwaltungsrechtImpfpflicht.tsx` - E-Mail-Adresse aktualisieren

**8. Downloads**
- `src/pages/Downloads.tsx` - "MERiTS Kanzlei" → "FRIK MAXEINER"

---

### 🎨 Logo-Aktualisierung

Die aktuelle Website verwendet `/merits-logo-white.png`. Sie werden ein neues FRIK MAXEINER Logo hochladen müssen, das dann in Header und Footer verwendet wird.

---

### ✅ Ergebnis nach der Umsetzung

- Alle "MERiTS" Referenzen werden zu "FRIK MAXEINER" geändert
- Alle Kontaktdaten werden auf Stuttgart aktualisiert
- Telefonnummern werden korrekt mit Vorwahl 0711 angezeigt
- E-Mail-Adressen werden auf @frik-maxeiner.de aktualisiert
- Partner-Namen werden aktualisiert (Julian Maxeiner, Roman Frik)
- Frankfurt am Main → Stuttgart überall
- Logo-Referenzen werden vorbereitet für neues Logo
