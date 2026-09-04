# AI-MED: Innovazione Data-Driven nella Farmacologia Oncologica 🧬💊

> **Progetto per il Master in AI e Agenti AI per il Business**  
> *Autore:* Lorenzo D'Angeli  
> *Ambito:* Agenda ONU 2030 – SDG 3: Salute e Benessere  

---

## 🎯 Context & Problema

Il processo tradizionale di Ricerca e Sviluppo (R&D) in ambito farmacologico oncologico presenta inefficienze critiche che rallentano l'accesso a cure efficaci e sostenibili:

* **Tempistiche estese**: occorrono circa **12 anni** per sviluppare e validare un nuovo farmaco.
* **Costi elevati**: il costo medio per progetto supera i **2 miliardi di euro**.
* **Alto tasso di fallimento**: circa il **90% dei candidati molecolari fallisce** nelle fasi avanzate per inefficacia o tossicità inaspettata.

---

## 💡 Proposta di Soluzione: AI-MED

**AI-MED** è una piattaforma concettuale di *in silico screening* e *de-novo design* che digitalizza la fase pre-clinica della ricerca oncologica. Sostituendo i test fisici a tentativo con simulazioni computazionali e algoritmi predittivi, la soluzione agisce come un **"Filtro Intelligente"** a tre stadi:

1. **Analisi Digitale**: Screening virtuale simultaneo di milioni di strutture molecolari.
2. **Machine Learning Predittivo**: Stima della probabilità di inibizione del target tumorale (modello *Serratura e Chiave*).
3. **AI Generativa (De-Novo Design)**: Progettazione *ex-novo* di molecole ottimizzate per la massima efficacia e la minima tossicità.

---

## 📊 Dati e Fonti

### Dati Richiesti per l'Implementazione
* **Dati Biochimici & Attività**: Parametri di affinità di legame, dati di inibizione e misura della potenza molecolare (pIC<sub>50</sub>).
* **Dati Strutturali 3D**: Conformazioni tridimensionali delle proteine bersaglio tumorali e dei complessi ligando-proteina.

### Fonti e Database di Riferimento
* **ChEMBL Database (EMBL-EBI)**: Per il recupero dei dati di bioattività molecolare.
* **RCSB Protein Data Bank (PDB)**: Per l'estrazione delle strutture molecolari 3D.
* **Tufts Center for the Study of Drug Development (CSDD)**: Per i dati statistici su costi, tempi e tassi di attrito R&D.
* **World Health Organization (WHO) & UN SDG 3**: Per il quadro epidemiologico e gli obiettivi globali di salute.

---

## 🤖 Modello Machine Learning, Metriche e Benefici

### Ruolo del Machine Learning
Il modello opera come un classificatore binario e regressore: riceve in input la coppia molecola-target biologico e restituisce la probabilità (0-100%) che il composto riesca a inibire la proteina tumorigena.

### Metriche di Misurazione
* **Metriche ML (Valutazione Algoritmica)**: Area Under Curve (**AUC-ROC**) e curve **Precision-Recall** per massimizzare l'identificazione di composti attivi e azzerare i falsi positivi.
* **Metriche Sperimentali**: **Hit Rate** (percentuale di successo confermata dai successivi test *in vitro*).

### Quantificazione dei Benefici
* **Economici**: Riduzione drastica dei costi R&D legati alla sperimentazione fisica a vuoto.
* **Temporali**: Significativa contrazione del *Time-to-Market* dei farmaci candidati.

---

## 🌍 Impatto Sociale e Ambientale (SDG 3)

* **Impatto Sociale**: Democratizzazione dell'accesso alle terapie oncologiche e accelerazione della ricerca per patologie a bassa frequenza o tumori rari.
* **Impatto Ambientale**: Riduzione dell'impronta ecologica della R&D farmaceutica grazie alla diminuzione dell'impiego e dello smaltimento di reattivi, solventi chimici e materiale di scarto nei laboratori tradizionali.

---

## 👥 Figure Professionali Necessarie

La realizzazione e l'operatività di AI-MED richiedono un team multidisciplinare:

1. **Data Scientist / AI Engineer**: Sviluppo, addestramento e ottimizzazione dei modelli di ML e Deep Learning.
2. **Bioinformatico**: Traduzione, pulizia e *feature engineering* dei dati biologici e molecolari.
3. **Chimico Farmaceutico**: Validazione chimica, sintesi e pianificazione dei test di laboratorio sui candidati selezionati.
4. **Project Manager**: Coordinamento cross-funzionale del passaggio della soluzione dalla fase computazionale a quella clinica.

---

## 📁 Documentazione Repository

* `Progetto Intro Data Science di Lorenzo D'Angeli.pdf`: Presentazione ufficiale del progetto con analisi di dettaglio.
