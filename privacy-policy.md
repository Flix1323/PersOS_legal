# Datenschutzerklärung – PersOS

**Stand:** 21. September 2026

*English version below.*

## 1. Verantwortlicher

Felix Hansmeier
Horstmarer Landweg 84
E-Mail: felix.hansmeier@gmail.com

PersOS wird von einer Privatperson entwickelt. Es gibt keinen Datenschutzbeauftragten, da keine Pflicht dazu besteht.

## 2. Grundsatz

PersOS funktioniert vollständig **ohne Konto**. Alle Daten, die du in der App erfasst, liegen zuerst und standardmäßig **nur auf deinem Gerät**. Es gibt **kein Tracking, keine Analytics, keine Werbung** und keine Weitergabe an Dritte zu Werbe- oder Analysezwecken. Daten verlassen dein Gerät nur, wenn du eine der unten beschriebenen Funktionen bewusst einschaltest.

## 3. Daten auf deinem Gerät

Die App speichert lokal, was du eingibst, zum Beispiel:

- Profil (Name, gewünschte Ansprache, Lebensabschnitt, aktive Bereiche)
- Aufgaben, Tagesplanung, Notizen, Ziele
- Studium und Arbeit (Stundenplan, Abgaben, Noten, Karteikarten)
- Workouts, Mahlzeiten, Wasser

Diese Daten liegen in der App-Datenbank auf deinem Gerät. Wir haben keinen Zugriff darauf. Sie werden gelöscht, wenn du die App löschst.

## 4. Apple-Schnittstellen

Diese Zugriffe fragt iOS einzeln ab. Du kannst sie jederzeit in den iOS-Einstellungen widerrufen.

- **Apple Health:** Die App liest Gesundheitswerte (z. B. HRV, Ruhepuls, Gewicht, Schlaf, Schritte, VO2max, SpO2, Atemfrequenz, Blutdruck, Blutzucker, Körperzusammensetzung, Nährwerte), um sie anzuzeigen. Sie schreibt Workouts, Mahlzeiten und auf Wunsch Wasser nach Apple Health. **Gesundheitswerte aus Apple Health verlassen dein Gerät nie**: Sie werden weder synchronisiert noch an eine KI gesendet noch an uns übermittelt.
- **Kalender und Erinnerungen:** zum Anzeigen und Anlegen von Terminen und Erinnerungen. Die Daten bleiben in deinem Kalender bzw. deinen Erinnerungen.
- **Musik:** um während eines Workouts den laufenden Titel anzuzeigen und die Wiedergabe zu steuern.

## 5. Optionale Synchronisierung

Du kannst in den Einstellungen **eines** von zwei Sync-Zielen wählen oder Sync ausgeschaltet lassen (Standard).

### 5.1 Konto (Supabase)

- **Anmeldung:** über „Mit Apple anmelden“ oder Google. Dabei erhalten wir eine Nutzer-ID und die E-Mail-Adresse, die Apple bzw. Google uns übermittelt (bei Apple ggf. eine anonymisierte Weiterleitungsadresse). Für die Anmeldung selbst gelten zusätzlich die Datenschutzbestimmungen von Apple bzw. Google.
- **Synchronisierte Daten:** die in Abschnitt 3 genannten App-Inhalte, damit sie auf deinen Geräten gleich sind. **Ausgenommen:** Herzfrequenz- und Energiewerte von Workouts sowie alle Werte aus Apple Health.
- **Anbieter:** Supabase Inc. als Auftragsverarbeiter. Die Datenbank liegt in einem Rechenzentrum in der **EU**. Da Supabase Inc. ein US-Unternehmen ist, ist ein Zugriff aus den USA nicht völlig ausgeschlossen. Grundlage dafür sind die EU-Standardvertragsklauseln.
- **Abmelden** beendet den Sync. Lokale Daten bleiben erhalten.

### 5.2 iCloud

Die Daten werden in deiner **privaten iCloud-Datenbank** bei Apple gespeichert. Sie sind nur mit deiner Apple-ID zugänglich, wir können sie nicht lesen. Es gelten die Datenschutzbestimmungen von Apple. Auch hier bleiben Gesundheitswerte auf dem Gerät.

## 6. KI-Funktionen

