# Eurion OS – Privacy Charter (GDPR-first)

Eurion OS considera privacy e trasparenza requisiti di prodotto.
La raccolta dati serve **solo** a migliorare stabilità, sicurezza e compatibilità.

## 1) Regola base
- Nessuna raccolta dati “nascosta”.
- Nessun “dark pattern”.
- Ogni raccolta dati deve essere:
  - **spiegata**
  - **minimizzata**
  - **controllabile**
  - **disattivabile**

## 2) Impostazione predefinita (Default)
Nelle prime versioni alpha:
- Telemetria: **OFF**
- Crash reports: **OFF**
- Hardware compatibility signals: **OFF**
- Security signals: **ON solo locale** (nessun invio remoto)

## 3) Opt-in e Preview obbligatoria
Qualunque invio dati (se attivato) deve avere:
- **Opt-in reale**
- **Preview obbligatoria**: l’utente vede il payload prima dell’invio
- “Invia una volta”, “Invia sempre”, “Non inviare”

## 4) Dati consentiti (minimi e utili)
### A) Crash & Stability (anonimi)
- versione Eurion OS
- lista pacchetti principali (solo nomi)
- stacktrace tecnico (ripulito)
- dati hardware generici (CPU/GPU model, RAM)

### B) Compatibilità Hardware (per farlo funzionare su tutto)
- ID dispositivo non identificante (no serial, no MAC)
- driver utilizzato
- esito: ok/crash/freeze
- metriche tecniche base (no contenuti utente)

### C) Security Signals (aggregati)
- conteggi/indicatori non sensibili
- eventi tecnici del sistema (es. update fallito)

## 5) Dati vietati (mai)
Eurion OS NON raccoglierà mai:
- contenuti dei file
- nomi file o percorsi personali
- cronologia navigazione
- testo digitato / keylogging
- contenuti chat/mail
- audio/video microfono/camera
- identificatori persistenti traccianti non necessari

## 6) Trasparenza & Controllo
L’utente avrà:
- pannello “Dati & Trasparenza”
- export dati (se presenti)
- cancellazione immediata
- spiegazione semplice del perché

## 7) Retention (conservazione)
Se la telemetria viene abilitata:
- retention breve e dichiarata (es. 30–90 giorni)
- anonimizzazione/pseudonimizzazione ove possibile
- accesso limitato e auditing interno

## 8) Missione
Eurion OS non tratta l’utente come un prodotto.
Eurion OS tratta l’utente come un cittadino.
