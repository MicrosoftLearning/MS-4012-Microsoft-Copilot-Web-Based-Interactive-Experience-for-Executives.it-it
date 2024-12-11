---
demo:
  title: 'Demo: Copilot in Excel'
---

[Torna all'indice](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft 365 Copilot in Excel

## Configurazione della demo

Scaricare il documento di esempio di Excel [**EV_Charger_Sales_Analysis_v1.xlsx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/raw/refs/heads/master/Resourcefiles/EV_Charger_Sales_Analysis_v1.xlsx). Questo file verrà usato per eseguire i passaggi della demo descritti in questa guida.


## Punti di discussione

Con Microsoft 365 Copilot in Excel tutti possono diventare analisti di dati, grazie alla possibilità di comprendere rapidamente le tendenze chiave, le metriche delle prestazioni e i fattori che orientano i risultati aziendali o dei progetti.

Sia che si usino dati di vendita, report finanziari, feedback dei clienti o metriche operative, Copilot consente di modellare e analizzare le informazioni, fornendo informazioni dettagliate ricavate da set di dati complessi con più origini.

Con Copilot è possibile estrarre facilmente informazioni dettagliate significative per migliorare il processo decisionale, indipendentemente dal tipo di dati o dalla complessità dell'analisi.

## Passaggi della demo

> **NOTA:** prima di procedere assicurarsi di aprire il file di Excel **EV_Charger_Sales_Analysis_v1.xlsx**.

1. **Passare alla scheda "Vendite per prodotto"** nel file di Excel.

1. Usare Copilot per calcolare i ricavi mensili:  

   Iniziare individuando la categoria dell'azienda che sta producendo il maggior numero di ricavi. Questo foglio contiene tre anni di dati sulle vendite, con migliaia di righe che mostrano le vendite per prodotto per mese. Sebbene si tratti di un'attività di routine, può essere difficile gestire un tale volume di dati. È possibile chiedere a Copilot di calcolare rapidamente i ricavi mensili per prodotto.

   Immettere il prompt seguente:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```
    - Copilot sa come eseguire questa operazione e a quali dati fare riferimento tra le varie schede. 
    - Copilot crea un piano per la modalità di esecuzione di tali numeri, esegue il piano mostrando il lavoro svolto progressivamente e chiede di porre domande o di ribadire la soluzione raggiunta.
    - Fare clic su **+Inserisci colonna**, quindi tornare alla scheda **Vendite per prodotto**.
   

1. Usare Copilot per analizzare i ricavi immettendo la richiesta seguente nel riquadro di Copilot:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot eseguirà i numeri e creerà un grafico a barre che potrà essere aggiunto alla cartella di lavoro.
    - Fare clic su **+Aggiungi a un nuovo foglio**, quindi tornare alla scheda **Vendite per prodotto**.

1. A questo punto, usare Copilot per evidenziare i prodotti con vendite basse immettendo la seguente richiesta:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot applicherà la formattazione condizionale, consentendo di individuare i prodotti che non rispettano gli standard stabiliti.

1. **Passare alla scheda "Recensioni"** per analizzare il feedback dei clienti.

1. Chiedere a Copilot di riepilogare le principali preoccupazioni immettendo la richiesta seguente:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot analizzerà il feedback e presenterà le tre principali preoccupazioni dei clienti. Sembra che un problema rilevante sia la velocità con cui viene effettuato l'addebito.

1. Successivamente, evidenziare le recensioni che citano la velocità di addebito immettendo questa richiesta:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot evidenzia tutte le recensioni pertinenti nel set di dati.

### Conclusa

Con l'aiuto di Copilot, sono stati analizzati set di dati complessi e sono state acquisite informazioni dettagliate sulle prestazioni dei prodotti e sul feedback dei clienti. Queste informazioni dettagliate possono essere usate come base per la prossima revisione aziendale.