- **Standard:** KI-Funktionen laufen **auf dem Gerät** (Apple Foundation Models). Dabei verlassen keine Daten das Gerät.
- **Cloud-KI (optional):** nur mit Konto **und** nachdem du sie in den Einstellungen eingeschaltet hast. Vor dem ersten Senden zeigt die App, welche Einträge übermittelt werden. Die Anfrage läuft über unseren Server (Supabase, EU) an **Mistral AI SAS (Frankreich)**.
- Anfrageinhalte werden von uns **weder gespeichert noch protokolliert**. Gespeichert wird nur ein Zähler der Anfragen pro Tag und Konto, um Missbrauch zu begrenzen.
- **Gesundheitswerte werden nie an die Cloud-KI gesendet.**
- Ergebnisse der KI werden nur übernommen, wenn du „Übernehmen“ tippst.

## 7. WHOOP (optional)

Wenn du dein WHOOP-Konto verbindest, meldest du dich direkt bei WHOOP an (OAuth). Die App ruft dann Recovery-, Strain- und Schlafwerte über die WHOOP-API ab und zeigt sie an.

- Die Zugangs-Tokens liegen **nur in der Keychain** deines Geräts, nicht im Sync und nicht im Backup.
- Zum Tausch und zur Erneuerung der Tokens leitet unser Server (Supabase, EU) die Anfrage an WHOOP weiter. Dabei wird **nichts gespeichert oder protokolliert**.
- Die WHOOP-Werte bleiben auf dem Gerät wie alle Gesundheitswerte.
- „Trennen“ löscht die Tokens. Für die Daten bei WHOOP gilt die Datenschutzerklärung von WHOOP, Inc.

## 8. Export und Backup

Du kannst alle Daten in eine Datei exportieren und an einem Ort deiner Wahl speichern. Die Datei ist mit deiner **Passphrase verschlüsselt**. Wir haben weder die Datei noch die Passphrase. Eine verlorene Passphrase kann **nicht wiederhergestellt** werden. Der Export enthält keine Anmelde-Tokens.

## 9. Rechtsgrundlagen

- Bereitstellung der App, Konto und Sync: Art. 6 Abs. 1 lit. b DSGVO (Nutzungsvertrag)
- Cloud-KI, WHOOP und Apple-Zugriffe: Art. 6 Abs. 1 lit. a DSGVO (Einwilligung)
- Gesundheitsdaten: Art. 9 Abs. 2 lit. a DSGVO (ausdrückliche Einwilligung)
- Missbrauchsbegrenzung durch den Anfragezähler: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse)

Eine Einwilligung kannst du jederzeit mit Wirkung für die Zukunft widerrufen, indem du die Funktion ausschaltest oder die Freigabe in iOS entziehst.

## 10. Speicherdauer und Löschung

- **Lokale Daten:** bis du sie löschst oder die App entfernst.
- **Konto und Sync-Daten:** bis zur Löschung des Kontos. Du löschst es jederzeit selbst unter **Profil und Einstellungen → Verbindungen → Konto löschen**. Dabei werden sofort alle zugehörigen Server-Daten gelöscht. Hast du dich mit Apple angemeldet, widerrufen wir außerdem die Verknüpfung mit deiner Apple-ID. Du entscheidest, ob die Daten auf dem Gerät erhalten bleiben oder ebenfalls gelöscht werden.
- **iCloud-Daten:** verwaltest du über deine iCloud-Einstellungen.
- **KI-Anfragezähler:** wird mit dem Konto gelöscht.

## 11. Deine Rechte

Du hast das Recht auf Auskunft (Art. 15), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung (Art. 18), Datenübertragbarkeit (Art. 20) und Widerspruch (Art. 21 DSGVO). Wende dich dazu an [E-MAIL]. Du hast außerdem das Recht, dich bei einer Datenschutz-Aufsichtsbehörde zu beschweren, etwa in deinem Bundesland.

## 12. Kinder und Jugendliche

PersOS richtet sich auch an Schülerinnen und Schüler. Für die optionalen Cloud-Funktionen (Konto, Cloud-KI, WHOOP) gilt: Wer jünger als 16 Jahre ist, braucht die Einwilligung der Eltern. Ohne diese Funktionen verarbeitet die App keine Daten außerhalb des Geräts.

## 13. Änderungen

Wir passen diese Erklärung an, wenn sich die App ändert. Das Datum oben zeigt den aktuellen Stand.

---

# Privacy Policy – PersOS

**Last updated:** September 21, 2026

## 1. Controller

Felix Hansmeier
Horstmarer Landweg 84
E-Mail: felix.hansmeier@gmail.com

PersOS is developed by a private individual. No data protection officer has been appointed, as none is required.

## 2. Principle

PersOS works fully **without an account**. Everything you enter is stored **on your device only** by default. There is **no tracking, no analytics, no advertising**, and no sharing with third parties for advertising or analytics. Data leaves your device only if you deliberately turn on one of the features described below.

## 3. Data on your device

