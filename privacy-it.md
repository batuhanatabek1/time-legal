# TiMe — Informativa sulla privacy

**Ultimo aggiornamento:** 13 novembre 2026
**In vigore dal:** 13 novembre 2026

> Questa è una traduzione. In caso di discrepanze prevale la versione
> inglese o turca.

---

## In breve

TiMe è un'app per monitorare il ciclo mestruale. I tuoi dati sono
**salvati sul tuo dispositivo per impostazione predefinita.** Non serve un
account. Non conserviamo i tuoi dati sul ciclo sui nostri server. Non
condividiamo dati con reti pubblicitarie. Le statistiche di utilizzo funzionano solo se le attivi nelle Impostazioni; i tuoi dati sanitari non finiscono mai nelle statistiche.

I tuoi dati lasciano il dispositivo solo in questi casi, ognuno sotto il tuo controllo:

1. **Commenti IA e chat** — quando attivi il modello online per la chat o quando il modello sul dispositivo non è
   disponibile e hai dato il consenso
2. **Scambio con Apple Salute (HealthKit)** — quando concedi il permesso
3. **Acquisti di abbonamenti**
4. **Segnalazioni di arresto anomalo e statistiche di utilizzo** — le segnalazioni sono attive per impostazione predefinita e si possono disattivare; le statistiche solo se le attivi

Dettagli qui sotto.

---

## 1. Titolare del trattamento

| | |
|---|---|
| Nome | Batuhan Atabek |
| Indirizzo | Antalya, Turchia — le richieste possono essere inviate via email |
| Email | atabeksoft+privacy@gmail.com |

Questa informativa si applica all'app TiMe per iOS.

---

## 2. Dati trattati

### 2.1 Dati che restano sul dispositivo

Salvati nel database locale del dispositivo e **mai inviati ai nostri
server:**

- Date di inizio e fine delle mestruazioni, durata dei cicli
- Intensità del flusso
- Sintomi (fisici, umore, perdite, pelle, digestione, sonno, energia)
- Registrazioni dell'attività sessuale
- Temperatura basale, peso, risultati dei test di ovulazione
- Le tue note a testo libero
- Preferenze dell'app (lingua, unità, orari dei promemoria)
- La cronologia della chat con l'IA

Alcuni di questi dati rientrano nelle **categorie particolari di dati**
(dati sanitari e relativi alla vita sessuale) ai sensi dell'art. 9 del
GDPR. Per questo la nostra architettura predefinita è l'archiviazione sul
dispositivo.

### 2.2 Dati che possono lasciare il dispositivo

**a) Commenti IA e chat**

TiMe usa prima **il modello di IA del tuo dispositivo** per generare i
commenti. In questo caso nessun dato lascia il dispositivo.

Se hai dato il consenso, puoi anche attivare "Chat più completa con il modello online" in Impostazioni. Se attiva, i messaggi della chat vanno prima al modello online secondo le regole qui sotto, anche se il dispositivo supporta il modello sul dispositivo. È disattivata per impostazione predefinita e non riguarda i commenti singoli.

Se il dispositivo non supporta questo modello, ti viene chiesto una volta
e **solo con il tuo consenso** vengono inviati, tramite connessione
crittografata, a un server proxy e da lì a un fornitore di IA:

Inviati:
- La durata dei tuoi cicli (solo numeri)
- La fase attuale del ciclo
- Le etichette dei sintomi che hai scelto
- I messaggi **che scrivi** in chat
- La lingua dell'interfaccia

Non inviati:
- Nome, email, data di nascita
- Posizione
- Identificativo del dispositivo o pubblicitario
- Date esatte
- Note a testo libero delle registrazioni giornaliere

Puoi revocare il consenso in qualsiasi momento da Impostazioni. L'app
torna allora ai commenti basati su regole e continua a funzionare.

**Importante:** il testo che scrivi in chat viene trasmesso al fornitore
così com'è. Ti consigliamo di non scrivere in chat informazioni che
possano identificarti.

**b) Apple Salute (HealthKit)**

