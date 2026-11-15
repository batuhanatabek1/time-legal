# TiMe — Datenschutzerklärung

**Zuletzt aktualisiert:** 13. November 2026
**Gültig ab:** 13. November 2026

> Dies ist eine Übersetzung. Bei Abweichungen gilt die englische bzw.
> türkische Fassung.

---

## Kurz gesagt

TiMe ist eine App zur Aufzeichnung des Menstruationszyklus. Deine Daten
werden **standardmäßig auf deinem Gerät gespeichert.** Ein Konto ist
nicht nötig. Wir speichern deine Zyklusdaten nicht auf unseren Servern.
Wir teilen keine Daten mit Werbenetzwerken. Nutzungsanalysen laufen nur, wenn du sie in den Einstellungen einschaltest; deine Gesundheitsdaten gehen nie in Analysen.

Deine Daten verlassen dein Gerät nur in diesen Fällen, jeweils unter deiner Kontrolle:

1. **KI-Kommentare und Chat** — wenn du für den Chat das Online-Modell einschaltest oder das Modell auf dem Gerät nicht
   verfügbar ist und du eingewilligt hast
2. **Austausch mit Apple Health (HealthKit)** — wenn du die Berechtigung
   erteilst
3. **Abo-Käufe**
4. **Absturzberichte und Nutzungsanalyse** — Absturzberichte sind standardmäßig an und lassen sich ausschalten; Nutzungsanalyse nur, wenn du sie einschaltest

Details unten.

---

## 1. Verantwortlicher

| | |
|---|---|
| Name | Batuhan Atabek |
| Adresse | Antalya, Türkei — Anfragen per E-Mail möglich |
| E-Mail | atabeksoft+privacy@gmail.com |

Diese Erklärung gilt für die iOS-App TiMe.

---

## 2. Welche Daten wir verarbeiten

### 2.1 Daten, die auf deinem Gerät bleiben

In der lokalen Datenbank deines Geräts gespeichert und **nie an unsere
Server gesendet:**

- Beginn- und Enddaten der Periode, Zykluslängen
- Blutungsstärke
- Symptome (körperlich, Stimmung, Ausfluss, Haut, Verdauung, Schlaf,
  Energie)
- Einträge zur sexuellen Aktivität
- Basaltemperatur, Gewicht, Ergebnisse von Ovulationstests
- Deine Freitextnotizen
- App-Einstellungen (Sprache, Einheiten, Erinnerungszeiten)
- Dein KI-Chatverlauf

Einige dieser Daten sind **besondere Kategorien personenbezogener Daten**
(Gesundheitsdaten und Daten zum Sexualleben) nach Art. 9 DSGVO. Deshalb
ist die Speicherung auf dem Gerät unsere Standardarchitektur.

### 2.2 Daten, die dein Gerät verlassen können

**a) KI-Kommentare und Chat**

TiMe nutzt zuerst **das eigene KI-Modell deines Geräts**, um Kommentare
zu erstellen. In diesem Fall verlassen keine Daten dein Gerät.

Wenn du eingewilligt hast, kannst du in den Einstellungen außerdem „Klügerer Chat mit dem Online-Modell“ einschalten. Dann gehen deine Chatnachrichten nach den folgenden Regeln zuerst an das Online-Modell, auch wenn dein Gerät das Modell auf dem Gerät unterstützt. Die Option ist standardmäßig aus und betrifft einmalige Kommentare nicht.

Unterstützt dein Gerät dieses Modell nicht, wirst du einmal gefragt, und
**nur mit deiner Einwilligung** wird Folgendes über eine verschlüsselte
Verbindung an einen Proxy-Server und von dort an einen KI-Anbieter
gesendet:

Gesendet:
- Deine Zykluslängen (nur Zahlen)
- Deine aktuelle Zyklusphase
- Von dir ausgewählte Symptom-Tags
- Nachrichten, die **du** im Chat schreibst
- Die Sprache der Oberfläche

Nicht gesendet:
- Dein Name, deine E-Mail, dein Geburtsdatum
- Standort
- Geräte- oder Werbe-ID
- Genaue Datumsangaben
- Freitextnotizen aus deinen Tageseinträgen

Du kannst diese Einwilligung jederzeit in den Einstellungen widerrufen.
Die App kehrt dann zu regelbasierten Kommentaren zurück und funktioniert
weiter.

