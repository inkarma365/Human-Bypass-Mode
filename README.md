Human Cognitive Asymmetry Engine (HCAE)

StatusTypeTarget
🧠 Il Progetto

HCAE è un framework di Prompt Engineering progettato per bypassare i rilevatori di Intelligenza Artificiale (AI Detectors) non alterando superficialmente le parole (come fanno gli spinner), ma modificando l'architettura probabilistica del testo.

La maggior parte dei tool anti-plagio IA (GPTZero, Turnitin, Copyleaks) non rilegge il "senso" del testo, ma si basa su due metriche matematiche:

    Perplexity (Imprevedibilità): Quanto è probabile la scelta della parola successiva. L'IA sceglie sempre la parola con la probabilità più alta (Top-1). Gli umani scelgono parole meno ovvie (Top-3 o Top-5).
    Burstiness (Ritmo): La variazione di lunghezza e struttura delle frasi. L'IA scrive frasi omogenee (15-20 parole). Gli umani alternano frasi lunghissime a frammenti di 3 parole.

⚙️ Come Funziona (La Metodologia)

Invece di chiedere all'LLM "scrivi come un umano" (che risulta in un testo finto-colloquiale e facilmente rilevabile), HCAE impone regole sintattiche rigide che rompono i pattern matematici del modello.

Il processo si basa su 5 pilastri:

    Rottura del Pattern SVO (Soggetto-Verbo-Oggetto): Spostamento deliberato delle subordinate all'inizio delle frasi per eliminare la monotonia strutturale tipica dell'IA.
    Iniezione di Burstiness: Forzatura matematica dell'alternanza tra frasi complesse (subordinate multiple) e frasi "tagliate" (max 6 parole).
    Elevazione della Perplexity: Divieto assoluto di connettivi ad alta probabilità (Inoltre, Pertanto, D'altra parte) e uso di lemmi sub-ottimali (la seconda o terza scelta del modello).
    Distruzione del Parallelismo: Trasformazione delle liste puntate logiche in paragrafi discorsivi asimmetrici. I dati tecnici vengono integrati nel testo, non elencati.
    Micro-colloquialismi Accademici: Inserimento di "crepe umane" accettabili in un contesto formale (es. "Per essere sinceri", "Nessuno lo nega"), che simulano il carico cognitivo di uno studente o ricercatore che spiega un concetto complesso.

🚀 Perché non usare semplici "Parafasatori" (Quillbot, WordAI)?

I parafrasatori sostituiscono i sinonimi ma mantengono intatta la sintassi perfect-pattern dell'IA. I detector moderni analizzeranno la struttura della frase e lo classificheranno comunque come "AI-generated". HCAE agisce a livello di generazione sintattica, rendendo il testo matematicamente umano fin dalla prima stesura.
🛠️ Come utilizzare questo Repo

    Clona o scarica la repository.
    Apri il file prompt.md.
    Copia il System Prompt contenuto nel file.
    Incollalo come istruzione di sistema (o come primo messaggio) in ChatGPT, Claude o qualsiasi altro LLM.
    Inserisci il testo da riscrivere subito dopo il prompt.

📌 Use Case Ideali

    Pubblicazione accademica e seminari universitari.
    Content Marketing e SEO (dove Google penalizza i contenuti AI-spidi).
    Emailing professionale.
    Documentazione tecnica che richiede un tono "umano".

📄 Licenza

Questo progetto è open-source e rilasciato sotto licenza MIT. Sentiti libero di adattare il prompt alle tue esigenze linguistiche specifiche.