Con il tuo permesso, flusso mestruale, temperatura basale e dati correlati
vengono scambiati con Apple Salute. Questi dati restano sul dispositivo e
non vengono inviati a noi.

**Non usiamo i dati HealthKit per pubblicità, marketing o data mining e
non li condividiamo con terzi.**

**c) Abbonamenti**

Gli acquisti sono gestiti da Apple. **Non abbiamo accesso ai tuoi dati di
pagamento.** Usiamo RevenueCat per verificare lo stato dell'abbonamento;
vengono inviati solo un identificativo utente anonimo e lo stato
dell'abbonamento, mai i dati sul ciclo.

**d) Prevenzione degli abusi**

Per prevenire abusi delle richieste IA, sul dispositivo viene creato un
identificativo casuale (UUID). Non può essere collegato a te, serve solo
a contare le richieste giornaliere e si azzera quando elimini l'app.

**e) Segnalazioni di arresto anomalo e statistiche di utilizzo (Google Firebase)**

- **Segnalazioni di arresto anomalo (Firebase Crashlytics):** se l'app si arresta, vengono inviati a Google il punto del codice in cui si è verificato l'errore, il modello del dispositivo, la versione di iOS, la versione dell'app e un identificativo di installazione casuale. La segnalazione non contiene cicli, sintomi, note né altri dati sanitari. Attive per impostazione predefinita; disattivale in Impostazioni > Privacy > «Segnalazioni di arresto anomalo».
- **Statistiche di utilizzo (Firebase Analytics):** **disattivate** per impostazione predefinita; funzionano solo se attivi Impostazioni > Privacy > «Statistiche di utilizzo». Se attive, vengono inviati quali schermate principali vengono aperte, il completamento della configurazione, la visualizzazione della schermata di abbonamento e i passaggi di acquisto (nome del prodotto compreso), insieme a un identificativo dell'app casuale. Cicli, sintomi, date, note e contenuti della chat non vengono **mai** inviati. Vengono inviati anche il fatto che è stato inviato un messaggio in chat (senza contenuto) e l'esito del ripristino degli acquisti. Firebase registra inoltre automaticamente informazioni di base come la prima apertura, l'inizio della sessione, il tempo di utilizzo, il modello del dispositivo, la versione di iOS e il paese approssimativo ricavato dall'indirizzo IP. L'identificativo pubblicitario (IDFA) non viene raccolto e la pubblicità personalizzata è disattivata. Disattivando l'opzione, l'identificativo di analisi sul dispositivo viene eliminato.

### 2.3 Dati che non raccogliamo

- Nome, email, numero di telefono
- Posizione
- Identificativo pubblicitario (IDFA)
- Contatti, foto, fotocamera, microfono
- Qualsiasi statistica che contenga dati sanitari

### 2.4 Funzioni non offerte al momento

L'app **non** offre la sincronizzazione cloud (iCloud). I tuoi dati non
vengono sincronizzati tra dispositivi. Se questa funzione verrà aggiunta,
l'informativa sarà aggiornata e il tuo consenso richiesto separatamente.

---

## 3. Base giuridica (GDPR)

| Finalità | Dati | Base giuridica |
|---|---|---|
| Previsione e monitoraggio del ciclo | Dati su ciclo e sintomi | Consenso esplicito, art. 9(2)(a) |
| Commenti IA (sul dispositivo) | Dati su ciclo e sintomi | Consenso esplicito |
| Commenti IA (online) | Dati di cui al §2.2(a) | Consenso esplicito separato |
| Integrazione con Apple Salute | Dati sanitari | Consenso esplicito |
| Notifiche | Date previste, orari scelti | Consenso |
| Gestione dell'abbonamento | ID anonimo, stato dell'abbonamento | Contratto, art. 6(1)(b) |
| Prevenzione degli abusi | Identificativo casuale del dispositivo | Legittimo interesse, art. 6(1)(f) |

---

## 4. Trasferimenti internazionali