**Wichtig:** Text, den du in den Chat schreibst, wird so an den Anbieter
übermittelt, wie du ihn geschrieben hast. Wir empfehlen, keine
identifizierenden Angaben in den Chat zu schreiben.

**b) Apple Health (HealthKit)**

Mit deiner Erlaubnis werden Menstruationsblutung, Basaltemperatur und
zugehörige Einträge mit Apple Health ausgetauscht. Diese Daten bleiben
auf deinem Gerät und werden nicht an uns gesendet.

Wir nutzen HealthKit-Daten **nicht für Werbung, Marketing oder Data
Mining und geben sie nicht an Dritte weiter.**

**c) Abos**

Käufe werden von Apple abgewickelt. Wir haben **keinen Zugriff auf deine
Zahlungsdaten.** Wir nutzen RevenueCat, um den Abostatus zu verfolgen;
dabei werden nur eine anonyme Nutzer-ID und der Abostatus gesendet, nie
deine Zyklusdaten.

**d) Missbrauchsschutz**

Um Missbrauch von KI-Anfragen zu verhindern, wird auf deinem Gerät eine
zufällig erzeugte Kennung (UUID) erstellt. Sie kann nicht mit dir
verknüpft werden, dient nur zum Zählen täglicher Anfragen und wird beim
Löschen der App zurückgesetzt.

**e) Absturzberichte und Nutzungsanalyse (Google Firebase)**

- **Absturzberichte (Firebase Crashlytics):** Wenn die App abstürzt, werden die Codestelle des Fehlers, das Gerätemodell, die iOS-Version, die App-Version und eine zufällige Installations-ID an Google gesendet. Der Bericht enthält keine Zyklen, Symptome, Notizen oder anderen Gesundheitsdaten. Standardmäßig an; ausschalten unter Einstellungen > Datenschutz > „Absturzberichte“.
- **Nutzungsanalyse (Firebase Analytics):** Standardmäßig **aus**; sie läuft nur, wenn du Einstellungen > Datenschutz > „Nutzungsanalyse“ einschaltest. Dann wird gesendet, welche Hauptbildschirme geöffnet werden, der Abschluss der Einrichtung, das Anzeigen des Abo-Bildschirms und Kaufschritte (inklusive Produktname), zusammen mit einer zufälligen App-ID. Zyklen, Symptome, Daten, Notizen und Chat-Inhalte werden **nie** gesendet. Außerdem wird gesendet, dass eine Chatnachricht gesendet wurde (ohne Inhalt), sowie das Ergebnis der Kaufwiederherstellung. Firebase erfasst zusätzlich automatisch Basisinformationen wie erstes Öffnen, Sitzungsbeginn, Nutzungsdauer, Gerätemodell, iOS-Version und das aus der IP-Adresse abgeleitete ungefähre Land. Die Werbe-ID (IDFA) wird nicht erhoben, personalisierte Werbung ist aus. Beim Ausschalten wird die Analyse-ID auf deinem Gerät gelöscht.

### 2.3 Daten, die wir nicht erheben

- Name, E-Mail, Telefonnummer
- Standort
- Werbe-ID (IDFA)
- Kontakte, Fotos, Kamera, Mikrofon
- Analysen, die Gesundheitsdaten enthalten

### 2.4 Derzeit nicht angebotene Funktionen

Die App bietet **keine** Cloud-Synchronisierung (iCloud). Deine Daten
werden nicht zwischen Geräten synchronisiert. Wird diese Funktion später
hinzugefügt, wird diese Erklärung aktualisiert und deine Einwilligung
gesondert eingeholt.

---

## 3. Rechtsgrundlage (DSGVO)

| Zweck | Daten | Rechtsgrundlage |
|---|---|---|
| Zyklusvorhersage und -aufzeichnung | Zyklus- und Symptomdaten | Ausdrückliche Einwilligung, Art. 9 Abs. 2 lit. a |
| KI-Kommentare (auf dem Gerät) | Zyklus- und Symptomdaten | Ausdrückliche Einwilligung |
| KI-Kommentare (online) | Daten aus §2.2(a) | Gesonderte ausdrückliche Einwilligung |
| Apple-Health-Anbindung | Gesundheitseinträge | Ausdrückliche Einwilligung |
| Benachrichtigungen | Vorhersagedaten, gewählte Uhrzeiten | Einwilligung |
| Aboverwaltung | Anonyme ID, Abostatus | Vertrag, Art. 6 Abs. 1 lit. b |
| Missbrauchsschutz | Zufällige Gerätekennung | Berechtigtes Interesse, Art. 6 Abs. 1 lit. f |

