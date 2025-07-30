# Scaletta Modifiche Documenti Legali - PodTxt

**Data creazione**: 28 Aprile 2025  
**Stato**: In corso  
**Versione**: 1.0

---

## 📋 Panoramica

Questa scaletta definisce gli interventi necessari per aggiornare e allineare la **Privacy Policy** e i **Terms of Use** ai requisiti:
- ✅ GDPR (Regolamento UE 2016/679)
- ✅ CCPA/CalOPPA (California Consumer Privacy Act)
- ✅ App Store Connect (Apple Privacy Nutrition Labels)
- ✅ Google Play Data Safety
- ✅ Gestione permessi runtime (iOS/Android)
- ✅ Localizzazione multilingue
- ✅ Cookie Policy
- ✅ EULA standard

---

## 🎯 1. Metadati e Versioning

### 1.1 "Last updated" e Changelog
- [ ] Inserire in testa a Privacy Policy e Terms of Use la dicitura "Last updated: 28 April 2025"
- [ ] Aggiungere un breve changelog (data + sintesi modifiche) all'inizio di ogni documento per tracciare evoluzioni e revisioni
- [ ] Creare sistema di versioning semantico (es. v1.0, v1.1, v2.0)

---

## ⚖️ 2. Sezioni Core da Aggiungere o Migliorare

### 2.1 Base giuridiche GDPR e Periodi di Conservazione
- [x] Specificare le base giuridiche del trattamento:
  - [x] Consenso esplicito
  - [x] Esecuzione del contratto
  - [x] Legittimo interesse
  - [x] Obbligo legale
- [x] Definire i periodi di retention giustificati per ciascuna categoria di dati:
  - [x] Dati di navigazione: 6 mesi
  - [x] Dati di contatto: fino alla revoca del consenso
  - [x] Log diagnostici: 12 mesi
  - [x] Documentare le motivazioni per ogni periodo

### 2.2 CCPA / CalOPPA
- [x] Integrare clausole specifiche per i diritti dei consumatori californiani:
  - [x] Shine The Light Law (Sezione 1798.83)
  - [x] Right to Know (diritto di sapere)
  - [x] Right to Delete (diritto di cancellazione)
  - [x] Right to Opt-Out (diritto di rinuncia)
- [x] Aggiungere informazioni su:
  - [x] Arricchimento dati
  - [x] Non discriminazione in base all'esercizio dei diritti
  - [x] Processo di verifica dell'identità

### 2.3 Cookie Policy & Tracking Technologies
- [x] Creare una sezione dedicata alla Cookie Policy:
  - [x] Classificazione cookie per finalità (necessari, analitici, marketing)
  - [x] Opzioni di opt-out chiare
  - [x] Link a cookie notice estesa
- [x] Indicare l'uso di:
  - [x] Web beacon
  - [x] Pixel di tracciamento
  - [x] Tecnologie simili
  - [x] Local storage e session storage

### 2.4 Condivisione con Terze Parti
- [x] Elencare i service provider e le categorie di terze parti:
  - [x] Payment processors (Stripe, PayPal, Apple Pay, Google Pay)
  - [x] Analytics services (Google Analytics, Firebase)
  - [x] Cloud storage (AWS, Google Cloud)
  - [x] Customer support tools (Zendesk, Intercom)
  - [x] Marketing platforms (Mailchimp, SendGrid)
  - [x] App store platforms (Apple App Store, Google Play)
- [x] Descrivere:
  - [x] Misure di sicurezza adottate
  - [x] Accordi di data processing con i sub-processor
  - [x] Trasferimenti internazionali di dati

### 2.5 Misure di Sicurezza ✅ COMPLETATO
- [x] Sintetizzare le misure organizzative e tecniche:
  - [x] Encryption in transit e at rest
  - [x] Backup e disaster recovery
  - [x] Access controls e authentication
  - [x] Security audits e monitoring
- [x] Includere disclaimer sulla sicurezza ("non garantiamo il 100% di protezione")

### 2.6 Diritti degli Interessati ✅ COMPLETATO
- [x] Ampliare le modalità di esercizio dei diritti GDPR:
  - [x] Diritto di accesso
  - [x] Diritto di rettifica
  - [x] Diritto di cancellazione (right to be forgotten)
  - [x] Diritto alla portabilità dei dati
  - [x] Diritto di limitazione del trattamento
  - [x] Diritto di opposizione
- [x] Dettagliare:
  - [x] Processo di verifica dell'identità
  - [x] Tempi di risposta (max 30 giorni)
  - [x] Modalità di contatto

### 2.7 Risoluzione delle Controversie ✅ COMPLETATO
- [x] Snellire le clausole di arbitrato e limitazione di responsabilità
- [x] Spostare dettagli in allegati se necessario
- [x] Mantenere riferimento sintetico nel documento principale

---

## 🏪 3. Requisiti Store

### 3.1 Apple App Store & Privacy Nutrition Labels ✅ COMPLETATO
- [x] Integrare riepilogo conforme alle Privacy Nutrition Labels Apple:
  - [x] "Data Used to Track You"
  - [x] "Data Linked to You"
  - [x] "Data Not Linked to You"
- [x] Assicurarsi che le dichiarazioni in App Store Connect corrispondano esattamente alle policy
- [x] Aggiornare le labels ad ogni nuova versione dell'app

### 3.2 Google Play Data Safety ✅ COMPLETATO
- [x] Preparare la sezione Data safety nel Play Console:
  - [x] Tipologie di dati raccolti
  - [x] Finalità di raccolta
  - [x] Condivisione con terze parti
  - [x] Sicurezza dei dati
- [x] Allegare il link alla Privacy Policy in ogni aggiornamento

---

## 📱 4. Dichiarazioni sui Permessi

