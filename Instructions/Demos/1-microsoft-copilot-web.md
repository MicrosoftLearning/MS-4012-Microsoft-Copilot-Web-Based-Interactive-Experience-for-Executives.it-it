---
demo:
  title: 'Demo: Microsoft Copilot (copilot.microsoft.com)'
---

[Torna all'indice](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (copilot.microsoft.com)

## Copilot e modelli linguistici di grandi dimensioni

### Punti di discussione

Microsoft Copilot offre un assistente personale basato sull'intelligenza artificiale che può rispondere a domande e fornire assistenza per le attività generali. È possibile porgli domande e l'assistente fornirà risposte simili a quelle che qualunque persona con un'istruzione superiore potrebbe dare.

Quando l'utente o l'organizzazione usano Copilot con protezione dei dati commerciali, la chat non viene salvata. Tutti i dati sono crittografati e Microsoft non conserva alcuna richiesta o risposta. Queste non vengono usate per eseguire il training del modello, pertanto si può essere sicuri che le informazioni personali e quelle dell'organizzazione vengono mantenute riservate.

Ad esempio, è possibile porre una domanda di cultura generale come quella riportata di seguito e ottenere molte informazioni utili. Si può immaginare che Copilot sia dotato di un modello concettuale di base del mondo, che può usare per rispondere alle domande.

**Esempio:**
- **Richiesta:** cosa puoi dirmi sugli elefanti?
- **Risposta:** (discutere la risposta)

Copilot usa modelli di linguaggio di grandi dimensioni (LLM) sottoposti a training con enormi quantità di informazioni, incluse le ricerche e i risultati di Bing. Ma Copilot non è solo un verificatore di fatti. Può essere usato come motore di ragionamento generale, che può riflettere in base a processi stocastici sulle domande che gli vengono poste. Ciò viene chiamata, tra gli addetti ai lavori, inferenza.

**Esempio:**
- **Richiesta:** mi interessa soprattutto la potenza di un elefante. Quanti esseri umani sarebbero necessari per vincere un "braccio di ferro" con un elefante? NOTA: tenere presente l'area e i destinatari, in quanto non tutti conoscono l'espressione "braccio di ferro"; pertanto potrebbe essere necessario fare delle modifiche di conseguenza. 
- **Risposta:** (discutere la risposta)

Copilot è stato in grado di fare ipotesi e di elaborare connessioni tra pezzi di conoscenza per fornire una risposta più articolata alla domanda che gli è stata posta. Man mano che Copilot viene migliorato, si impara molto su ciò che questi LLM riescono a fare bene o non molto bene e tale conoscenza viene aggiunta al prodotto durante la compilazione.

### Passaggi della demo

> **NOTA:** se si desidera usare le proprie richieste, iniziare con un argomento di cultura generale interessante per sé o per il cliente.

1. Per avviare Microsoft Copilot, aprire una nuova scheda del browser Edge e passare a <a href="https://copilot.microsoft.com" target="_blank">copilot.microsoft.com</a>.

1. Accedere a un account Microsoft non aziendale.

    > **NOTA:** se si accede all'account aziendale, si verrà reindirizzati a Business Chat (m365.cloud.microsoft/chat) 

1. Nella casella di testo **Invia messaggio a Copilot** copiare e incollare la richiesta dai documenti della libreria di richieste oppure digitare:

    ```text
    What can you tell me about elephants?
    ```
1. Selezionare il pulsante **Invia**.
1. Nella casella di testo **Invia messaggio a Copilot** copiare e incollare la richiesta:

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. Selezionare il pulsante **Invia**.

## Grounding

### Punti di discussione

Ciò che incrementa ulteriormente questa potenza è la capacità di far sì che Copilot si basi su dati e conoscenze esterni. A volte questa operazione è denominata generazione aumentata di recupero (RAG). Si tratta del processo di fornire informazioni aggiuntive al modello linguistico pertinente per l'attività in questione.

Le domande possono essere basate su tutti i tipi di dati e documenti, ad esempio la relazione sull'occupazione del Bureau of Labor Statistics. Si tratta di un documento corposo, pubblicato annualmente, ricco di dati sulle tendenze nel lavoro e nell'occupazione negli Stati Uniti. Copilot è in grado di individuare queste informazioni, comprenderle e fornire una risposta alla domanda dell'utente in tempo reale. Inoltre, fornisce riferimenti che indicano dove ha ottenuto tali informazioni, ad esempio, sul sito Web del Bureau of Labor Statistics. Ciò significa che è possibile controllare l'origine delle informazioni e ottenere un maggiore contesto, perché si tratta di Copilot e non di Autopilot.

### Passaggi della demo

1. Avviare un nuovo argomento facendo clic su **Visualizza cronologia** e quindi su **Avvia nuova chat**.

1. Nella casella di testo **Invia messaggio a Copilot** copiare e incollare la richiesta:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. Selezionare il pulsante **Invia**.
1. Nella risposta, accanto a **Altre informazioni**, posizionare il mouse su uno o due riferimenti.

## Competenze aggiuntive di Copilot

### Punti di discussione

Tutto ciò è ottimo, ma sarebbe davvero interessante vedere un grafico di questi dati. Sfortunatamente, al momento Copilot non riesce a disegnare un grafico, ma ciò non significa che si sia arrivati a un punto morto. Man mano che Copilot viene compilato, vengono aggiunte competenze diverse. Le competenze sono modi in cui Copilot può attingere alla sua potenza di ragionamento per risolvere i problemi.

Un'altra competenza nota di Copilot è la possibilità di scrivere codice. Si può ricordare a Copilot che è in grado di scrivere codice e vedere se si può indurlo a scrivere il codice Python per il grafico richiesto.

**Esempio:**
- **Richiesta:** puoi fornirmi un elenco dei tassi di partecipazione della forza lavoro registrati dal Bureau of Labor Statistics negli ultimi 5 anni? So anche che puoi scrivere codice. Puoi acquisire i dati da bls.gov e scrivere il codice Python che produrrebbe il grafico che mi interessa?
- **Risposta:** (discutere la risposta)

Nel corso del tempo è probabile che questi tipi di processi diventino più semplici e più automatizzati.

### Passaggi della demo

1. Avviare un nuovo argomento facendo clic su **Visualizza cronologia** e quindi su **Avvia nuova chat**.

1. Nella casella di testo **Invia messaggio a Copilot** copiare e incollare la richiesta:

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. Selezionare il pulsante **Invia**.

## Passaggi facoltativi della demo

### Riconoscimento delle immagini

Innanzitutto scaricare: [**What is this image.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. Avviare un nuovo argomento facendo clic su **Visualizza cronologia** e quindi su **Avvia nuova chat**.

1. Selezionare l'icona + (**+**) nella parte inferiore della pagina.

1. Passare alla posizione in cui è stata scaricata l'immagine, selezionare **What is this picture.png**, quindi selezionare **Apri**.
1. Nella casella di testo **Invia messaggio a Copilot...** digitare la richiesta:

    ```text
    What is this picture?
    ```

1. Selezionare il pulsante **Invia**.

### Mostrare in che modo Copilot può creare immagini

1. Nella casella di testo **Invia messaggio a Copilot** copiare e incollare la richiesta:

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. Selezionare il pulsante **Invia**.

[Torna all'indice](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