---

## 4. Internationale Übermittlungen

Wenn du in Online-KI-Kommentare einwilligst, werden die in §2.2(a)
genannten Daten an Server außerhalb deines Landes übermittelt.

| Empfänger | Rolle | Land |
|---|---|---|
| Cloudflare, Inc. | Proxy-Server | USA |
| Anthropic, PBC | KI-Anbieter — Kommentare und Chat (Claude) | USA |
| Google LLC | Absturzberichte und Nutzungsanalyse (Firebase) — §2.2(e) | USA |

KI- und Nutzungsanalyse-Übermittlungen beruhen auf deiner **ausdrücklichen Einwilligung.** Absturzberichte enthalten keine Gesundheitsdaten; wenn du sie nicht senden willst, schalte sie in den Einstellungen aus. Ohne Einwilligung für die KI werden deine Zyklus- und Symptomdaten nicht übermittelt und die App funktioniert weiter auf dem Gerät.

Unser Proxy **protokolliert** deine Gesundheitsdaten **nicht.**

Datenbedingungen der Anbieter:
- Google Firebase: https://firebase.google.com/support/privacy
- Anthropic: https://www.anthropic.com/legal/commercial-terms

---

## 5. Speicherdauer

- **Daten auf dem Gerät:** bis du sie löschst. Das Löschen der App
  löscht sie.
- **An den KI-Anbieter gesendete Daten:** werden von uns nach Erstellung
  der Antwort nicht gespeichert.
- **Kennung zum Missbrauchsschutz:** 24 Stunden.
- **Absturzberichte:** bis zu 90 Tage bei Google Firebase.
- **Nutzungsanalyse:** Daten auf Ereignisebene bis zu 2 Monate bei Google Analytics.
- **Abo-Aufzeichnungen:** wie gesetzlich vorgeschrieben, bei Apple und
  RevenueCat.

---

## 6. Deine Rechte

Nach der DSGVO hast du das Recht auf Auskunft, Berichtigung, Löschung,
Einschränkung der Verarbeitung, Datenübertragbarkeit, Widerspruch und
jederzeitigen Widerruf deiner Einwilligung. Außerdem kannst du dich bei
deiner Aufsichtsbehörde beschweren.

**In der Praxis:** Da die meisten deiner Daten nur auf deinem Gerät
liegen, kannst du mehrere dieser Rechte direkt in der App ausüben:

- **Auskunft / Übertragbarkeit:** Einstellungen → Daten exportieren
- **Löschung:** Einstellungen → Alle Daten löschen
- **Widerruf der Einwilligung:** Einstellungen → KI-Einwilligung

Für andere Anfragen: atabeksoft+privacy@gmail.com. Wir antworten
innerhalb von 30 Tagen.

---

## 7. Kinder

TiMe richtet sich nicht an Kinder unter 13 Jahren, und wir erheben
wissentlich keine Daten von ihnen. Wenn du Elternteil oder
Erziehungsberechtigte(r) bist und glaubst, dass dein Kind die App nutzt,
schreib an atabeksoft+privacy@gmail.com.

---

## 8. Sicherheit

- Daten werden in der standardmäßigen iOS-App-Sandbox gespeichert.
- Optionale App-Sperre (Face ID / Touch ID).
- Der gesamte Netzwerkverkehr ist per TLS verschlüsselt.
- Unser Proxy protokolliert keine Gesundheitsdaten.
- An den KI-Anbieter gesendete Daten werden minimiert.

Kein System ist vollkommen sicher. Wir empfehlen, dein Gerät aktuell zu
halten und einen Gerätecode zu verwenden.

---

## 9. Medizinischer Hinweis

TiMe dient der Information und persönlichen Aufzeichnung. Es ist **keine
medizinische Diagnose, keine Behandlung und keine Verhütungsmethode.**
Vorhersagen sind statistisch und können falsch sein. Wende dich für
Entscheidungen über deine Gesundheit an medizinisches Fachpersonal.

---

## 10. Änderungen

Wenn wir diese Erklärung ändern, zeigen wir einen Hinweis in der App und
aktualisieren das Datum oben. Bei wesentlichen Änderungen bitten wir
erneut um deine Einwilligung.

---

## 11. Kontakt

**Batuhan Atabek**
Antalya, Türkei — Anfragen per E-Mail möglich
atabeksoft+privacy@gmail.com