Se acconsenti ai commenti IA online, i dati elencati al §2.2(a) vengono
trasferiti a server fuori dal tuo paese.

| Destinatario | Ruolo | Paese |
|---|---|---|
| Cloudflare, Inc. | Server proxy | USA |
| Google LLC | Fornitore di IA — commento singolo (Gemini) | USA |
| Anthropic, PBC | Fornitore di IA — chat (Claude) | USA |
| Google LLC | Segnalazioni di arresto anomalo e statistiche di utilizzo (Firebase) — §2.2(e) | USA |

I trasferimenti per l'IA e per le statistiche di utilizzo si basano sul tuo **consenso esplicito.** Le segnalazioni di arresto anomalo non contengono dati sanitari; se non vuoi inviarle, disattivale nelle Impostazioni. Senza consenso per l'IA, i tuoi dati su ciclo e sintomi non vengono trasferiti e l'app continua a funzionare sul dispositivo.

Il nostro proxy **non registra** i tuoi dati sanitari.

Condizioni dei fornitori:
- Google: https://ai.google.dev/gemini-api/terms
- Google Firebase: https://firebase.google.com/support/privacy
- Anthropic: https://www.anthropic.com/legal/commercial-terms

---

## 5. Conservazione

- **Dati sul dispositivo:** finché non li elimini. Eliminare l'app li
  elimina.
- **Dati inviati al fornitore di IA:** non li conserviamo dopo la
  generazione della risposta.
- **Identificativo anti-abuso:** 24 ore.
- **Segnalazioni di arresto anomalo:** fino a 90 giorni presso Google Firebase.
- **Statistiche di utilizzo:** dati a livello di evento fino a 2 mesi presso Google Analytics.
- **Dati sugli abbonamenti:** come richiesto dalla legge, presso Apple e
  RevenueCat.

---

## 6. I tuoi diritti

Ai sensi del GDPR hai diritto di accesso, rettifica, cancellazione,
limitazione del trattamento, portabilità, opposizione e di revocare il
consenso in qualsiasi momento. Puoi anche proporre reclamo all'autorità di
controllo (in Italia, il Garante per la protezione dei dati personali).

**In pratica:** poiché la maggior parte dei tuoi dati si trova solo sul
dispositivo, puoi esercitare diversi diritti direttamente nell'app:

- **Accesso / portabilità:** Impostazioni → Esporta i tuoi dati
- **Cancellazione:** Impostazioni → Elimina tutti i dati
- **Revoca del consenso:** Impostazioni → Consenso IA

Per altre richieste: atabeksoft+privacy@gmail.com. Rispondiamo entro 30
giorni.

---

## 7. Minori

TiMe non è rivolta a minori di 13 anni e non raccogliamo consapevolmente i
loro dati. Se sei un genitore o tutore e pensi che tuo figlio o tua figlia
usi l'app, scrivi a atabeksoft+privacy@gmail.com.

---

## 8. Sicurezza

- I dati sono salvati nella sandbox standard delle app iOS.
- Blocco facoltativo dell'app (Face ID / Touch ID).
- Tutto il traffico di rete è crittografato con TLS.
- Il nostro proxy non registra dati sanitari.
- I dati inviati al fornitore di IA sono ridotti al minimo.

Nessun sistema è completamente sicuro. Ti consigliamo di tenere aggiornato
il dispositivo e di usare un codice di accesso.

---

## 9. Avvertenza medica

TiMe serve per informazione e monitoraggio personale. **Non è una diagnosi
medica, un trattamento né un metodo contraccettivo.** Le previsioni sono
statistiche e possono essere errate. Per le decisioni sulla tua salute
rivolgiti a un professionista sanitario.

---

## 10. Modifiche

Se modifichiamo questa informativa mostreremo un avviso nell'app e
aggiorneremo la data qui sopra. Per modifiche sostanziali ti chiederemo di
nuovo il consenso.

---

## 11. Contatti

**Batuhan Atabek**
Antalya, Turchia — le richieste possono essere inviate via email
atabeksoft+privacy@gmail.com
