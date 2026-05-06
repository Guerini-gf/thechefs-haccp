# 🍳 THE CHEFS — HACCP Software

**Applicazione web completa per la gestione dell'autocontrollo alimentare HACCP in ristoranti e trattorie.**

Sviluppata da **SOFTTHECHEFS** — pensata da chef, per chef.

---

## Cosa fa

THE CHEFS è un'applicazione single-file HTML che gestisce l'intero sistema di autocontrollo HACCP richiesto dalla normativa europea (Reg. CE 852/2004, Reg. UE 1169/2011). Funziona offline, salva tutto in localStorage, e si sincronizza tra dispositivi tramite Firebase.

Un solo file. Nessun server. Nessun abbonamento. Apri e lavori.

---

## Funzionalità

### Registri giornalieri
- **Temperature** — Frigo, freezer, abbattitore, mantenitore. Alert automatico fuori range.
- **Merci in Entrata** — Scanner barcode USB/webcam, scan fattura con AI (riconoscimento automatico prodotti e fornitore), alert scadenze a 3/7 giorni.
- **Pulizie** — Checklist giornaliera per zona, storico mensile, percentuale completamento.

### Menu e cucina
- **Menu del Giorno** — Database 500+ piatti italiani, selezione rapida per categoria, stampa A5.
- **Menu Fisso** — Editabile con allergeni, stampa A5 multipagina fedele al formato cartaceo (copertina, piatti, vegano/GF, legenda allergeni, storia del locale).
- **Ricette** — Archivio con ingredienti, procedimento, food cost calcolato.
- **Etichette Post-Cottura** — Stampa etichette con dati di produzione, abbattimento, scadenza, lotto.
- **Ordini Merce** — Generazione ordini per fornitore.

### 16 Schede HACCP
- Rapporto Non Conformità
- Controllo Infestanti Trimestrale
- Validazione Cottura
- Conservabilità
- Allergeni Somministrazione
- Forniture
- Registro Abbattitore
- Registro Produzioni
- Campionamenti
- Fornitori MOCA
- Disinfestazione
- Registro Sanificazione Mensile
- **Gestione Olio Frittura** — Test composti polari, cambio olio, alert >25%
- **Decongelamento** — Prodotto, metodo, temperature, tempi
- **Formazione Personale** — Attestati con scadenze, alert rinnovo automatico
- **Allergeni per Servizio** — Registro comunicazione al cliente (Reg. UE 1169/2011)

### Stampa e ispezioni
- **Stampa Mensile** — Fascicolo completo del mese con tutti i registri selezionabili.
- **Dossier Ispezione** — Stampa per periodo (dal/al). Se l'ispettore arriva il giorno 8, stampi dal 1 all'8. Copertina con anagrafica, tutti i registri, spazio firma.
- **Dashboard Salute** — Quadro a colpo d'occhio: prodotti scaduti, attestati in scadenza, NC aperte, temperature fuori range, pulizie del giorno.

### AI integrata
- **Chef Plane AI** — Assistente intelligente integrato (Groq, gratuito). Risponde su HACCP, ricette, food cost, allergeni, anti-spreco, menu.
- **Scan Fattura AI** — Fotografa la fattura fornitore, l'AI riconosce prodotti, quantità, lotti, prezzi e nome fornitore. Import diretto nel registro merci.

### Sincronizzazione
- **Firebase Realtime Database** — Sincronizza PC e mobile con un URL. Stesso database per tutti i dispositivi.
- **Export CSV** — Temperature, merci, pulizie, etichette, menu.
- **Backup JSON** — Scarica/importa tutto.

---

## Requisiti

- Un browser moderno (Chrome, Edge, Safari, Firefox)
- Nient'altro

Per le funzioni AI: una API key gratuita da [console.groq.com](https://console.groq.com)

Per la sincronizzazione: un progetto Firebase gratuito con Realtime Database

---

## Installazione

1. Scarica `TheChefs_HACCP_v7.html`
2. Aprilo nel browser
3. Fine

Non serve server, non serve installazione, non servono dipendenze.

---

## Struttura

```
TheChefs_HACCP_v7.html    ← Applicazione completa (single-file)
README.md                  ← Questo file
```

Tutto è contenuto in un unico file HTML: CSS, JavaScript, database piatti, logica HACCP, stampa, AI.

---

## Normativa coperta

- **Reg. CE 852/2004** — Igiene dei prodotti alimentari
- **Reg. UE 1169/2011** — Informazioni al consumatore sugli alimenti (allergeni)
- **D.Lgs. 193/2007** — Sanzioni per violazioni HACCP
- **Linee guida regionali** — Formazione alimentaristi, autocontrollo

---

## Licenza

© 2026 The Chefs — SOFTTHECHEFS. Tutti i diritti riservati.

Nessuna parte di questa pubblicazione può essere riprodotta, distribuita o trasmessa in qualsiasi forma o con qualsiasi mezzo senza il preventivo consenso scritto dell'autore.

---

## Contatti

Per informazioni, collaborazioni o proposte commerciali:

**SOFTTHECHEFS**

*Pensato da chef, per chef. Perché il tempo in cucina non è mai abbastanza.*