### 4.1 iOS Info.plist
- [ ] Aggiungere i campi con spiegazioni contestuali chiare:
  - [ ] `NSCameraUsageDescription` - "Accesso alla fotocamera per scattare foto"
  - [ ] `NSLocationWhenInUseUsageDescription` - "Accesso alla posizione per servizi locali"
  - [ ] `NSMicrophoneUsageDescription` - "Accesso al microfono per registrazioni audio"
  - [ ] `NSPhotoLibraryUsageDescription` - "Accesso alla galleria per selezionare immagini"

### 4.2 Android Runtime Permissions
- [ ] Fornire messaggi di permission rationale che giustifichino l'uso di:
  - [ ] Fotocamera
  - [ ] Posizione
  - [ ] Microfono
  - [ ] Archiviazione
- [ ] Documentare nel manifesto le autorizzazioni
- [ ] Spiegare in-app perché vengono richieste

---

## 🌍 5. Localizzazione

### 5.1 Versioni Multilingue
- [ ] Pubblicare la Privacy Policy e i Terms in:
  - [ ] EN (inglese) - versione principale
  - [ ] IT (italiano) - traduzione completa
  - [ ] CN (cinese) - traduzione completa
- [ ] Creare file separati per ogni lingua
- [ ] Indicare i link nel menu dell'app

### 5.2 Best Practices di Traduzione
- [ ] Garantire coerenza terminologica in tutte le lingue
- [ ] Usare traduttori tecnici o service professionali
- [ ] Verificare conformità legale in ogni giurisdizione
- [ ] Mantenere aggiornate tutte le versioni

---

## 📄 6. EULA (End User License Agreement)
- [ ] Creare o adeguare un EULA standard per l'app che copra:
  - [ ] Licenza d'uso del software
  - [ ] Proprietà intellettuale
  - [ ] Aggiornamenti e modifiche
  - [ ] Limitazioni di responsabilità
  - [ ] Terminazione della licenza
  - [ ] Disposizioni generali

---

## 📁 7. Struttura dei File nell'App

### 7.1 Naming Convention
- [ ] Usare nomi standardizzati:
  - [ ] `privacy_en.html`, `privacy_it.html`, `privacy_cn.html`
  - [ ] `terms_en.html`, `terms_it.html`, `terms_cn.html`
  - [ ] `cookie_policy_en.html`, `cookie_policy_it.html`, `cookie_policy_cn.html`
  - [ ] `eula_en.html`, `eula_it.html`, `eula_cn.html`

### 7.2 Cartelle
- [ ] Organizzare in:
  - [ ] `assets/legal/` o `www/legal/`
  - [ ] Gestione hit di caching
  - [ ] Caricamento via WebView

---

## 🔄 8. Passaggi Operativi

### 8.1 Setup del Repo ✅ COMPLETATO
- [x] Repository `podtxt-legal-docs` creato
- [x] Branch `main` configurato
- [x] File originali committati

### 8.2 Flusso di Commit
- [x] **Primo commit**: versioni originali (`privacy-policy-original.md`, `terms-of-use-original.md`)
- [x] **Secondo commit**: versioni aggiornate con tutte le migliorie elencate
- [ ] **Commit successivi**: modifiche incrementali con changelog

### 8.3 Workflow di Sviluppo
- [ ] Lavorare sui file `*-updated.md`
- [ ] Testare le modifiche localmente
- [ ] Commit con messaggi descrittivi
- [ ] Push al repository
- [ ] Review e approvazione finale

---

## 📊 9. Checklist di Conformità

### 9.1 GDPR Compliance
- [ ] Base giuridiche specificate
- [ ] Periodi di retention definiti
- [ ] Diritti degli interessati dettagliati
- [ ] Misure di sicurezza descritte
- [ ] Trasferimenti internazionali regolamentati

### 9.2 CCPA/CalOPPA Compliance
- [ ] Diritti californiani implementati
- [ ] Processo di opt-out definito
- [ ] Non discriminazione garantita
- [ ] Verifica identità documentata

### 9.3 App Store Compliance
- [ ] Privacy Nutrition Labels aggiornate
- [ ] Dichiarazioni accurate
- [ ] Link policy funzionanti
- [ ] Permessi giustificati

### 9.4 Google Play Compliance
- [ ] Data Safety form completato
- [ ] Categorie dati accurate
- [ ] Condivisione terze parti documentata
- [ ] Sicurezza descritta

---

## 🎯 10. Prossimi Passi

### Fase 1: Preparazione
- [ ] Analisi dettagliata dei documenti attuali
- [ ] Identificazione gap di conformità
- [ ] Definizione priorità modifiche

### Fase 2: Implementazione
- [ ] Aggiornamento Privacy Policy
- [ ] Aggiornamento Terms of Use
- [ ] Creazione Cookie Policy
- [ ] Creazione EULA

### Fase 3: Localizzazione
- [ ] Traduzione in italiano
- [ ] Traduzione in cinese
- [ ] Review legale traduzioni

### Fase 4: Testing e Deploy
- [ ] Test integrazione app
- [ ] Verifica link e WebView
- [ ] Aggiornamento store
- [ ] Deploy finale

---

## 📞 11. Contatti e Risorse

### Team di Sviluppo
- **Lead Developer**: [Nome]
- **Legal Advisor**: [Nome]
- **QA Tester**: [Nome]

### Risorse Utili
- [GDPR Guidelines](https://gdpr.eu/)
- [CCPA Compliance Guide](https://oag.ca.gov/privacy/ccpa)
- [Apple App Store Guidelines](https://developer.apple.com/app-store/review/guidelines/)
- [Google Play Policy](https://play.google.com/about/developer-content-policy/)

---

**Ultimo aggiornamento**: 28 Aprile 2025 