The app stores what you enter locally, for example:

- Profile (name, preferred form of address, life stage, active areas)
- Tasks, day planning, notes, goals
- Study and work (timetable, assignments, grades, flashcards)
- Workouts, meals, water

This data lives in the app's database on your device. We have no access to it. It is deleted when you delete the app.

## 4. Apple frameworks

iOS asks for each permission separately. You can revoke them at any time in iOS Settings.

- **Apple Health:** The app reads health values (e.g. HRV, resting heart rate, weight, sleep, steps, VO2 max, SpO2, respiratory rate, blood pressure, blood glucose, body composition, nutrition) to display them. It writes workouts, meals and, if you choose, water to Apple Health. **Health values from Apple Health never leave your device**: they are not synced, not sent to any AI and not transmitted to us.
- **Calendar and Reminders:** to show and create events and reminders. The data stays in your calendar and reminders.
- **Music:** to show the current track during a workout and control playback.

## 5. Optional sync

In Settings you can choose **one** of two sync targets, or leave sync off (default).

### 5.1 Account (Supabase)

- **Sign-in:** with Sign in with Apple or Google. We receive a user ID and the email address that Apple or Google provides (with Apple possibly an anonymous relay address). The privacy policies of Apple or Google also apply to the sign-in itself.
- **Synced data:** the app content listed in section 3, so it is the same on all your devices. **Excluded:** heart rate and energy values of workouts, and all values from Apple Health.
- **Provider:** Supabase Inc. as processor. The database is hosted in a data center in the **EU**. As Supabase Inc. is a US company, access from the US cannot be fully ruled out. This is covered by the EU Standard Contractual Clauses.
- **Signing out** stops sync. Local data is kept.

### 5.2 iCloud

Data is stored in your **private iCloud database** at Apple. It is only accessible with your Apple ID. We cannot read it. Apple's privacy policy applies. Health values stay on the device here as well.

## 6. AI features

- **Default:** AI features run **on your device** (Apple Foundation Models). No data leaves the device.
- **Cloud AI (optional):** only with an account **and** after you turn it on in Settings. Before the first request, the app shows which entries will be sent. Requests go through our server (Supabase, EU) to **Mistral AI SAS (France)**.
- We **neither store nor log** request content. We only store a count of requests per day and account to limit abuse.
- **Health values are never sent to the cloud AI.**
- AI results are only applied when you tap "Apply".

## 7. WHOOP (optional)

If you connect your WHOOP account, you sign in directly with WHOOP (OAuth). The app then fetches recovery, strain and sleep values from the WHOOP API and displays them.

- Access tokens are stored **only in your device's Keychain**, not in sync and not in backups.
- To exchange and refresh tokens, our server (Supabase, EU) forwards the request to WHOOP. **Nothing is stored or logged** in the process.
- WHOOP values stay on the device like all health values.
- "Disconnect" deletes the tokens. WHOOP, Inc.'s privacy policy applies to data held by WHOOP.

## 8. Export and backup

You can export all your data to a file and store it wherever you like. The file is **encrypted with your passphrase**. We have neither the file nor the passphrase. A lost passphrase **cannot be recovered**. The export contains no sign-in tokens.

## 9. Legal bases

- Providing the app, account and sync: Art. 6(1)(b) GDPR (contract)
- Cloud AI, WHOOP and Apple permissions: Art. 6(1)(a) GDPR (consent)
- Health data: Art. 9(2)(a) GDPR (explicit consent)
- Abuse limitation via the request counter: Art. 6(1)(f) GDPR (legitimate interest)

You can withdraw consent at any time with effect for the future by turning the feature off or revoking the permission in iOS.

## 10. Retention and deletion

- **Local data:** until you delete it or remove the app.
- **Account and sync data:** until the account is deleted. You can delete it yourself at any time under **Profile and Settings → Connections → Delete Account**. All associated server data is deleted immediately. If you signed in with Apple, we also revoke the link to your Apple ID. You decide whether the data on the device is kept or deleted as well.
- **iCloud data:** managed through your iCloud settings.
- **AI request counter:** deleted with the account.

## 11. Your rights

You have the right of access (Art. 15), rectification (Art. 16), erasure (Art. 17), restriction (Art. 18), data portability (Art. 20) and objection (Art. 21 GDPR). Contact [EMAIL]. You also have the right to lodge a complaint with a data protection supervisory authority.

## 12. Children

PersOS is also meant for school students. For the optional cloud features (account, cloud AI, WHOOP), users under 16 need parental consent. Without these features the app processes no data outside the device.

## 13. Changes

We update this policy when the app changes. The date at the top shows the current version.
