---
title: Istruzioni ospitate online
permalink: index.html
layout: home
---

# MS-4012: Esperienza interattiva di Microsoft Copilot per dirigenti 

## Directory contenuto

Le demo per questo corso sono basate sulle demo del kit acceleratore [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

È importante acquisire familiarità con le demo prima di tenere questa formazione. Per diversi laboratori, verranno utilizzati documenti di esempio, riunioni e messaggi di posta elettronica di Teams creati in modo preliminare.

- Pre-scaricare tutti i documenti di esempio [qui](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles).
- Configurare riunioni e thread di posta elettronica di Teams seguendo le istruzioni riportate [qui](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Acquisire familiarità con l'esperienza interattiva disponibile [qui](https://aka.ms/CopilotWebEE).



## Descrizione del corso

Esplorare il potenziale trasformativo di Microsoft Copilot e il suo impatto sull'efficienza organizzativa. Progettata per dirigenti e responsabili aziendali senza una licenza Copilot, questa esperienza esplora l'arte di creare richieste efficaci, offre un'esperienza interattiva e dimostra come Microsoft 365 Copilot possa integrarsi facilmente nei flussi di lavoro aziendali giornalieri per aumentare la produttività e l'innovazione.

Gli obiettivi principali di questa esposizione sono:

- Insegnare come creare richieste efficaci
- Illustrare Microsoft Copilot (ambito Web) e guidare i partecipanti attraverso un'esperienza interattiva
- Illustrare Microsoft 365 Copilot nelle app di Office (fino a 3 demo)
- Invitare i partecipanti a scaricare e provare Microsoft Copilot per dispositivi mobili

## Tempistiche del corso (stima) 

| # | Argomento                                 | Dettagli                                                                                          | Total Time      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | Creare richieste efficaci in Microsoft Copilot per Microsoft 365 | - Diapositiva sull'arte di formulare richieste <br> - Diapositiva sulla compilazione delle richieste <br> - Diapositiva sui lab relativi a Copilot | 10 minuti    |
| 2 | Microsoft Copilot sul Web          | - Demo di Microsoft Copilot (modalità Web) <br> - Esperienza interattiva  <br> - Diapositiva per condividere la propria esperienza | 30 minuti      |
| 3 | Microsoft 365 Copilot per il lavoro     | - Diapositiva di Microsoft Graph <br> - Demo di Copilot in Word, Microsoft Copilot (modalità di lavoro), Copilot in Outlook e Copilot in Teams <br> - Diapositiva testimonial <br> - Diapositiva di Microsoft Copilot per dispositivi mobili | 20 minuti      |
|   |                                       |                                                                                                  | **Tempo totale 60 minuti** |


In basso sono elencati i collegamenti ipertestuali a tutti i lab.

## Demo

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
