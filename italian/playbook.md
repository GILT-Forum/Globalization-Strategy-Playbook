 
# Guida alle strategie di globalizzazione     
### *Una guida per i professionisti della localizzazione e della globalizzazione*
---
## Cronologia della revisione del documento

| Versione| Data della revisione  | Descrizione                   |
| ------- | --------------------  | ----------------------------- |
| v1.0    | 15 ottobre 2021       | Documento Markdown pubblicato |

 
 
 **Autori: Strategic Thinking Group**
   
         Melissa Biggs (Locale Solutions)
         Wayne Bourland (Dell Technologies)
         Karen Combe (Combe Consulting)
         Francesca Di Marco (Pinterest)
         Loïc Dufresne de Virel (Intel)
         Mimi Hills (Hillstra Associates)
         Natalia Levitina (PTC)
         Christian Redmann (Siemens Digital Industries Software)
         Lyena Solomon (ServiceNow)
         Jean-François Vanreusel (Adobe)
         Erji Wang (VMware)
         Lorna Whelan (Tripadvisor)


## Recensioni

Un ringraziamento speciale va ai professionisti del settore della localizzazione elencati di seguito che hanno rivisto questa Guida alle strategie di globalizzazione. 

Questo è ciò che hanno detto: 

*"Questa Guida alle strategie di globalizzazione è un testo completo, utile ed esplicativo per tutti i professionisti che si occupano di sviluppare, gestire o guidare la globalizzazione".*

**EDITH BENDERMACHER**, Head of Globalization Strategy, Localization Operations presso NetApp

*"La Guida alle strategie di globalizzazione offre ai globalization leader consigli pratici e diretti. Il suo formato invita i lettori a considerare quali sono gli obiettivi principali delle loro organizzazioni mentre affrontano le sfide poste dalla creazione di una visione critica. In questo modo, la guida assume il ruolo di un maestro attento, che incoraggia l'introspezione piuttosto che l'aderenza a principi assoluti. Questo è esattamente ciò di cui i leader hanno bisogno per affrontare il complesso e sfaccettato mondo della globalizzazione".*

**ADAM YOUNGFIELD**, Global Manager, Translation Operations presso la Church of Jesus Christ of Latter-day Saints

*"Questa guida strategica, scritta da leader G11N che in totale vantano 200 anni di esperienza nel settore, copre tutti gli aspetti della strategia L10N, dalle lingue alla tecnologia, passando per gli stakeholder, la qualità e altro ancora. È una lettura obbligata per chiunque, sia per chi si approccia alla globalizzazione sia per chi ne ha già esperienza".*

**JENNY KANG**, Director, Globalization presso Veritas

## Informazioni su licenza e restrizioni
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />

Come indicato dalla[ di Licenza di Creative Commons "Attribuzione-NonCommerciale-CondividiAlloStessoModo"](https://creativecommons.org/licenses/by-nc-sa/4.0/), **non è in alcun modo consentito** l'uso del materiale per[ scopi commerciali](https://creativecommons.org/faq/#does-my-use-violate-the-noncommercial-clause-of-the-licenses) (ossia per la pubblicazione e/o monetizzazione del documento).

**È consentito** l'uso del contenuto di questo materiale a condizione del rispetto dei termini di utilizzo della[ licenza](https://creativecommons.org/licenses/by-nc-sa/4.0/) per i seguenti scopi:



1. Migliorare il ROI della vostra azienda impostando o migliorando i processi di localizzazione e globalizzazione;
2. Istruzione e formazione.

Come indicato dai termini della licenza, è sempre necessario citare in modo appropriato gli autori, fornire un link alla [licenza](https://creativecommons.org/licenses/by-nc-sa/4.0/) e indicare se sono state apportate modifiche. È possibile farlo in qualsiasi modo ragionevole, ma non in modo che suggerisca che chi concede la licenza appoggi voi o l'uso che ne fate. Se modificate, ampliate o trasformate il materiale, i vostri contributi dovranno essere distribuiti secondo la stessa licenza del documento originale.




## Sommario


<!-- vscode-markdown-toc -->

- [Capitolo 1: Scopo e vision](#chapter-1-purpose-and-vision)
    - [Pensiero strategico e fasi di pianificazione](#strategic-thinking-and-planning-steps)
      - [Fase 1. La vision della vostra organizzazione](#step-1-your-organization-vision)
      - [Fase 2. La strategia della vostra organizzazione](#step-2-your-organization-strategy)
      - [Fase 3. Esecuzione del vostro piano](#step-3-execution-of-your-plan)
    - [Ringraziamenti](#acknowledgements)
- [Capitolo 2: Panoramica della strategia](#chapter-2-strategy-overview)
    - [Valutare la vostra azienda rispetto all'Azienda ideale](#assessing-your-company-against-the-ideal-company)
      - [Strategia linguistica](#language-strategy)
      - [Internazionalizzazione](#internationalization)
      - [Fusioni e acquisizioni](#mergers-and-acquisitions)
      - [R&S-CICD, UX](#RDCICD-UX)
      - [Processo di sviluppo del prodotto](#product-development-process)
      - [Informazioni finanziarie](#finance-information)
      - [Procurement](#procurement)
      - [IT](#it)
    - [La strategia della vostra azienda](#your-company-strategy)
    - [Creare una strategia di reparto](#building-a-department-strategy)
- [Capitolo 3: Stakeholder - Coinvolgimento e comunicazione strategici](#chapter-3-stakeholdersstrategic-engagement-and-communication)
    - [Definire i vostri stakeholder](#defining-your-stakeholders)
    - [Capire i tipi di stakeholder](#understanding-types-of-stakeholders)
      - [Stakeholder primari #1](#primary-stakeholders-1)
      - [Stakeholder primari #2](#primary-stakeholders-2)
      - [Stakeholder primari #3](#primary-stakeholders-3)
      - [Stakeholder secondari](#secondary-stakeholders)
      - [Stakeholder primari ma troppo spesso "dimenticati"](#primary-but-too-often-forgotten-stakeholders)
      - [Altri stakeholder indiretti](#other-indirect-stakeholders)
    - [Coinvolgere i vostri stakeholder](#engaging-with-your-stakeholders)
    - [Gli stakeholder come partner strategici](#stakeholders-as-strategic-partners)
    - [Best practice a portata di mano](#best-practices-at-hand)
- [Capitolo 4: Strategia linguistica](#chapter-4-language-strategy)
    - [Definire la strategia linguistica](#defining-the-language-strategy)
    - [La rilevanza della strategia linguistica](#the-relevance-of-language-strategy)
    - [Partner e pubblico per la strategia linguistica](#partners-and-audience-for-language-strategy)
      - [Stakeholder chiave](#key-stakeholders)
      - [Fattori chiave della strategia linguistica](#drivers-of-language-strategy)
    - [Costruire la strategia](#building-the-strategy)
    - [Componenti e allineamento](#components-and-alignment)
    - [Governance: best practice per la supervisione della strategia linguistica](#governance-best-practices-for-language-strategy-oversight)
    - [Comprensione approfondita della strategia linguistica](#deeper-understanding-of-language-strategy)
      - [Lingua parlata o scritta](#spoken-or-written)
      - [Considerazioni linguistiche e culturali che influiscono sulla localizzazione](#linguistic-and-cultural-considerations-impacting-localization)
    - [Una strategia linguistica di successo](#a-successful-language-strategy)
- [Capitolo 5: Strategia tecnologica](#chapter-5-technology-strategy)
    - [Cos'è una strategia tecnologica di globalizzazione?](#what-is-a-globalization-technology-strategy)
    - [Creare e implementare la vostra strategia tecnologica](#create-and-implement-your-technology-strategy)
      - [Dimostrare il valore](#demonstrate-value)
      - [Mappatura degli obiettivi aziendali agli strumenti](#map-business-objectives-to-tools)
      - [Modello di maturità tecnologica](#technology-maturity-model)
      - [Capire a che punto siete nel modello di maturità tecnologica](#understand-where-you-sit-in-the-technology-maturity-model)
      - [Identificare quale tecnologia adottare](#identify-what-technology-to-go-after)
      - [Creare un business case e ottenere il consenso all'acquisto](#build-a-business-case-and-get-buy-in)
      - [Implementare la soluzione](#implement-the-solution)
      - [Creare report e monitorare i risultati](#build-reporting-and-monitor-results)
    - [Evoluzione della tecnologia](#technology-evolution)
    - [Come incorporare diverse tecnologie nella vostra strategia](#how-to-incorporate-different-technologies-into-your-strategy)
    - [Concetti chiave](#main-takeaways)
- [Capitolo 6: Data Analytics per la strategia di globalizzazione](#chapter-6-data-analytics-for-globalization-strategy)
    - [Strategia dei dati di globalizzazione](#globalization-data-strategy)
    - [Considerazioni chiave](#key-considerations)
    - [Report e dashboard strategici](#strategy-reports-and-dashboard)
    - [Comprendere i dati](#understanding-the-data)
      - [Dati incompleti](#incomplete-data)
      - [Lacune nei dati](#data-gaps)
    - [Ruoli di Globalization Data Engineering e Globalization Data Analyst](#globalization-data-engineering-and-analyst-roles)
    - [Partnership](#partnership)
    - [Strumenti di analisi](#analytics-tools)
    - [Come creare un business case](#how-to-build-a-business-case)
      - [Utilizzare i dati per creare un business case](#using-data-to-build-a-business-case)
    - [Misurare la qualità e l'efficacia della MT](#measuring-mt-quality-and-effectiveness)
    - [Concetti chiave](#main-takeaways-1)
- [Epilogo: la nostra conclusione](#epilogue-our-final-words)
- [Appendice A: Fattori che influenzano le decisioni tecnologiche e obiettivi strategici](#appendix-a-technology-decision-drivers-and-strategic-objectives)
- [Appendice B: Inventario dei dati](#appendix-b-data-inventory)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc --> 


## 


## Capitolo 1: Scopo e vision

Sviluppare e implementare una strategia è la responsabilità principale di ogni leader. Che siate i responsabili di un piccolo o grande reparto di un'impresa sul lato cliente o che il vostro team si occupi di localizzazione, internazionalizzazione o altro ancora, i globalization leader immaginano il futuro ideale per il loro team e la loro azienda indicando come e quando raggiungere gli obiettivi più opportuni. Questo insieme di azioni è chiamato strategia.

In questa guida, introdurremo i concetti principali del pensiero strategico, come la vision, i pilastri, gli obiettivi e i traguardi, la tabella di marcia e le metriche, e spiegheremo in che modo si applicano al processo di globalizzazione.

I tipi di strategie che un leader deve considerare sono due.

La prima strategia è quella dell'unità aziendale, che determina in che modo, in futuro, la vostra organizzazione si inserirà nella struttura e nel successo dell'azienda e cosa dovete fare per assicurarvi la posizione ottimale per contribuire il più possibile. Immaginate che la vostra azienda stia incentrando la strategia di monetizzazione su una nuova serie di mercati e che quindi come leader della globalizzazione abbiate bisogno di riconfigurare il posizionamento del vostro team con i vostri stakeholder. Come gestite aspetti quali la strategia linguistica, la strategia di mercato, i processi di internazionalizzazione? Come vi assicurate di predisporre la vostra azienda e il vostro team al successo?

Il secondo tipo di strategia è quella relativa al vostro team: qual è il tipo di team (competenze, anzianità, esperienza) necessario per soddisfare la domanda futura e quali percorsi lavorativi è necessario prevedere per le persone che avete intenzione di assumere.

Forse si dovrebbe aggiungere un terzo tipo di strategia: la strategia di outsourcing, che permette di soddisfare la domanda fluttuante. Questo include come e quando riconsiderare la vostra strategia relativa ai fornitori, renderla più agile o semplicemente rivalutarla in base alle mutevoli esigenze aziendali.

Una buona strategia vi aiuta a raggiungere una destinazione senza farvi sentire persi, fornisce supporto ed esprime la sua massima efficacia nel farvi superare gli ostacoli e progredire. 

Offrendo un'ampia varietà di strumenti e un ampio quadro di globalizzazione, questo documento vuole essere una bussola in questo percorso: come fanno i globalization leader a sapere quando stanno risolvendo il problema giusto? Come definiscono i problemi?

Questa guida punta a consentire ai globalization leader di costruire una risposta strategica coerente, offrendo una panoramica di quanto segue:

* **Vision:** che aspetto ha il futuro che state cercando di creare? Come definite gli obiettivi relativi a qualsiasi cosa su cui vogliate lavorare in futuro? Immaginando, per esempio, che il vostro obiettivo sia quello di fornire capacità di globalizzazione out-of-the-box in ogni prodotto, quale deve essere la vostra vision relativa all'esperienza internazionale del cliente? Come vi assicurate che il pubblico non anglofono abbia un'esperienza utente simile o migliore di quella degli utenti di madrelingua inglese? 
* **Direzione strategica:** con direzione strategica si intendono i pilastri strategici, gli obiettivi annuali, i traguardi e le tabelle di marcia. I pilastri strategici sono i campi di battaglia più importanti che un globalization leader deve gestire per assicurare alla sua azienda il successo a lungo termine. 

    I pilastri strategici per il Globalization team sono: persone (interne ed esterne), processi (specifici della localizzazione e ciclo di vita aziendale), infrastrutture (TMS, cioè Translation Management Systems, librerie di globalizzazione, MT, ossia traduzione automatica, ecc.) e strumenti di reporting (dashboard, newsletter, ecc.). Il resto degli elementi sono obiettivi e traguardi annuali, che rappresentano il risultato desiderato. 

    La tabella di marcia, infine, è il piano tattico e operativo che descrive i dettagli su come raggiungere gli obiettivi e le metriche per misurare il successo di tali azioni tattiche.

* **Guida alle conversazioni:** quali sono gli argomenti, le metriche e le logiche di cui un globalization leader dovrebbe discutere con gli stakeholder e il gruppo dirigente per allineare la funzione di globalizzazione con gli obiettivi aziendali; condividere i dati sulla localizzazione che mostrano l'impatto sulle entrate e la fedeltà dei clienti, nonché le metriche del successo della localizzazione tra i leader dell'azienda; e definire chi influenzerà il lavoro direttamente o indirettamente.
* **Suggerimenti e best practice:** quali sono le procedure e i processi che meglio rappresentano la linea d'azione più efficace nella localizzazione (dal reclutamento dei fornitori alla valutazione degli strumenti, ecc.). Questo processo di solito inizia con la definizione del vostro stato attuale, dei vostri progetti e di come contribuiscano a raggiungere lo stato futuro in linea con la vostra vision. Continua poi con la raccolta dei dati, la creazione di un business case e il riallineamento delle risorse e dei progetti per seguire la strategia. Infine, si conclude con la valutazione del divario tra lo stato presente e quello futuro e su quali azioni vi aiuteranno a raggiungerlo e quando.

Il contenuto di questa guida spazia da consigli tattici a informazioni più creative. Tuttavia, il tema ricorrente di questo lavoro è quello di guidare i globalization leader attraverso un processo di pensiero strategico, dove la strategia è l'approccio che si adotta per raggiungere un obiettivo e un obiettivo è il risultato primario e misurabile di una strategia. 

Mentre gli obiettivi potrebbero essere diversi tra i lettori (perché sono legati a business specifici), la strategia e l'allenamento del pensiero strategico incoraggiato da questa guida dovrebbero essere stimolanti per ogni tipo di lettore. Che siate globalization leader di una piccola azienda o di una società esperta, il quadro strategico da affrontare per perseguire un obiettivo specifico è lo stesso.


### Pensiero strategico e fasi di pianificazione

Questa guida illustrerà diverse fasi pratiche, dalla descrizione di dove voi e il vostro team volete essere tra un paio d'anni alla definizione delle pietre miliari e delle metriche per guidare il vostro team lungo il percorso. In questa sezione vi proponiamo una versione di tali fasi. 


#### Fase 1. La vision della vostra organizzazione

La vision della vostra organizzazione è una rappresentazione di come essa potrà, a partire da ora e per diversi anni, adattarsi e contribuire alla vostra azienda. Essa dovrà allinearsi alla vision della vostra azienda e contribuire al successo generale di quest'ultima. 

Per esempio, se la vision della vostra azienda consiste nel diventare un'azienda globale in tre anni, la vostra vision potrebbe essere quella di creare una strategia Go to Market (GTM) per i mercati internazionali. Se la vostra azienda è in rapida crescita o appartiene ad un settore in via di sviluppo, la vostra vision non dovrebbe andare oltre un paio d'anni. Se invece appartiene ad un settore consolidato e il suo obiettivo è quello di capitalizzare la quota di mercato esistente, la vostra vision potrebbe estendersi da tre a cinque anni o, per evitare di continuare a modificarla, potrebbe essere ancora meno specifica. Tuttavia, la vostra vision deve sempre allinearsi con quella della vostra azienda.

In questo contesto, la strategia del Globalization team utilizza il piano dell'azienda per i mercati internazionali e lo amplia. Come punto di riferimento per i clienti internazionali e i team locali, la vostra organizzazione assumerà vari ruoli in tutta l'azienda: consulente, stakeholder, esecutore, ricercatore, program manager, esperto in materia (SME), ecc. La vostra strategia di globalizzazione, sebbene focalizzata sui non anglofoni, dovrà iniziare con una strategia aziendale per gli anglofoni. In molti modi, la strategia di globalizzazione influenzerà la strategia di un'azienda per diventare veramente globale.

I membri del vostro team devono essere i migliori dell'azienda in termini di collaborazione e influenza. Devono essere ottimi ascoltatori e ottimi sostenitori dei non anglofoni, in modo che la vostra azienda possa realizzare gli obiettivi fissati per i mercati internazionali di destinazione.


#### Fase 2. La strategia della vostra organizzazione

Una volta che, in base alla vostra vision, sapete dove arrivare, mettete a punto una strategia. Sarà la vostra bussola. Pensate a come raggiungere il vostro obiettivo e create una dichiarazione generale che rifletta il vostro piano. Dovrebbe essere abbastanza chiara e specifica, in modo che non ci sia ambiguità, ma anche abbastanza generica, in modo da poter cambiare le tattiche, ma non la strategia per realizzare il vostro obiettivo. 

In altre parole, avete bisogno di una dichiarazione che definisca come selezionate le pietre miliari o i risultati per rendere la vostra vision una realtà. 

Se dovete guidare da San Francisco a Los Angeles, per esempio, non ci sono molte strade che potrete scegliere. Tuttavia, potete decidere dove fermarvi per il pranzo e quando, come reagire in caso troviate traffico e dove è più probabile che ciò accada, quali sono le ore del giorno in cui non dovreste trovarvi vicino alle aree popolate in modo che il traffico non vi rallenti. La vostra strategia può essere "Raggiungere Los Angeles entro le 20 di venerdì" o "Arrivare a Los Angeles in sei ore". Notate la differenza? Le vostre tattiche saranno diverse in base all'obiettivo: tempo di viaggio o orario di arrivo.

Questo processo di pensiero può essere applicato alle decisioni relative alla vision della globalizzazione. Per esempio, se volete sviluppare un'infrastruttura di traduzione automatica (MT) nella vostra azienda, potreste assumere ingegneri di elaborazione del linguaggio naturale che creino i vostri motori e la vostra infrastruttura di traduzione automatica, decidere di acquistare la traduzione automatica come servizio da un fornitore terzo o scegliere un mix di entrambi.

Il vostro processo di pianificazione dovrebbe consistere in tre fasi di pensiero: 

1. Qual è la vostra previsione per la domanda futura del prodotto di lavoro della vostra organizzazione? Pensate in termini ambientali: la vostra azienda, il vostro settore e il mondo.
2. Qual è il vostro stato attuale? Cosa state producendo ora? Cosa produrrete man mano che i vostri progetti saranno completati? Se non fate nulla di diverso, come sarà in futuro il vostro contributo?
3. Confrontate A e B per determinare se c'è un divario tra le richieste attuali e quelle future. Avete bisogno di aumentare o ridurre la produzione di qualcosa? Avete bisogno di produrre qualcosa di completamente diverso?

#### Fase 3. Esecuzione del vostro piano

Ora che sapete dove volete arrivare e come, è il momento di pianificare un percorso. È il momento di stabilire le pietre miliari o i risultati specifici che dovrete raggiungere per realizzare la vostra vision. Si tratta di risultati molto specifici, legati a scadenze e misurabili che dovrete monitorare e controllare regolarmente. Questo è il "monitor dello stato di salute" della vostra vision. 

Usando la nostra analogia dell'infrastruttura di traduzione automatica menzionata in precedenza è possibile affidarsi a un fornitore terzo. Questo significa che dovrete identificare i fornitori che supportano le vostre combinazioni linguistiche. Per scegliere i fornitori più adatti alle vostre esigenze, sarà anche necessario adottare dei criteri di selezione. Questi criteri possono includere la disponibilità della lingua, i costi, la strategia di hosting, la qualità della traduzione, la velocità di consegna, la capacità di personalizzare/addestrare i motori, ecc.

Proprio per questo motivo, la vostra dichiarazione strategica dovrà essere sia specifica che generica: fissate le priorità della vostra organizzazione senza però specificarne il modo esatto di esecuzione. Il vostro piano esecutivo e la sua misurazione vi guideranno nel capire a che punto del vostro percorso siete e quanto è probabile che possiate raggiungere il vostro obiettivo.


### Ringraziamenti

Questo playbook è stato realizzato grazie all'iniziativa, la partecipazione e il contributo di un gruppo di leader nel settore della globalizzazione con background ed esperienze diverse. Mettendo insieme le nostre diverse esperienze quotidiane nei reparti di globalizzazione, i nostri anni di esperienza, i nostri diversi stili di lavoro e competenze, speriamo di aver reso questa guida ancora più efficace. Ecco l'elenco dei collaboratori:



* [Melissa Biggs](https://www.linkedin.com/in/melissa-biggs-2a3289/), socia fondatrice dell'azienda di servizi di consulenza Locale Solutions. Ha ricoperto posizioni dirigenziali nel settore della localizzazione per oltre 25 anni, lavorando per aziende tecnologiche. Melissa ha contribuito a questa guida unica nell'intento di renderla un potente canale di comunicazione dei molteplici aspetti chiave della strategia globale, sia all'interno dei gruppi di localizzazione che in *ogni* azienda e organizzazione partner.
* [Wayne Bourland](https://www.linkedin.com/in/wayne-bourland-0963ab4/) negli ultimi 14 anni si è occupato di diversi aspetti della traduzione ed è attualmente Director of Translations (L10N, I18N e interpretazione) per Dell Technologies. Wayne ha contribuito a questa guida con la sua passione per la condivisone delle best practice e perché aveva bisogno di fare qualcosa di diverso che parlare un'altra volta di tariffe a parola, tempi di completamento e metriche di qualità (tutte cose comunque molto importanti!).
* [Karen Combe](https://www.linkedin.com/in/karen-combe-14086/) si è recentemente ritirata dal suo ruolo di Vice President of Localization presso PTC, dopo aver lavorato per 20 anni alla realizzazione e allo sviluppo del reparto di localizzazione. Karen desidera condividere i risultati delle sue sfide e dei suoi successi con gli altri in modo che possano ottimizzare la loro produttività.
* [Francesca Di Marco](https://www.linkedin.com/in/fdimarco/) è l'Internationalization Lead di Pinterest, presso cui ha avuto il privilegio di creare prima un programma di localizzazione e poi uno di internazionalizzazione. Ha lavorato saltuariamente nel settore della localizzazione per 20 anni. Francesca ha contribuito a questa guida con il desiderio di trasmetterla alla prossima generazione di globalization leader come una ricetta da migliorare e personalizzare, piuttosto che da conservare.
* [Loïc Dufresne de Virel](http://linkedin.com/in/loicddev) guida attualmente il team di localizzazione interno di Intel. Loïc ha una profonda esperienza riguardo tutti gli aspetti legati alla localizzazione, traduzione, internazionalizzazione, strumenti di memoria di traduzione, QA (Quality Assurance), ottimizzazione dei processi, innovazione e altro ancora. Più di recente, ha lavorato a progetti di localizzazione avanzata che coinvolgono la comprensione del linguaggio naturale e i motori di riconoscimento vocale multilingue. Loïc si è unito a questa iniziativa per aiutare altri localizzatori a fare progressi più rapidamente attraverso la collaborazione, il lavoro di squadra e la condivisione di esperienze. 
* [Mimi Hills](https://www.linkedin.com/in/mimihills/) è stata direttrice dei Globalization team presso importanti aziende della Silicon Valley. Si impegna per garantire che i clienti non anglofoni ricevano un ottimo servizio e affinché il reparto di localizzazione sia considerato strategico per gli obiettivi dell'azienda.
* [Natalia Levitina](https://www.linkedin.com/in/nlevitina/) è Localization Director presso PTC, ruolo in cui è responsabile dell'implementazione di tecnologie di localizzazione nel reparto, nonché della supervisione del team di traduzione interno e della gestione dei fornitori. Natalia ha contribuito a questa guida strategica con la convinzione che si impari non solo facendo ma anche mettendo i propri pensieri nero su bianco (o anche su un documento Google!).
* [Christian Redmann](https://www.linkedin.com/in/christian-redmann-8579b8/), è Localization Director presso Siemens Digital Industries Software. Christian ha ricoperto un ruolo di leadership nella localizzazione per più di 20 anni e ha avuto il privilegio di creare un programma e un'organizzazione di localizzazione all'inizio della sua carriera. Christian ha dedicato tutta la sua carriera alla globalizzazione e alla localizzazione e ha una grande passione per questo campo. Ha contribuito a questo playbook poiché una guida del genere non esisteva, ma era convinto che sarebbe stata una risorsa inestimabile per chiunque cerchi di creare e gestire un programma e un'organizzazione di globalizzazione di successo che supportino la cultura e promuovano gli obiettivi strategici dell'azienda.
* [Lyena Solomon](https://www.linkedin.com/in/lyenas/) è Globalization Director presso ServiceNow. È responsabile della globalizzazione dei prodotti e della strategia Go to Market aziendale. Lyena ha contribuito alla realizzazione di questo playbook per poter aiutare i leader della globalizzazione a sviluppare una mentalità strategica e imparare dagli esperti dell'industria della localizzazione. Pensare in grande, iniziare in piccolo, valutare, modificare, raggiungere il successo: questi sono gli elementi chiave del dominio globale.
* [Jean-François Vanreusel](https://www.linkedin.com/in/jfvanreu/) è Director of Globalization presso Adobe, ruolo in cui da oltre 20 anni gestisce i team e le attività di globalizzazione. Si è unito a questa iniziativa per condividere il suo _savoir-faire_ in modo che chiunque nel mondo possa godere al meglio di contenuti e prodotti software. 
* [Erji Wang](https://www.linkedin.com/in/erji-wang/) è Senior Globalization Program Manager presso VMware Inc. Erji lavora nel campo della globalizzazione dei prodotti da otto anni e di recente ha iniziato ad utilizzare i dati aziendali per costruire la roadmap della globalizzazione dei prodotti di VMware. Ha contribuito a questa guida strategica per condividere ciò che ha imparato in questo percorso. 
* [Lorna Whelan](https://www.linkedin.com/in/lornawhelan/) è Senior Director of Localization presso Tripadvisor e lavora nel settore della localizzazione da 20 anni. Lorna ha partecipato a questa guida per condividere ciò che ha appreso e contribuire alla creazione di una risorsa molto preziosa che possa aiutare i nuovi globalization leader ad aumentare l'importanza strategica della localizzazione.


## 


## Capitolo 2: Panoramica della strategia

Immaginate di essere il globalization leader di un'ipotetica Azienda ideale. L'Azienda ideale sviluppa una strategia che funziona per il suo mercato globale. Non la sviluppa prima per un solo paese per poi vedere quali modifiche è possibile apportare per adattarla agli altri mercati. Questa strategia globale influenza tutto il lavoro relativo a marketing aziendale e regionale, servizi professionali, prodotti, ricerca e sviluppo, vendite, assistenza clienti, formazione, certificazione, ecc. 

Non è un approccio totalmente diretto dall'alto verso il basso: tutti questi gruppi si concentrano sulla raccolta di feedback dai loro clienti e li utilizzano per influenzare la strategia globale. In qualità di globalization leader collaborerete con vari gruppi agli approcci strategici che possano soddisfare le aspettative degli utenti multilingue nei loro mercati geografici.

![Immagine GTM Data Stategy](/media/Chapter%202_GTM%20Strategy.png)

La strategia GTM (Go To Market) globale viene messa in pratica per i nuovi prodotti o servizi tenendo in considerazione sia il mercato geografico che le preferenze linguistiche dei potenziali clienti. I mercati in cui il prodotto sarà introdotto per primo sono scelti in anticipo, insieme alle lingue necessarie per supportare quei mercati. Viene poi stanziato un budget per la localizzazione e, quando il prodotto viene spedito per la prima volta, i materiali di marketing, i materiali di servizio e la localizzazione del prodotto sono pronti.

In tutto ciò, naturalmente, un ruolo centrale verrà ricoperto da voi globalization leader. Avrete accesso a tutti i dati relativi alle vendite, all'uso dei prodotti e del sito Web, nonché all'uso della lingua e alle preferenze linguistiche dei clienti e così via. Non sarete solo destinatari delle informazioni, ma avrete un ruolo nel processo decisionale della strategia.

Quando l'azienda valuta una nuova campagna di mercato o un nuovo prodotto, voi presenterete i dati sui risultati di campagne o prodotti simili che l'azienda ha adottato in passato. Nessuno penserebbe infatti di mettere a punto un piano senza chiedere i vostri dati e senza affidarsi alla vostra esperienza e saggezza.

Siete a capo di un singolo team dell'Azienda ideale e questo gestisce il lavoro di localizzazione per tutti i reparti. Il vostro team è ben configurato e ottimizzato per la strategia aziendale. Avete il budget necessario per i servizi che esternalizzate, così come per i membri del team che si occupano del lavoro. Il vostro team include project e program manager (e forse un vendor manager), data analyst ed esperti di tecnologia che possono aiutarvi con gli strumenti, esperti di traduzione automatica ed esperti linguistici: tutto ciò di cui avete bisogno per eseguire la strategia e contribuirvi. Disponete anche di un program manager esperto che si concentra sulla strategia. 

<img src="/media/Chapter%202_Globalization%20Team.png" alt="Immagine del Globalization team" width="600"/>

Che rispondiate al team di Global Marketing, al capo del team di Ricerca e Sviluppo (R&S) o a un altro team, voi e il vostro team siete dei collaboratori rispettati. Le persone capiscono come il vostro team influenza la strategia, aumenta la soddisfazione del cliente e contribuisce a generare entrate. 

In effetti, avete un problema di cui andate orgogliosi: i vostri stakeholder vi chiamano, vi mandano e-mail e messaggi per consultarvi. Vi considerano preziosi membri dei loro team e vi invitano a partecipare alle loro riunioni, ma non potete accettare tutti gli inviti. Fortunatamente, il vostro team è preparato per queste situazioni e potete vantare specialisti per ogni disciplina e area di prodotto che possono parlare a nome del reparto e contribuire a risolvere le sfide degli stakeholder.

È chiaro, quindi, che il vostro ruolo nell'Azienda ideale è molto apprezzato. Come prova di ciò, stamattina avete ricevuto una telefonata dall'amministratore delegato, che vuole attribuirvi un nuovo titolo: Chief Globalization Officer (CGO). Vi chiede inoltre di partecipare alle riunioni del suo staff. 

Come dite? Non funziona così nella vostra azienda? In realtà, nemmeno in tutte le aziende in cui lavoriamo noi funziona così. Ci siamo fatto questa confessione molto tempo fa e abbiamo iniziato a condividere tra noi le nostre idee: date le culture, strategie, prodotti e servizi delle nostre aziende, come possiamo sfruttare al meglio i nostri ruoli? Abbiamo testato alcune idee, ne abbiamo rifiutate altre e infine abbiamo sviluppato strategie di localizzazione che funzionano per le circostanze in cui ci troviamo. La nostra reputazione è cresciuta nel tempo insieme a quella dei nostri team all'interno delle nostre aziende. 

In questa guida condividiamo le nostre idee in modo che possiate imparare ciò che si è rivelato efficace per noi. Su molti aspetti non vi è una risposta perfetta: è necessario porsi le domande giuste e scegliere ciò che è più adatto alla vostra azienda. Siete voi a conoscere la cultura e la strategia della vostra azienda e a poter scegliere ciò che pensiate funzioni meglio per essa. 


### Valutare la vostra azienda rispetto all'Azienda ideale

Che stiate assumendo il controllo della globalizzazione per un reparto esistente, sviluppando una nuova funzione di localizzazione in una start-up o in un'altra azienda o ripensando il vostro reparto attuale, in qualità di globalization leader strategici dovrete avere un obiettivo e un piano d'azione che vi permetta di raggiungerlo entro un periodo di tempo specifico. 

Avete bisogno di una vision di un futuro migliore per i vostri clienti internazionali e per la vostra azienda e dovete determinare i KPI (Key Performance Indicator) e gli obiettivi per monitorare i vostri progressi e, al bisogno, apportare modifiche. Questo è ciò che nel capitolo precedente abbiamo definito strategia e vision. 

Tuttavia, il primo passo per sviluppare la strategia è la valutazione della vostra azienda rispetto all'Azienda ideale in termini di strategia di globalizzazione e prontezza generali, comprese la visibilità da parte dei dirigenti aziendali e l'interazione con essi.


#### Strategia linguistica

1. La vostra azienda possiede uno specifico gruppo strategico, che sia autonomo o parte di una funzione esecutiva? La funzione di questo gruppo sarebbe quella di considerare in quali mercati l'azienda dovrebbe cercare di espandersi, in base al settore e ai dati economici generali, e stabilire le priorità relative all'impegno delle risorse aziendali. 

    Se la risposta è "sì", allora il vostro team dovrebbe in una certa misura essere integrato in quel gruppo, a seconda del livello di maturità dell'organizzazione. Il Globalization team forse ha reso il gruppo strategico consapevole della necessità di valutare i mercati in base alle lingue piuttosto che alla geografia (ad esempio, la Germania piuttosto che l'Europa centrale, o i paesi di lingua spagnola piuttosto che l'Europa). Oppure potrebbe contribuire fornendo i dati riguardanti le prestazioni passate per ogni lingua, poiché è probabile che solo il vostro reparto raccolga quei dati.

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Kate si è confrontata con il responsabile del team strategico della sua azienda per cercare di ottenere più dati di settore relativi alla lingua piuttosto che alla più inclusiva "geografia". Considerata l'assenza di quei dati in quel momento, la leader dell'SVP ha incaricato un membro del suo team di effettuare una ricerca e collaborare con il team di localizzazione.
>  
>Kate è stata in grado di stabilire un rapporto continuo con il gruppo strategico, presentando loro regolarmente i dati del ROI per lingua e per prodotto. Questo ha permesso di trasformare il rapporto in una partnership reciprocamente vantaggiosa che ha reso possibile un'analisi più approfondita dei mercati target esistenti e potenziali. 

2. Se la vostra azienda non è dotata di un gruppo strategico, chi decide quali mercati penetrare? Il reparto Vendite (sì, spesso è così)? Alcuni reparti di localizzazione fanno capo a quello che viene eufemisticamente definito "Revenue", che può fornire l'opportunità di contribuire direttamente alla formulazione di una strategia di mercato globale, se ancora non esiste. 

    In assenza di localizzazione, è possibile avviare il processo di sviluppo del ROI dei mercati potenziali lavorando attivamente con i responsabili regionali delle vendite su previsioni e proiezioni nei paesi in cui l'azienda vende attivamente. Se il prodotto fosse localizzato, quanto migliorerebbero i risultati? Ci sono prodotti concorrenti sviluppati nella lingua nativa? Gli altri concorrenti localizzano nelle lingue rilevanti? Per maggiori dettagli da integrare a questi esempi, consultate il capitolo ["Strategia linguistica"](#chapter-4-language-strategy).

3. Il Product Management (a volte considerato Product Marketing) è quello che dà avvio all'ingresso in uno o più mercati internazionali sulla base della propria analisi del panorama competitivo. In questo caso, si dovrebbe lavorare con gli stakeholder per stabilire un processo, come indicato nel capitolo ["Strategia linguistica"](#chapter-4-language-strategy). 

    Il punto centrale è determinare come la vostra azienda prende decisioni riguardanti il supporto linguistico, in modo da capire come sostenere al meglio tale processo o ottimizzarlo. Per essere efficaci, dovrete probabilmente fare affidamento sulle vostre capacità di influenzare e gestire gli stakeholder. Per approfondire, potete consultare il capitolo ["Stakeholder - Coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication).

#### Internazionalizzazione

Per entrare nei mercati internazionali, indipendentemente dal tipo di azienda in cui lavorate, i prodotti devono essere "pronti per il mondo", devono cioè poter funzionare correttamente in qualsiasi mercato di destinazione dell'azienda e deve essere possibile localizzarli in modo produttivo. 

L'internazionalizzazione non si applica solo al software e all'hardware, ma anche ad altri contenuti, tra cui la documentazione tecnica, il materiale di marketing, il sito Web, gli articoli di supporto tecnico e, più in generale, qualsiasi altro documento rivolto al cliente, come ad esempio le presentazioni di vendita. I vostri prodotti potrebbero essere utilizzati nella lingua di origine (di solito l'inglese) da persone di lingua madre diversa nel caso in cui non siano disponibili elementi localizzati. 

Questo significa che la creazione di un contenuto deve seguire determinate linee guida, in modo da ottenere un testo chiaro, conciso e facilmente comprensibile. Il contenuto creato in questo modo è anche agevolmente traducibile da esseri umani e macchine. Se una delle organizzazioni della vostra azienda ha strategie relative ai contenuti, il vostro team può fornire consigli sulla creazione di contenuti che siano pronti per la localizzazione. I team dei mercati locali saranno probabilmente un ottimo partner in questa iniziativa.

La vostra azienda possiede linee guida di internazionalizzazione appropriate per lo sviluppo e la creazione di contenuti? Se la risposta è no, parte della strategia del vostro reparto dovrebbe includere iniziative per la loro creazione, implementazione e convalida. Spesso tali linee guida includono marchi e altri requisiti legali per la traduzione, regolamenti interni per la scrittura di codice e regole riguardanti tassonomia e nomenclatura. 


#### Fusioni e acquisizioni

La maggior parte di noi ha avuto la necessità di integrare un'azienda acquisita. Idealmente, il Globalization team viene coinvolto nella due diligence dal team Fusioni e Acquisizioni prima che qualsiasi accordo venga concluso. I prodotti dell'azienda target sono internazionalizzati, localizzati, distribuiti in mercati non inglesi? 

La vostra azienda trarrà benefici se riuscirete ad integrare nel processo le vostre competenze, perché se i prodotti non sono pronti per essere distribuiti a livello mondiale, ci saranno dei costi per l'internazionalizzazione, che i dirigenti non avranno preso in considerazione nel fissare il prezzo di acquisizione. Ci possono essere ritardi nel rendere i prodotti disponibili sui mercati globali, il che significa che i ricavi previsti nell'ambito dell'acquisizione subirebbero ritardi. Inoltre, naturalmente, ciò potrebbe gravemente condizionare il costo di un'eventuale localizzazione. 

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> L'azienda di Kate ha acquisito un'azienda che usava una documentazione dettagliata per spiegare il proprio prodotto. Ogni pagina della documentazione era formattata a mano, con molteplici grafici che dovevano essere posizionati con la massima precisione. La domanda del prodotto a livello internazionale è stata immediata. Il costo di localizzazione è stato molto alto, per non dire astronomico, e sono stati necessari diversi tentativi per giungere a un approccio più razionale per un prodotto globale. Lezione imparata!


#### R&S-CICD, UX

Molti reparti di globalizzazione fanno capo al reparto R&D (noto anche come Engineering) e si integrano efficacemente nei processi di sviluppo. Tuttavia, anche i Globalization team che fanno capo ad altri reparti hanno bisogno di sviluppare gli stessi stretti legami, supponendo che siano responsabili della localizzazione dei prodotti. 

Nel valutare la vostra azienda rispetto a quella ideale, vi consigliamo di concentrarvi sulle quattro aree seguenti, alcune delle quali applicabili solo alle aziende di software (sebbene anche le aziende di hardware ora facciano un ampio uso di software nei loro prodotti).


#### Processo di sviluppo del prodotto

Che tipo di **processo di sviluppo** segue la vostra azienda? Waterfall, Agile o una combinazione dei due? Fino a che punto la localizzazione è integrata in esso? Considerati i paragrafi precedenti, daremo per scontato che vi stiate già occupando di internazionalizzazione. Quindi, a seconda del tipo di tecnologie di localizzazione di cui disponete, (per informazioni dettagliate, vedere il capitolo ["Strategia tecnologica"](#chapter-5-technology-strategy)), potreste trovare integrazioni dirette esistenti con i repository e la pipeline di integrazione. 

Se la vostra è un'azienda di software e utilizza il metodo CICD (Continuous Integration Continuous Deployment), è senz'altro necessario incorporare la pianificazione di queste integrazioni nella strategia del vostro reparto. Se sono già presenti, è l'ideale. Anche se la vostra azienda non utilizza un approccio CICD, il rapporto ottimale con il team di sviluppo richiede la massima automazione possibile in modo da avere un obiettivo chiaro.

E per quanto riguarda la **garanzia di qualità (QA)?** La QA copre più aspetti della localizzazione, ma in questo contesto si occupa principalmente del test funzionale e include anche il test di internazionalizzazione. La funzione QA nel vostro team di sviluppo usa test automatici? E questi test funzionano per tutte le lingue? In caso contrario, questo argomento va aggiunto alla vostra to-do list per l'internazionalizzazione.

Nell'Azienda ideale, il team di QA è responsabile dell'esecuzione di test automatici su tutte le lingue, sia su server separati che in una pipeline centralizzata. Tuttavia, il debugging dei test non riusciti spetta necessariamente a ingegneri dotati di competenze linguistiche. Il vostro team, quindi, dovrà fornire questa funzione tramite il personale o i fornitori. La conformità dell'internazionalizzazione dovrebbe essere inclusa nella Definition of Done per le release di software e il vostro team potrebbe gestire i processi a essa relativi.

Spesso il team **UX** (User Experience) fa parte del reparto di sviluppo. La vostra valutazione include questo team e la sua conoscenza dei clienti internazionali. Le sue best practice o il suo sistema di progettazione includono idealmente anche linee guida appropriate per i clienti globali. Il vostro reparto potrebbe essere nella posizione migliore per fornire input o consulenza. Se tale consapevolezza è assente, dovrete aggiungere un'altra voce alla to-do list della vostra strategia.

L'esperienza utente è spesso legata all'accessibilità. Per alcuni mercati esistono requisiti legali e requisiti relativi ai clienti. Allineatevi con i team che si occupano di accessibilità e includete controlli e correzioni nel flusso di lavoro di QA.

Il team con cui spesso quello di globalizzazione lavora più a stretto contatto è quello delle **Pubblicazioni** (scrittura tecnica). Tra i due gruppi della vostra azienda ci sono spirito di collaborazione e una comprensione reciproca delle esigenze di ciascuno? A seconda della strategia di sviluppo (spedizione simultanea di tutte le lingue, CICD, release scaglionate), potrebbe essere necessario collaborare con il reparto pubblicazioni per trovare modi creativi per accorciare i tempi senza conseguenze negative sulla qualità. Trattare il team delle pubblicazioni come un vostro alleato nel raggiungimento degli obiettivi strategici offre generalmente i migliori risultati.

A volte le priorità della documentazione differiscono per i vari mercati. Le informazioni che raccogliete dai team locali su tali priorità sarebbero preziosissime per stabilire le priorità relative a cosa tradurre o non tradurre, in quali lingue e quando. 


#### Informazioni finanziarie

Per contribuire pienamente agli obiettivi del mercato globale della vostra azienda, avete bisogno di informazioni dal reparto Finance, in particolare quelle sulle entrate e sul bilancio. Senza considerare le entrate (e quindi il ritorno), non si può infatti stabilire il ROI per prodotti e lingue, così come se non si dispone di una visione aziendale del budget e dei costi, non è possibile valutare il lato dei costi (investimento). Anche il personale rappresenta una parte della gestione finanziaria della vostra organizzazione. 

In un'analisi del ROI di un prodotto, ad esempio, i costi di localizzazione includono sia la percentuale di personale del vostro reparto assegnato al prodotto sia i costi esterni. Per il vostro organico, però, dovreste includere solo lo stipendio e i benefit o aggiungere i bonus, più i premi in azioni, più le spese generali delle strutture? La risposta è sapere in che modo la vostra azienda calcola il costo di un organico. 

Questi dati relativi a entrate e costi costituiscono una parte dei dati di cui avete bisogno per gestire efficacemente il vostro reparto e per la gestione fino al livello esecutivo. Per ulteriori informazioni, consultate anche il capitolo ["Data Analytics per la strategia di globalizzazione"](#chapter-6-data-analytics-for-globalization-strategy). Se non avete accesso a questo tipo di informazioni, direttamente o attraverso il vostro responsabile, per stabilire una relazione produttiva con il reparto Finance, prendete in considerazione anche gli approcci illustrati nel capitolo ["Stakeholder - Coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication). 

#### Procurement

Un reparto o una funzione di procurement (approvvigionamento) può essere di grande aiuto al Globalization team nella selezione dei fornitori e nelle trattative con essi. Questa relazione, però, funziona bene solo se il reparto di procurement comprende in modo sufficiente i requisiti specifici dei prezzi di localizzazione. Davvero contate le parole e ne esistono diversi tipi? 

È improbabile che un reparto di procurement raggiunga una profonda comprensione del settore della localizzazione e delle sue sfumature, quindi, in quanto leader, è vostra responsabilità dimostrare una profonda conoscenza di prezzi e requisiti. È importante che prendiate l'iniziativa sui prezzi e che rivediate la cadenza dei contratti con i fornitori. Quando è necessario nelle negoziazioni e negli accordi standard con i fornitori, il reparto di procurement può quindi contribuire con la sua esperienza a un risultato ottimale. Se non trovate questa relazione equilibrata nella vostra valutazione, avete un altro punto da aggiungere alla vostra to-do list della strategia.

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> L'azienda di Kate ha aggiunto un reparto di procurement la cui missione in un primo momento era quella di ridurre il numero di fornitori da diverse migliaia a un numero ragionevole. In secondo luogo, il suo compito era quello di risparmiare denaro attraverso la funzione di procurement. Quando il nuovo vicepresidente ha visitato il reparto di localizzazione, Kate è stata lieta di poter dimostrare la padronanza della strategia dei fornitori da parte del suo team: * Un breve elenco di fornitori di lunga data, con le motivazioni alla base della scelta ciascuno di essi * Proposta di consolidamento ed espansione dell'ambito di lavoro dei fornitori selezionati in base alle loro competenze (servizi di QA, ad esempio) * Certificazione CMMI (Capability Maturity Model Integration per lo sviluppo di software dell'università Carnegie Mellon), pratiche documentate per l'acquisizione di nuovi fornitori, compresi i test di qualità, fattibilità del business e raccomandazioni verificate fornite da altri clienti * Accordi sul livello del servizio (SLA) con appendici sui prezzi e le penalità per la mancata esecuzione * Un sistema per la gestione di preventivi e probabilmente offerte, per confrontare le offerte di più agenzie di localizzazione  
>
>È diventato subito chiaro che le pratiche di gestione dei fornitori del reparto di localizzazione non avevano eguali in nessun altro reparto dell'azienda. Kate e il suo vendor manager hanno successivamente dimostrato nel loro software di gestione dei costi come funzionano i prezzi nel settore della localizzazione: esistono tariffe per parola diverse a seconda della lingua, del fornitore, dell'utilizzo di contenuti simili tradotti in precedenza e dell'uso della traduzione automatica e tariffe orarie per attività che non prevedono traduzione. L'uso della traduzione automatica si è dimostrato efficace nella riduzione continua e crescente dei costi. Il VP del reparto di procurement se n'è andato felice dopo quella riunione di un'ora e non è più tornato!


#### IT

Se il vostro reparto o uno con cui lavorate a stretto contatto usa tecnologie di localizzazione, ad esempio un TMS, interagirete con il reparto di Information Technology (IT). L'aspetto più importante nella tecnologia è la sicurezza, quindi qualsiasi tecnologia che si connette a entità al di fuori del firewall aziendale deve soddisfare gli standard che l'IT definisce. 

Supponiamo ora che il vostro dipartimento usi un TMS che non soddisfa gli standard. L'IT probabilmente insisterà che la tecnologia venga aggiornata o cambiata entro un certo periodo di tempo. Avete bisogno di un'interazione produttiva con l'IT per assicurarvi che le tempistiche possano essere rispettate, oppure dovete offrire un'alternativa accettabile. 

In uno scenario leggermente diverso, alcuni reparti IT preferiscono gestire direttamente la tecnologia, il che presenta un'ulteriore difficoltà nella gestione delle relazioni.

 Assicuratevi infine di disporre di un buon SLA con l'IT, poiché la vostra infrastruttura di localizzazione dev'essere disponibile 24/7.

Se la vostra azienda opera nello spazio tecnologico del cloud, ci saranno requisiti di privacy dei dati associati alla tecnologia TMS, cioè dove vanno i dati per la traduzione e come vengono restituiti. L'IT, la Commissione per la proprietà intellettuale, il team della tecnologia cloud, ecc. influenzeranno le vostre decisioni tecnologiche. Quando prendete decisioni sul TMS, considerate la possibilità di confrontarvi con questi team.

Come potete capire, qualunque sia la valutazione della vostra azienda e del vostro dipartimento, avrete bisogno di una strategia per muovervi verso l'ideale. Tutto ciò implica, certamente, la creazione o il miglioramento delle relazioni con gli stakeholder.


### La strategia della vostra azienda

Rivediamo la storia delle iniziative di una globalization leader per valutare ed esaminare la propria azienda rispetto all'Azienda ideale. Questo esercizio pratico vi consentirà di iniziare il benchmarking della vostra strategia e vi fornirà alcuni utili insegnamenti.

> <img src="/media/story_icon.png" alt="immagine del libro " width="30"/> Una delle responsabilità di Diana era quella di gestire un programma per tradurre il sito web della sua azienda in tedesco, nell'ambito della espansione dell'azienda nel mercato tedesco. Settimane dopo l'avvio del programma, le è stato chiesto di aggiungere altre cinque lingue. Era chiaro che il programma avrebbe dovuto avere un proprio leader e un proprio piano. È così che Diana ha abbandonato tutto il resto ed è stata messa a capo del gruppo di localizzazione del sito web. 
>
>Chiamare il suo team un gruppo era un'esagerazione: era l'unica a farne parte e collaborava con più team operativi per portare avanti la sua localizzazione a bassa priorità. Stava quindi a Diana ora definire quali risorse aveva bisogno di assumere, di quale budget aveva bisogno per tradurre e quali fornitori ingaggiare per esigenze specifiche. Poiché la sua esperienza nella gestione di una funzione di localizzazione era di poche settimane, ha effettuato delle ricerche e si è rivolta alle sue varie reti.
>
>È risultato presto abbastanza chiaro che non esistono risposte semplici a nessuna di quelle domande. Tutte le risposte iniziavano con "Dipende...". 
>
>Mentre Diana si districava dal labirinto operativo della produzione e dei flussi di lavoro, ha impostato i framework per garantire la consegna puntuale e misurare il successo, si è interfacciata con gli stakeholder, ha assunto i membri del team e ha effettuato l'onboarding dei fornitori, imparando così diverse lezioni.
>
>* Un Globalization team ha successo quando aiuta altri team a raggiungere i loro obiettivi nei mercati internazionali. Il valore aggiunto è in particolare legato alla consulenza sulle esigenze di quei mercati e al collegamento delle azioni alla strategia globale dell'azienda per accelerare il successo. Vedere il capitolo ["Stakeholder - Coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication).
>
>* Ciò che misurate dovrebbe confluire nelle misurazioni della strategia globale dell'azienda. Il vostro contributo è un valore aggiunto e moltiplica il successo aziendale nei mercati locali. Vedere il capitolo ["Data Analytics per la strategia di globalizzazione"](#chapter-6-data-analytics-for-globalization-strategy).
>* Il Globalization team rappresenta il collegamento tra l'azienda e i clienti, i team aziendali e locali e i team funzionali all'interno dell'azienda. È per questo essenziale che il team collabori e lavori bene con gli altri.

Cosa fareste se foste al posto di Diana? Ecco il framework. 

![Immagine del processo di strategia GTM](/media/Chapter%202_GTM%20Strategy%20Process.png)

1. Iniziate confrontando e comprendendo come la concorrenza mette in pratica la globalizzazione nei vostri mercati di riferimento. In questo modo determinerete il vostro ambito solo per competere su un piano di parità. Una cosa da considerare è che la vostra concorrenza in inglese potrebbe essere diversa da quella di un mercato locale; potrebbe anche essere al di fuori del vostro settore. Concentratevi sulle aspettative di esperienza linguistica dei vostri clienti.
2. Capite come la vostra azienda produce il prodotto che vendete e dove il vostro ambito di globalizzazione si interseca con i loro processi e consegne. Parlate con il leader di ogni processo e individuate possibili aggiustamenti nei loro flussi di lavoro in modo da poter includere la globalizzazione. Questi leader sono i vostri partner più preziosi e la collaborazione con loro è fondamentale per il vostro successo.
3. Capite cosa potete fare _ora_ e cosa dovrà essere fatto più tardi. Lavorate con i leader non solo sulla gestione dei cambiamenti, ma anche sulla revisione della vostra visione strategica e del vostro piano. Mentre voi apprendete il loro processo e loro apprendono il vostro, è essenziale acquisire conoscenze sufficienti per lavorare bene insieme senza interferire nei flussi di processo dell'altro.
4. Convalidate piani e ipotesi con i vostri mercati locali. Ascoltate le loro priorità e assicuratevi che siano allineate con le priorità commerciali/tecniche/finanziarie della vostra azienda e dei vostri stakeholder di prodotto. Individuate i dati di cui avete bisogno per creare il vostro business case.
5. Eseguite il vostro piano avvalendovi della collaborazione dei vostri stakeholder. I program manager gestiranno l'avanzamento dei vari progetti che includono traduzione, internazionalizzazione o localizzazione. Il vostro compito è quello di assicurarvi che tutti i gruppi si muovano nella direzione delineata nella vostra visione strategica.

Avete ora completato una valutazione di dove si trova la vostra azienda rispetto all'Azienda ideale e avete visto come Diana, una globalization leader, è stata in grado di pianificare una strategia globale adatta alla strategia dell'azienda e di costruire con successo ponti con altre parti dell'azienda.

A volte, la localizzazione è un ripensamento nella strategia del mercato globale. Se state considerando come mai non siete inclusi nel processo, non siete soli. Molti di noi si sono trovati con i propri reparti in posizioni simili. Le situazioni tipiche includono:

* L'azienda divide il mercato globale per regioni e ogni regione elabora la propria strategia. Non c'è coordinamento tra i mercati linguistici.
* La strategia di mercato globale è considerata una strategia di vendita. Quando un mercato è prioritario, può includere un certo budget per il marketing, ma il budget per la localizzazione non è coordinato.
* La strategia di mercato globale è delineata per tutti, ma ogni prodotto dà la priorità alla propria strategia. Il budget di localizzazione può non essere coordinato. Ci possono essere team regionali di marketing e di prodotto che usano il loro budget per riempire le lacune di localizzazione, in inglese o nelle lingue native.
* Non c'è una strategia di mercato globale. In questo scenario, un team di vendita può fornire al reparto di localizzazione un budget per localizzare determinate campagne o prodotti.
* Nelle aziende in cui ci sono diversi gruppi di localizzazione, il management può perseguire diverse strategie che non sono coordinate tra i gruppi. 

Se queste situazioni vi sembrano familiari, non disperate. Come globalization leader, anche noi abbiamo dovuto affrontarle. Alcune delle domande che ci siamo posti pensando alla strategia della nostra azienda sono le seguenti:

* Quali sono le disconnessioni: il budget non è allocato secondo la strategia di mercato globale? Le aspettative dei clienti regionali vengono soddisfatte? Le limitazioni del mercato (per esempio, la conoscenza della lingua inglese) vengono prese in considerazione?
* Dove sono le disconnessioni? Si trovano a livello di azienda, di prodotto o di reparto? 
* Quali sono i dati utilizzati per decidere la strategia? Chi raccoglie le metriche? Chi effettua l'analisi e quali sono i canali di distribuzione? 
* Siete inclusi nel processo di sviluppo della strategia, sia perché considerati stakeholder o perché contribuite direttamente ad essa? Se lo siete, qual è il vostro ruolo? E quali sono le aspettative che riponete nei risultati del vostro team? Sono realistiche? Contribuiranno al risultato aziendale atteso? 
* Come si inseriscono i risultati del vostro reparto nella strategia globale? Sapete a che punto si trova il vostro reparto e quale direzione prendere in seguito? Questa è una domanda importante a cui dovrete rispondere quando considerate la seconda fase.

### Creare una strategia di reparto

Potreste essere entrati in una azienda come globalization leader e aver scoperto che, anche se la strategia di mercato globale era buona nel complesso, era carente in un'area importante (e non c'erano finanziamenti per colmare tale lacuna): un reparto di globalizzazione che potesse supervisionare la strategia di globalizzazione.

Se siete stati assunti da una startup per creare un nuovo Globalization team, congratulazioni! Avete l'opportunità di creare un reparto che si adatti alla perfezione alla strategia di mercato globale dell'azienda. Potete sviluppare strategie per le lingue, l'outsourcing, le tecnologie e una struttura di reparto secondo le priorità attuali, tenendo presente la direzione in cui si muove l'azienda.

Molti di noi non hanno questo lusso. I nostri reparti hanno un budget, dipendenti in vari ruoli e risultati da raggiungere e aspettative da soddisfare con quel budget e quei dipendenti. Anche mentre cerchiamo di capire quale dovrebbe essere la strategia del nostro reparto per i prossimi tre-cinque anni, è fondamentale riuscire a ottenere risultati che soddisfino le aspettative. Dobbiamo guadagnarci la fiducia del management e degli stakeholder, convincerli che sappiamo cosa stiamo facendo, in modo che quando diremo loro cos'altro dobbiamo fare, si fideranno di noi. 

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Minato è stato assunto come Localization Director per un'azienda di software che da oltre dieci anni localizza i propri prodotti. La localizzazione dei prodotti ha richiesto la collaborazione tra un gruppo di project manager esperti e i fornitori. Un altro gruppo era invece responsabile dell'internazionalizzazione e della garanzia di qualità della localizzazione e ha interagito bene con il primo gruppo. Il software è stato venduto come prodotti individuali e suite. Tutti i prodotti sono stati quindi localizzati nello stesso set di lingue per assicurare al cliente un'esperienza ottimale.
>
> L'azienda sembrava avere processi maturi e una strategia matura, con un'eccezione: nessuno dei prodotti era localizzato in spagnolo. Il primo passo di Minato è stato quello di mettersi in contatto con i reparti di vendita in America Latina e in Spagna. I venditori latinoamericani riconobbero chiaramente che le vendite sarebbero potute aumentare se i prodotti fossero stati localizzati. Minato chiese la percentuale di aumento e, anche se erano riluttanti a fare promesse di cui avrebbero dovuto rispondere se non fossero state raggiunte, concordarono un prudente aumento delle vendite del 20%.
>
>Minato ha poi svolto ricerche sui dati di vendita, suddivisi per prodotto e per paese. Ha ottenuto delle stime per la nuova localizzazione basate sui conteggi delle parole che erano disponibili nel suo reparto per prodotto. Successivamente, è stato in grado di dimostrare che un aumento delle vendite del 20% sui prodotti avrebbe portato al pareggio nel primo anno e che entro cinque anni avrebbe prodotto oltre 15 volte il ritorno annuale sull'investimento. Ha presentato i dati ai dirigenti responsabili dei prodotti e gli è stato concesso il budget per aggiungere lo spagnolo al budget esistente per la localizzazione del prodotto.
> 
> Alla fine, a tre anni dall'iniziativa di localizzazione di Minato, la traduzione in spagnolo ha prodotto un ROI del 348%.

In ogni azienda c'è un limite a ciò che un globalization leader può realisticamente fare, considerando le risorse, la direzione strategica aziendale, la tecnologia e le esigenze aziendali di globalizzazione alla base. Un modo per fare la differenza è definire un approccio diverso per ciascuna delle tre seguenti aree:

* **Ciò che controllate**. Questo può includere gli strumenti che usate, le persone che assumete, i fornitori che selezionate, i processi che introducete, i risultati che generate, ecc.

* **Ciò che influenzate**. Questi risultati sono di dimensioni maggiori rispetto a quelli del vostro team e possono includere la roadmap del prodotto, l'ambito di progetto di altri team (per esempio, la formazione) e altri risultati dell'azienda. Lavorereste con gli stakeholder per aggiungere la prospettiva della globalizzazione ai requisiti, alle caratteristiche e alle metriche del ROI per le lingue.

* **Ciò a cui dovete adattarvi** poiché non avete alcuna influenza o controllo. Quest'area è la più difficile perché include cose che non si possono cambiare. Per esempio, la vostra azienda non è pronta per entrare nel mercato in cui pensate che dovrebbe essere, o non avete ottenuto personale per un ruolo di cui avete bisogno. Oppure, l'azienda non ha raggiunto i risultati previsti e ridimensiona la vostra organizzazione. Queste cose possono succedere e, poiché lavorate con l'intera l'organizzazione, a voi potrebbero accadere con più frequenza che ad altri. Create la descrizione dei requisiti essenziali e a questi adattate i confini dell'ambito che controllate. Dovrete continuare a innovare e a estendere i limiti. 

È importante concentrare se stessi e il proprio team su ciò che si può controllare e sui risultati che si possono ottenere, sviluppare ed espandere la propria sfera d'influenza e adattarsi rapidamente al cambiamento delle priorità, in modo che i risultati che si possono controllare siano in linea con gli obiettivi aziendali. 

Uno dei ruoli di un globalization leader è quello di costruire un'organizzazione che segua i principi dell'eccellenza operativa e organizzativa. Un leader di successo assume le persone giuste per i ruoli necessari ad aggiungere valore al business, investe nella tecnologia adeguata e crea processi scalabili per accrescere i profitti dell'azienda nei mercati internazionali. Il Globalization team strategico collabora e innova, espande le integrazioni e rafforza l'interoperabilità per estendere le funzionalità di una lingua ai mercati multilingue. In questo playbook verranno delineati i principi di base per formare un team con queste caratteristiche.

Per avere successo, qualsiasi Globalization team deve infatti essere operativamente solido e assicurare innovazione e risultati eccellenti. La gestione delle prestazioni, il miglioramento continuo e l'eccellenza dei processi sono fondamentali quando si cerca di ottenere una consegna scalabile con dipendenze complesse da varie unità e gruppi di tutta l'azienda. Pertanto, il Globalization team dovrebbe avere un focus sia interno che esterno. 

Il focus interno è principalmente operativo e volto a soddisfare le esigenze dell'azienda. Normalmente, il suo scopo principale è la consegna di una traduzione di elevata qualità. Il focus interno comprende anche le tecnologie, i processi, la gestione dei fornitori, il QA e il supporto linguistico. La collaborazione con gli esperti del marchio, l'ufficio legale, il Marketing e altri gruppi contribuirà a creare linee guida linguistiche per la traduzione nelle lingue supportate. 

Il focus esterno è rivolto al vostro cliente e ai suoi clienti. La parte strategica del vostro lavoro consiste nel capire le esigenze dei clienti internazionali e influenzare la roadmap del prodotto per rendere l'offerta aziendale più allettante nei mercati internazionali. Le raccomandazioni che il tuo team formula in relazione ai requisiti dei clienti e alle aspettative di mercato dovrebbero far parte di ogni strategia go-to-market dell'azienda. Il vostro team dovrebbe definire e mettere in pratica un framework interno di standard e processi che soddisfino le esigenze dei clienti, in modo da poter consegnare un prodotto o un servizio in linea con le aspettative aziendali.

In quanto globalization leader, dovete assumere talenti che vi aiutino a definire le aspettative del business e le esigenze dei clienti e a colmare il gap. Se la collaborazione con altri team alle loro roadmap è necessaria per il vostro successo, ancora più complesso sarà il lavoro del vostro team. L'unico modo per fare ciò sta nel creare una cultura collaborativa e infondere fiducia all'interno del team, permettendo ai suoi membri di lavorare in modo indipendente. La trasparenza, così come la comunicazione, è una necessità. Come globalization leader, avete il compito di fornire una direzione strategica, perciò siate chiari nell'indicare le metriche di successo e gli obiettivi del team. 

Al giorno d'oggi, tutte le aziende tengono traccia di una quantità crescente di dati con l'obiettivo monitorare il loro business e persino di prevedere il comportamento dei clienti. Negli ultimi anni, un maggior numero di Globalization team ha creato posizioni dedicate di Globalization Data Engineering e Globalization Data Analyst. Queste figure sono responsabili della creazione e gestione di un'infrastruttura di dati sulla globalizzazione e dell'identificazione delle informazioni chiave, fondamentali per impostare la strategia di globalizzazione. Anche semplici metriche che indicano la percentuale di progetti consegnati in tempo e nel rispetto del budget possono mostrare al vostro team e al management che i risultati ottenuti rispecchiano i piani. 

Il capitolo ["Data Analytics per la strategia di globalizzazione"](#chapter-6-data-analytics-for-globalization-strategy) illustra in modo più approfondito le modalità di raccolta e utilizzo delle metriche per mostrare come state attuando la vostra strategia.

Fino ad ora, abbiamo visto come l'Azienda ideale potrebbe creare una strategia globale e abbiamo parlato di cosa intendiamo per strategia. Abbiamo visto come una valutazione dell'azienda per cui lavorate è essenziale per l'elaborazione di una strategia. Abbiamo parlato di come assicurarvi che la funzione strategica del vostro reparto funzioni in sintonia con la strategia dell'azienda e di come creare una strategia per il vostro reparto. Diamo adesso un'occhiata a diverse aree fondamentali per il successo della vostra strategia di reparto, che garantiscono che essa contribuisca alla strategia aziendale.


## Capitolo 3: Stakeholder - Coinvolgimento e comunicazione strategici

Per la natura stessa delle loro attività, i team di localizzazione in-house si trovano spesso a un crocevia tra i reparti di ingegneria del prodotto e di marketing, tra la sede centrale e gli uffici nei vari Paesi e tra i documenti diretti all'interno e i materiali collaterali diretti all'esterno. Di conseguenza, essi devono interagire con una varietà di stakeholder. Anche se alcuni stakeholder sono più essenziali di altri, a un certo punto tutti meritano attenzione.


### Definire i vostri stakeholder

Adottando un approccio olistico, consideriamo "stakeholder" qualsiasi parte che interagisce o dovrebbe interagire con il Globalization team, in maniera abitudinaria o saltuaria.

Esistono diversi modi di approcciarsi agli stakeholder, per esempio in base alla sfera di influenza rispetto al Globalization team o in base al rapporto di lavoro che hanno con i membri del vostro team, all'interno o all'esterno dell'azienda.

Dal punto di vista del globalization leader, gli stakeholder possono essere categorizzati in tre gruppi principali:

1. Singoli individui o team che hanno **esigenze e aspettative specifiche** relative al team di localizzazione. Chiamati anche clienti interni, sono le unità aziendali che si affidano al Globalization team per la produzione di un risultato specifico. Spesso rappresentano un pubblico più ampio di utenti finali globali, partner di settore o rivenditori, ossia i consumatori finali dei prodotti o contenuti localizzati. Anche gli utenti finali sono stakeholder del team di localizzazione, ma nella nostra esperienza l'interazione con essi è spesso indiretta, poiché avviene attraverso i rappresentanti del supporto clienti o i team di vendita e marketing dei vari Paesi.

2. Individui o team che esercitano un'**influenza diretta o indiretta** su un progetto o programma, ad esempio tramite il potere di veto o la capacità decisionale. Essi potrebbero avere solo interazioni sporadiche con il team di localizzazione, ma quei pochi punti di contatto possono essere fondamentali per il vostro successo. Spesso rappresentano:
    * I dirigenti, per lo più interessati alla strategia e al quadro generale. Per esempio, possono voler sapere come un prodotto internazionalizzato contribuisca al successo dell'azienda e li aiuti a raggiungere specifici obiettivi relativi alle entrate o alla crescita.
    * Team ingegneristici, team di sviluppo, team di prodotti e persino agenzie creative. La necessità di supportare più lingue avrà un impatto sul loro lavoro e, come minimo, richiederà un'adeguata internazionalizzazione.
    * UX designer, poiché l'esperienza dell'utente potrebbe cambiare da un paese all'altro o da una lingua all'altra.
    * Team di analisi e raccolta delle informazioni, in quanto convalideranno le vostre ipotesi e forniranno i dati necessari per creare solidi business case.
    * Reparti Finance, IT, Procurement, Legal, compresi i team di Information Security e Privacy.
    * Reparti Field Sales, Customer Success, Customer Support, su scala globale.
    * Partner dell'ecosistema e della formazione, in particolare nel caso di programmi di certificazione.
3. Singoli individui o team che sono **coinvolti nella produzione di materiali localizzati**. Queste risorse sono in genere un mix di dipendenti, lavoratori atipici e freelance, interamente assegnati al team di localizzazione o assunti con un contratto a misura. Tra i dipendenti coinvolti nella localizzazione, alcuni potrebbero non far parte del team di localizzazione. Potrebbero appartenere a un team di vendita o di marketing di un Paese specifico a cui viene chiesto di revisionare un white paper tradotto o una nuova campagna di marketing localizzata.

Uno stakeholder può appartenere a più di una categoria. Ad esempio, il reparto di procurement potrebbe assistere il team di localizzazione durante le trattative contrattuali con un importante fornitore di servizi di localizzazione (LSP, Localization Service Provider), ma anche avvalersi dei servizi dello stesso team per tradurre i contratti di acquisto o il materiale per la formazione dei fornitori. 

Come globalization leader, le vostre priorità, preoccupazioni e responsabilità cambiano man mano che avrete a che fare con diversi stakeholder, sui quali potete avere o meno autorità o influenza. Quando supervisionate le vostre risorse, potreste dover pensare ai percorsi di carriera e alla gestione delle prestazioni. Relazionandovi con altri team, potreste dover gestire le priorità di bilancio e le iniziative strategiche.

### Capire i tipi di stakeholder

Esaminiamo più a fondo le categorie di stakeholder. In base alla loro funzione e a seconda della struttura, delle dimensioni e dei fattori ambientali dell'azienda, gli stakeholder possono essere classificati come "primari" o "secondari", così come "dimenticati" o "indiretti" Queste etichette possono essere applicate agli stessi stakeholder in momenti diversi. Gli stakeholder che vengono considerati primari da un'azienda possono essere secondari per un'altra.

Gli stakeholder principali sono le unità aziendali per le quali il team di localizzazione fornisce servizi di traduzione, comprese organizzazioni come Product Team, Sales, Customer Success, Marketing e Customer Support. Esistono diversi tipi di stakeholder primari.

#### Stakeholder primari #1 

Sono le figure con le quali il team di localizzazione interagisce abitualmente e alle quali consegna. Possono essere team di vendita e di successo dei clienti, che vi consentiranno di avere un confronto con i clienti in modo da poter ricevere il loro feedback (vedere la sezione "Utenti finali"). Oppure, possono essere un team di assistenza clienti che vi aiuta a interpretare il feedback dei clienti. Questi stakeholder si relazionano sia con i team Development che Marketing e possono avere priorità contrastanti.

Le organizzazioni di marketing possono essere i vostri stakeholder primari o secondari, a seconda del modello di coinvolgimento del vostro team. In alcune aziende, il Globalization team è lo stakeholder del reparto di Marketing. In altre aziende, se il vostro team è responsabile della localizzazione degli elementi web e di marketing, il reparto Marketing è lo stakeholder principale. In questo caso, il reparto Marketing ha un ruolo centrale nel generare il ritorno sull'investimento per le nuove iniziative di localizzazione, poiché deve supportare nuove lingue nei prodotti.

#### Stakeholder primari #2

Questi stakeholder sono gli utenti finali dei prodotti localizzati. Quando possibile, mettetevi in contatto con gli utenti finali: essi forniscono un input inestimabile sulla qualità dei prodotti localizzati nella vita reale. Essi forniscono informazioni anche sul modo in cui usano quei prodotti e offrono la prospettiva dell'utente internazionale necessaria per creare modelli di design UX inclusivi del pubblico multilingue.

Monitorate anche i canali social, poiché sui social i problemi di traduzione possono diventare virali rapidamente. In fin dei conti, localizziamo i nostri prodotti e servizi per raggiungere ovunque coloro che non parlano inglese, quindi dovremmo sempre tenere a mente le esigenze degli utenti finali e considerare il loro feedback come la più importante misura del successo.

Nel caso delle aziende business-to-business (B2B), i clienti dei clienti sono importanti, in quanto definiscono il successo del cliente: è infatti l'utente finale a determinare il successo di tutti.

#### Stakeholder primari #3

Questi stakeholder sono rappresentati dalla catena di gestione aziendale. La localizzazione, anche se spesso un business di nicchia, fa parte di un'organizzazione più grande. Per questo, è importante collegare il vostro lavoro e i vostri risultati agli obiettivi delle organizzazioni madri. Un buon rapporto con la vostra catena di gestione è utile durante le trattative sul budget, o quando è necessario richiamare informalmente i team esterni che non seguono le opportune linee guida di internazionalizzazione e localizzazione.

#### Stakeholder secondari

Gli stakeholder secondari includono IT, Finance, HR, M&A, Procurement, Legal, Privacy e Compliance, ecc. Anche se non sono direttamente coinvolti nella fornitura di servizi linguistici o nell'effettivo lavoro di produzione, questi stakeholder devono capire cosa fate, come lo fate e sostenere i vostri sforzi e la vostra strategia. Avere conversazioni regolari con loro per ricercare l'allineamento e costruire la fiducia è un must.

Il reparto di procurement, per esempio, può aiutare indirizzando le richieste per i fornitori non preferiti al team centrale di localizzazione. Il team di localizzazione può quindi garantire che vengano utilizzati i fornitori preferiti, che i sistemi aziendali (come il TMS) vengano utilizzati su più progetti per massimizzare il ritorno sugli investimenti (ROI) e che vengano applicate le tariffe negoziate. 

Il segreto di una collaborazione a lungo termine con il reparto di procurement è duplice: trovare soluzioni che riducano i costi e aumentino le entrate e costruire un rapporto basato sulla fiducia. Il Procurement valorizza i comportamenti etici nei partner: un approccio trasparente, quindi, è fondamentale. In questa partnership, è importante che il globalization leader sia colui che decide quando si tratta di prezzi e coinvolgimento dei fornitori. Il Procurement dovrebbe svolgere un ruolo di esecuzione e di logistica.

Un altro stakeholder secondario cruciale è il reparto Finance. Il Finance può fornire i dati necessari per costruire una proposta di globalizzazione con una solida analisi del ROI, come i dati di vendita specifici per Paese. È possibile che in alcune aziende le informazioni sulle vendite e le priorità del Paese possano essere ottenute dal reparto Sales. 

A volte, i requisiti linguistici per fare affari in un Paese derivano da obblighi contrattuali o legali. Per esempio, gestire correttamente le questioni di privacy e compliance su scala globale, per soddisfare il Regolamento generale sulla protezione dei dati (GDPR) in Europa o la legge federale russa sui dati personali, richiede una solida conoscenza delle norme in più giurisdizioni, nonché una stretta collaborazione con i team Legal e Compliance. 

L'IT è un partner indispensabile per implementare un solido stack tecnologico di localizzazione nell'impresa e per integrarlo con i sistemi di gestione dei contenuti (CMS). Per informazioni su come fare una valutazione della relazione con l'IT, vedere ["Valutare la vostra azienda rispetto all'Azienda ideale"](#assessing-your-company-against-the-ideal-company) nel capitolo ["Panoramica della strategia"](#chapter-2-strategy-overview).

#### Stakeholder primari ma troppo spesso "dimenticati"

Gestire un team di più fornitori che devono collaborare regolarmente è come allenare una squadra nazionale: ci si aspetta che tutti i giocatori indossino la stessa maglia con orgoglio e diano il meglio di sé, ma, appena la partita è finita, ogni giocatore torna alla propria squadra e compete contro gli altri. Influenzarli in modo che lavorino davvero come una squadra ad alte prestazioni è una sfida continua. Tuttavia, quando i giocatori capiscono che il gioco non è necessariamente quello in cui una parte vince e l'altra perde, siete sulla strada giusta.

I dipendenti che lavorano nel Globalization team sono un altro tipo di stakeholder dimenticato. Quando qualcuno si occupa di localizzazione da 10 o 15 anni, dove va dopo? Se avete dei traduttori nel vostro staff, che tipo di percorso di carriera offrite loro all'interno di una grande azienda? 

Una buona soluzione potrebbe essere quella di trasferirli in Product Team o Marketing Team, trasformandoli in solidi partner commerciali nonché i vostri migliori "venditori", con il contestuale avanzamento della loro carriera. Dal punto di vista aziendale, è meglio vedere i dipendenti spostarsi in un altro team sempre all'interno dell'azienda piuttosto che perdere talenti a favore di un'altra azienda o un concorrente. 

Dovreste investire regolarmente tempo e sforzi nella gestione della carriera e nella pianificazione della successione. Perdere talenti è sempre doloroso, specialmente in un settore come la localizzazione, in cui la differenza tra un successo e un fallimento dipende spesso dalla competenza e le conoscenze tecniche di pochi individui. Assicuratevi quindi che, in caso un dipendente chiave lasci l'azienda inaspettatamente, altre risorse siano sempre pronte a sostituirlo.

#### Altri stakeholder indiretti

Questi stakeholder sono rappresentati dai governi locali (fonte di norme e regolamenti che dovete rispettare) e anche dai concorrenti. Potreste non avere a che fare direttamente con questi gruppi, ma avete bisogno di monitorare ciò che stanno facendo, poiché i cambiamenti ambientali più ampi potrebbero avere un impatto sulla vostra strategia e su come gestite il vostro business.

Un esempio è quello della Cina, che non tollera nessuno riferimento a Taiwan come•	"Paese". Ovviamente, se all'improvviso uno dei vostri concorrenti principali espande la sua offerta a dieci nuove lingue, potreste percepire una certa pressione a colmare il divario, o aumentare voi stessi il set di lingue supportate per mantenere il vostro vantaggio competitivo.

### Coinvolgere i vostri stakeholder

Una volta identificati i vostri stakeholder, investite qualche sforzo per creare legami con loro. Identificate e coltivate i sostenitori, gli alleati o gli sponsor in tutti i diversi tipi di stakeholder. Coltivate le relazioni con i colleghi, i quali riconosceranno il bisogno di consultare il vostro team nelle riunioni e vi coinvolgeranno ben presto nelle conversazioni. 

Alcuni stakeholder necessitano di essere gestiti da vicino, mentre altri hanno solo bisogno di essere informati e altri ancora devono semplicemente essere monitorati. L'obiettivo finale è quello di mantenere i vostri stakeholder coinvolti e solidali. Dopo tutto, la gestione degli stakeholder corrisponde a mantenere buone relazioni con le persone che hanno il maggior impatto sul vostro lavoro. 

Sviluppare e sostenere attivamente le relazioni con gli stakeholder porta a un numero di benefici incredibile, e migliorare la gestione del rischio e minimizzare l'incertezza diminuisce indirettamente i costi: accelera la risoluzione dei problemi e il processo decisionale, e aumenta il sostegno degli stakeholder, portando, alla fine, a risultati migliori per l'azienda.

Uno strumento utile per la gestione degli stakeholder è una matrice di priorità, in cui gli stakeholder sono posizionati su due assi perpendicolari, che rappresentano, generalmente, l'influenza e il livello di interesse. Col tempo, man mano che raccogliete informazioni sui vostri stakeholder, potrete aggiungere a questa mappa metadati specifici utili per gli stakeholder, come la frequenza della comunicazione, lo stile di comunicazione preferito, la personalità, le date chiave e le relazioni. 

![Immagine della mappa degli stakeholder](/media/Chapter%203_Stakeholder_Map.png) Gli stakeholder nel quadrante in alto a destra sono la vostra priorità: con loro discuterete e vi accorderete su roadmap, budget, iniziative comuni, risultati strategici, ecc. Il vostro obiettivo è quello di aumentare il livello di interesse dei vostri stakeholder: trattate quindi soprattutto con le persone nei due quadranti superiori. Detto questo, poiché le aziende sono tutt'altro che statiche, nuovi stakeholder potrebbero comparire in uno qualsiasi dei quattro quadranti. Nel caso di un'acquisizione o di una riorganizzazione aziendale, è necessario monitorare attentamente l'ambiente.

Per coinvolgere efficacemente gli stakeholder, si possono utilizzare diverse strategie di gestione degli stakeholder. Queste sono le strategie di base che raccomandiamo per gestire le aspettative e guadagnare fiducia.

1. **Capire la loro vision**. La chiave per coinvolgere efficacemente gli stakeholder sta nel comprendere bene la loro vision. Raccogliendo i requisiti dei vostri stakeholder, capirete meglio le loro preoccupazioni e i loro vincoli, e sarà più facile trovare soluzioni. Quali sono gli obiettivi e i programmi dei vostri stakeholder? Quali sono i problemi che stanno cercando di risolvere? Quali sono le informazioni aggiuntive che vi aiuteranno a capire i loro bisogni e le loro priorità? 

    Esaminate l'urgenza e la legittimità delle aspettative dei vostri stakeholder, chi influenza le loro opinioni e chi essi influenzano a loro volta. Nel trattare con una varietà di stakeholder (dai Product Team agli Executive Team, fino al Procurement, ecc.), dovrete affrontare priorità contrastanti. Quando si deve effettuare una delicata definizione delle priorità, il principio guida è fare ciò che è meglio per l'azienda.
    
    **Fornire supporto nella lingua locale**

> <img src="/media/story_icon.png" alt="Immagine del libro" width="30"/> Nella sua ricerca di mercato per un mercato locale, Diana ha scoperto che c'erano seri problemi di comprensione in uno dei mercati di destinazione, per il quale non venivano forniti prodotti localizzati. Dopo aver confermato i risultati con i team locali, ha poi creato una proposta strategica per migliorare le entrate di quel mercato e affrontare i problemi di comprensione traducendo i prodotti nella lingua preferita dai clienti. 
>
>Uno dei suggerimenti è stato quello di aggiungere al call center più operatori dell'assistenza clienti che parlassero giapponese. Il responsabile dell'assistenza clienti ha riferito a Diana di non ricevere mai chiamate di segnalazione di problemi in giapponese. Diana ha risposto che i clienti non chiamano perché nessuno nel call center parla la loro lingua. 
>
>Per uscire da quell'impasse, Diana ha fatto uso di dati rilevanti. I team locali hanno condiviso le loro analisi di monitoraggio del tempo, mostrando che il team di vendita ha speso il 40% del proprio tempo a risolvere i problemi dei clienti. Il team di vendita sentiva di non essere così bravo nella risoluzione dei problemi come i team di assistenza clienti debitamente formati, e anche questi ultimi team percepivano di essere meglio preparati per risolvere i problemi più velocemente. 
>
>Ricordando a tutti la vision condivisa e l'obiettivo comune, Diana è stata in grado di giustificare l'assunzione di addetti all'assistenza clienti che parlavano giapponese. I team di vendita locali sono stati molto apprezzati, e i clienti hanno sperimentato una risoluzione dei problemi del 70% più rapida. Il tempo di risoluzione dei problemi per questo mercato locale era in linea con i risultati ottenuti per i mercati di lingua inglese. Come risultato, il Net Promoter Score (NPS) della regione è migliorato significativamente. 

2. **Strategia di comunicazione.** Capire la vision dei vostri stakeholder, allinearsi e comunicare con ognuno di loro è il modo più efficace per costruire e mantenere le relazioni. Prendete in considerazione con che frequenza ogni stakeholder vorrà ricevere aggiornamenti, la natura degli aggiornamenti e il loro formato preferito (brief di progetto, incontri faccia a faccia o aggiornamenti visivi come grafici o diapositive?). 

    Concentratevi prima sugli stakeholder più importanti, e dopo su quelli meno cruciali. Assicuratevi di pianificare le vostre interazioni, in modo che il vostro tempo venga usato in maniera efficace. La comunicazione nella gestione degli stakeholder non è un business plan, però vi aiuta a raggiungere alcuni degli obiettivi di business della vostra organizzazione.
    
    **Commissione direttiva di localizzazione**

> <img src="/media/story_icon.png" alt="Immagine del libro" width="30"/> Dopo che la sua organizzazione è diventata finanziata a livello centrale, Larry ha lavorato con il suo manager per formare una commissione direttiva di localizzazione. Ha incluso il suo vicepresidente, i rappresentanti Senior delle unità aziendali a cui è stato assegnato almeno un milione di dollari per la localizzazione, e il reparto di procurement. Gli obiettivi principali di questa commissione direttiva erano di assicurare l'allineamento sulle priorità e massimizzare l'impatto della localizzazione. Il loro approccio includeva: * Spendere il budget disponibile in programmi altamente visibili allineati alla strategia generale dell'azienda. * Migliorare il coordinamento e la pianificazione condividendo un messaggio coerente sulla partnership e l'allineamento a livello di gestione. * Guidare le attività congiunte per migliorare l'efficienza. * Costruire la consapevolezza di eventuali sfide e iniziative a lungo termine per le quali era necessario un certo supporto o approvazione. \*
>
>La commissione, riunendosi con cadenza trimestrale, ha anche collaborato nel definire il finanziamento annuale necessario per sostenere i programmi di localizzazione concordati e allineati con le principali iniziative aziendali.

3. **Educare**. "Evangelization" è il termine usato per indicare il processo di posizionamento delle attività del Globalization team, adottato con l'obiettivo di permettere consegne migliori e di aumentare la fiducia. Assicuratevi che i vostri stakeholder sappiano che il vostro team esiste, che capiscano cosa fate e che si rendano conto di come l'efficienza del team dipenda dalle scelte di design o architettura effettuate a monte della localizzazione. 

    Selezionate gli elementi educativi che condividete con un determinato stakeholder per facilitare la collaborazione e la soddisfazione del cliente, e per migliorare visibilità e fiducia. Se un'ora in più di lavoro del o può eliminare 20 ore di sforzo del Globalization team, allora quest'ultimo dovrebbe essere in grado di convincere il Product Team a inserire questa ora extra. 


    La fiducia è fondamentale, e gli stakeholder reagiscono meglio quando c'è una comunicazione trasparente. Condividere apertamente e chiaramente le vostre conoscenze e le vostre sfide favorisce la collaborazione e l'allineamento, oltre che contribuire a una migliore comprensione. Condividere le proprie conoscenze in modo completo porta a una maggiore fiducia e a un maggiore rispetto.

4. **Stabilire dei limiti**. Stabilire dei limiti vi permette di gestire efficacemente le risorse della vostra azienda e mantenere il benessere del vostro team. Senza limiti, è probabile che ci si concentri sulle priorità degli altri team o si risponda ai loro bisogni invece che ai propri, e il team può diventare meno efficace. Stabilire dei limiti significa anche comunicare indirettamente agli stakeholder come lavorare con voi. 

    In generale, non è necessario stabilire dei limiti per ogni aspetto del vostro lavoro. Tuttavia, vi sono aree a cui un globalization leader deve prestare attenzione, come il budget e le risorse del team. Uno dei limiti che ci si aspetta voi stabiliate è assegnare un budget a un flusso di lavoro che non è efficace dal punto di vista dei costi, così come dedicare un membro del vostro team a un programma perché non è ottimale. Tenete presente che gestire le risorse dell'azienda, a volte, significa anche dire di no ai propri stakeholder. Richiedete le giustificazioni aziendali delle richieste di traduzione o un finanziamento e, in alcuni casi, personale ai team che richiedono lavoro che amplierà l'ambito di consegna della globalizzazione.

    Questo delicato equilibrio tra l'essere un fornitore di servizi e uno stratega può essere semplificato se identificate in modo proattivo i confini, comunicandoli chiaramente e in modo formale. Potrebbe essere necessario creare un sistema o un processo per rafforzare un confine, per esempio creando dei template per le richieste che segnalano ciò che non può essere accolto.

### Gli stakeholder come partner strategici

Nel rapporto con ogni stakeholder, l'obiettivo è quello di passare da quella che viene chiamata "relazione ad-hoc o transazionale" a "consulente di fiducia" fino a "partner strategico" Analogamente allo spostamento dei vostri stakeholder verso l'area di "alto interesse" nella mappa degli stakeholder, il vostro intento è che gli stakeholder spostino la localizzazione nel quadrante in alto a destra nella loro rispettiva mappa, riconoscendo il valore apportato dal vostro team.

In definitiva, come globalization leader, il vostro obiettivo è ottenere dal tempo investito conoscenza, comprensione e gestione degli stakeholder. Passare dall'essere trattati come un fornitore di servizi i cui costi devono essere minimizzati all'essere riconosciuti come partner strategici che contribuiscono alle entrate della vostra azienda e al valore del vostro marchio globale richiede tempo e impegno, ma è anche altamente gratificante. 

La tabella seguente mostra alcuni esempi di tali cambiamenti comportamentali e dei risultati. 

<table>
  <tr>
   <td><strong>Fornitore di servizi</strong>
   </td>
   <td><strong>Partner strategico</strong>
   </td>
  </tr>
  <tr>
   <td>Quando il prodotto inglese sarà pronto, e dopo aver capito la necessità di tradurre il prodotto, i potenziali clienti interni contatteranno il vostro team.
   </td>
   <td>Insieme ad altre unità aziendali interne, si contribuisce alle sessioni di pianificazione per il prodotto inglese.
   </td>
   </tr>
   <tr>
   <td>Il cliente A e il cliente B lavorano con due diversi project manager del vostro team, con glossari differenti e diverse combinazioni di lingue.
   </td>
   <td>Il vostro team si impegna in modo proattivo con diverse unità aziendali per cercare l'allineamento dei glossari e dei set di lingue.
  </td>
  </tr>
  <tr>
   <td>I vostri project manager trascorrono una quantità significativa di tempo a negoziare finanziamenti con potenziali clienti su una base ad-hoc.      </td>
   <td>Durante le sessioni di pianificazione a lungo termine si discute il vostro finanziamento, che permette di sostenere la prevista crescita internazionale della vostra azienda.
   </td>
    </tr>
     <tr>
      <td>Il feedback sulla qualità da parte dei team nazionali vi raggiunge settimane dopo il lancio di un prodotto, o quando i revisori nazionali, con buone intenzioni, implementano modifiche che si traducono in incongruenze o errori di battitura.
      </td>
    <td>Inserite un senior linguist qualificato nei team dei vari Paesi, spingendo i team locali di vendita e marketing a delegare eventuali revisioni a questo esperto (che si dà il caso sia ben integrato con il team di localizzazione).
    </td>
     </tr>
</table>

Potete anche usare elementi della struttura del processo di pianificazione strategica per guidare il coinvolgimento con alcuni dei vostri stakeholder: 



1. Quale problema aziendale state risolvendo? Articolate il risultato aziendale che state cercando di raggiungere. Idealmente, sarà radicato nel feedback dei mercati locali, nella direzione strategica aziendale e nelle capacità e responsabilità del Globalization team. 
2. Come risolverete il problema? Fate le vostre raccomandazioni e sottolineate l'impatto di business della vostra soluzione, insieme al valore che avrà per il cliente. Definite gli stakeholder con cui dovrete coordinarvi. 
3. Cosa bisogna fare? Collaborate con gli stakeholder sulle parti della soluzione rilevanti per le loro funzioni aziendali. Definite una raccomandazione di azione comunemente accettata. Includete informazioni sul budget e sull'organico necessario per avere successo. Legate le metriche di successo a un problema aziendale rilevante per lo stakeholder e avrete guadagnato un forte Ambassador ed Evangelist.
4. Ricercate l'approvazione. Scegliete uno degli stakeholder per presentare il piano al giusto gruppo di dirigenti, con il vostro ambito come parte della soluzione. 
5. Eseguitelo. Una volta ricevute le approvazioni, sarà creato un team interfunzionale per l'esecuzione del piano strategico. Potete affidare il vostro piano alle abili cure dei project manager.
6. Misurate il successo. Mentre il progetto procede, tenete d'occhio le metriche di successo che avete definito. A volte avrete bisogno di modificarle man mano che nel progetto verranno modificati scopi, integrazioni e implementazioni. Dopo il lancio, misurate il successo, ottenete un feedback e aggiustate il progetto in base a tali elementi.

Infine, ricordate che state gestendo il budget per conto di molti stakeholder, e che volete che questi stakeholder siano i vostri partner strategici. La gestione del budget può variare molto da un'azienda all'altra, a seconda del modo in cui il Globalization team viene finanziato e persino del modo in cui la localizzazione viene percepita (dall'essere considerata _costo delle merci vendute_ all'essere trattata come un _investimento_). 

Questi sono alcuni principi di base che contribuiscono a rendere meno stressanti le discussioni sul budget con i vostri stakeholder:

* Integrità indiscussa. Qualsiasi decisione dovrebbe sempre essere presa per massimizzare il beneficio per la vostra azienda nel suo insieme.
* Reputazione consolidata come affidabile, competitiva ed efficiente. I vostri stakeholder non devono avere dubbi sul fatto che gestirete i loro budget di localizzazione in modo efficiente (se applicabile) e che il vostro team è di prim'ordine.
* In definitiva, non è importante se si controlla il budget per la localizzazione o se si ricevono finanziamenti da alcuni stakeholder su base progettuale, i finanziamenti per la localizzazione a sostegno delle principali iniziative aziendali saranno garantiti in un modo o nell'altro.

Gestire un budget di **localizzazione centralizzato** può essere una benedizione e una maledizione al tempo stesso. Vi darà una certa flessibilità perché sarete in grado di reinvestire eventuali risparmi e guadagni di produttività per finanziare iniziative di R&S focalizzate sulla localizzazione, o di intraprendere un nuovo progetto. Vi costringerà però anche ad intrattenere conversazioni difficili con gli stakeholder per dare priorità ad alcune iniziative rispetto ad altre, o per ottimizzare i processi end-to-end, guardando a ciò che accade pre e post-localizzazione. 

Se volete seguire questa strada, vi suggeriamo di collaborare con il reparto di procurement per valutare la spesa complessiva della vostra azienda per la localizzazione, nonché con il Finance per consolidare più budget separati sotto un'unica voce assicurandovi al contempo il consenso dei diversi team che potrebbero essere interessati da questo cambiamento. 

Operare sotto un modello di **charge-back o di finanziamento distribuito** comporta anche un particolare livello di complessità: bisogna infatti bilanciare i costi fissi e gli impegni a lungo termine rispetto una domanda variabile e un finanziamento a breve termine. Confrontarsi regolarmente con gli stakeholder sui loro piani a lungo termine, sulle tabelle di marcia triennali e sulle priorità chiave vi aiuterà a colmare eventuali lacune.

Abbiamo anche visto modelli **ibridi** con la domanda di localizzazione continua finanziata centralmente e la domanda inaspettata o nuova finanziata attraverso meccanismi di bill-back nel primo anno.

In definitiva, il modo per affrontare i problemi di budget è quello di cambiare la prospettiva dalla quale il management aziendale considera la localizzazione. Per assicurarvi il finanziamento di un progetto o di una iniziativa potreste aver bisogno di costruire un solido business case, ma ora dovreste disporre dei partner e i dati necessari per completare questa fase con successo. Vedere il capitolo ["Data Analytics per la strategia di globalizzazione"](#chapter-6-data-analytics-for-globalization-strategy) se pensate che i vostri dati non siano solidi come vorreste.

### Best practice a portata di mano

In qualsiasi azienda, la funzione di globalizzazione si fonda su parternship e fiducia. Costruire partnership e fiducia richiede tempo e può essere fatto solo attraverso azioni intenzionali e comunicazione proattiva. Non volete essere il globalization manager che si impegna con gli stakeholder solo durante un'escalation, o che incontra per primo un Product Manager per dargli la brutta notizia che la loro nuova applicazione non può essere localizzata perché deve essere prima correttamente internazionalizzata. 

Un impegno regolare, coordinato e mirato con tutti gli stakeholder vi aiuterà ad aumentare la visibilità della vostra organizzazione all'interno della vostra azienda, a massimizzare l'impatto che il Globalization team ha sul vostro marchio e sul vostro fatturato aziendale su scala globale, con dati a sostegno della vostra storia di successo, e a guidare miglioramenti ed efficienze di processo sostenute.

Collaborare con una molteplicità di stakeholder è un esercizio delicato e impegnativo. Tuttavia, ricordare le poche best practice elencate qui sotto vi aiuterà a semplificare la vostra strategia:

* Costruire una mappa degli stakeholder solida e dettagliata, e mantenerla in modo proattivo. 
* Identificare i sostenitori e gli alleati all'interno della vostra azienda e informarli regolarmente delle vostre strategie, sfide, piani e successi.
* Impiegare l'aiuto dei colleghi del reparto di procurement per indirizzare attraverso il vostro team le richieste di traduzione che dirette ai fornitori non preferiti. 
* Sfruttare le risorse più esperte nel Paese come "ambassador" locali per costruire partnership e fiducia profonde con gli stakeholder degli uffici sul campo.
* Capire i limiti e i vincoli in cui operano alcuni dei vostri stakeholder, e aiutarli a capire i vostri.



## Capitolo 4: Strategia linguistica 

 "Se parli a un uomo in una lingua che capisce, arriverai alla sua testa. Se gli parli **nella sua lingua**, _arriverai al suo cuore._"
 
_-Nelson Mandela_

### Definire la strategia linguistica

Per ogni azienda o business esiste un'unica strategia linguistica, basata su molteplici fattori tra cui obiettivi di business, clienti, mercati, marchi, prodotti e contenuti. La strategia linguistica è una struttura viva e a lungo termine.

La strategia linguistica comprende un set raccomandato di _lingue,_ per uno scopo aziendale specifico o un gruppo, basato su un'analisi della portata e del risultato desiderato. È spesso legato a KPI come le vendite, le entrate, le visite o gli incidenti di supporto, nonché ad altri fattori come le realtà geopolitiche. È limitata dal budget, dalle risorse, dalle capacità degli strumenti e da altri aspetti pratici.

La strategia linguistica _non è:_ \* Un business plan, anche se spesso ne integra uno. * È necessario capire quali siano i bisogni linguistici specifici di un dato Paese di destinazione, definendo la strategia linguistica con rigore per ogni Paese o regione. Ci possono per esempio essere dei requisiti legali, come in Canada, dove sono supportati sia l'inglese che il francese canadese. In alcuni casi, come in India, a seconda del pubblico di destinazione l'inglese può essere accettato o addirittura preferibile. * Un mandato inflessibile: raramente le aziende ottengono un supporto dall'alto verso il basso per una strategia linguistica obbligatoria, il che significa che l'onere di assicurare il budget è a carico del business owner, mentre al Globalization team compete consultarsi sul giusto set di lingue per capitalizzare i risultati aziendali desiderati.

Le eccezioni esistono e dovrebbero esistere per una politica e un quadro linguistico.


### La rilevanza della strategia linguistica

La strategia linguistica non riguarda tanto la lingua, quanto il raggiungimento del pubblico. Definire le lingue che supportate è il modo in cui potete raggiungere questo obiettivo. Una buona strategia linguistica focalizza la sua attenzione sull'insieme dei mercati che contano di più per il business in base a KPI, branding, e/o altri requisiti specifici del Paese o del cliente. Inoltre, contribuisce ad assicurare (ma non garantire) l'allineamento interfunzionale sul supporto linguistico per quei mercati, migliorando, in definitiva, l'esperienza del cliente internazionale end-to-end.

Per molte persone, è normale associare una lingua ad un Paese. È importante che un globalization leader comunichi la distinzione in modo che una considerazione separata per le lingue, come il francese canadese e il francese parlato in Francia, sia data dalla direzione strategica dell'azienda. Allo stesso modo, avviate le decisioni su quale versione di LATAM Spanish sarà appropriata per lo scopo unico dell'azienda e gli obiettivi di mercato. 

Infine, comunicate che esiste un pubblico internazionale all'interno dei Paesi e delle regioni. La popolazione ispanofona presente negli Stati Uniti, per esempio, deve essere considerata nel caso in cui la vostra azienda sia coinvolta nella distribuzione di servizi o informazioni sanitarie alle comunità.


### Partner e pubblico per la strategia linguistica

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Eva si trova ad affrontare una sfida che ha sperimentato molte volte in aziende grandi e piccole: un costumer journey incoerente nelle interazioni con l'azienda, dalla ricerca e considerazione, fino all'acquisto e infine il supporto. 
>
>Nei mercati Tier 1 come quello francese e tedesco, l'esperienza è relativamente senza soluzione di continuità con un supporto linguistico coerente durante le transazioni del cliente. Tuttavia, per i mercati di livello inferiore, come il Vietnam, il customer journey è disgiunto nel migliore dei casi. 
>
>Mentre per trovare i prodotti dell'azienda il cliente può cercare su Google, quando entra nel sito Web la sua esperienza è in inglese. Quando i clienti chiamano per acquistare, vengono accolti nella loro lingua madre. Tuttavia, se cercano supporto dopo l'acquisto, scoprono che mentre il supporto è disponibile in lingua locale, il processo per recuperare la documentazione o i driver dal sito è di nuovo in inglese. 
>
>Abilitare un certo numero di siti, piattaforme e unità aziendali al supporto di diverse lingue locali non è un compito semplice, e ottenere un accordo tra di loro sulla necessità di coerenza è un processo a sé. 

Definire, accogliere e gestire con successo le esigenze dei vostri partner linguistici e del pubblico aziendale è la chiave per il successo della vostra strategia e della vostra azienda, le cui pietre miliari sono i partecipanti e coloro che beneficiano di una strategia linguistica.

#### Stakeholder chiave

Come indicato nel capitolo precedente, all'interno di un'azienda si può avere una varietà di stakeholder che saranno partner primari o secondari nella gestione e nel successo della strategia linguistica. Gli attori chiave possono avere un ruolo attivo sia nella strategia linguistica che nella sua attuazione. Esempi di questi stakeholder sono Sales, Field Support, IT; funzioni di Marketing o Growth; Product Team e funzioni di localizzazione. 

Oppure possono avere ruoli di supporto chiave intorno alla strategia linguistica, come per esempio Social Media, User Experience, content provider, legal/regulatory, Human Resources, Procurement o Finance. 

Oltre agli stakeholder interni, le aziende possono avere una vasta gamma di stakeholder per la loro strategia linguistica, attraverso "funzioni" esterne. A seconda del focus aziendale, vi possono essere partner, investitori, legali, enti regolatori, enti governativi e speciali settori di clienti verticali come stakeholder. 

Ognuna di queste funzioni può rappresentare gli stakeholder chiave, i clienti e i potenziali clienti; prendete in considerazione tutte queste aree quando costruite la vostra strategia linguistica.


#### Fattori chiave della strategia linguistica

Come menzionato nel Capitolo 2, ["Panoramica sulla strategia",](#chapter-2-strategy-overview) a seconda della struttura e delle operazioni dell'azienda, un certo numero di stakeholder chiave può anche fungere da motore della strategia linguistica. 

Questi driver possono includere quanto segue:

![Immagine driver strategia linguistica](/media/Chapter%204_Lang%20Strategy%20Drivers.png)

I driver della strategia linguistica possono variare a seconda di molti fattori, tra cui il tipo di azienda (B2B, B2C, Consumer, Non-Profit, ecc.), il mercato verticale dell'azienda. I driver della strategia linguistica possono partecipare o essere inclusi nelle iniziative di governance. (Vedere la sezione 5.6) Indipendentemente dal titolo o dal dipartimento, la strategia linguistica è tipicamente guidata da una di queste tre forze:

* Il desiderio di attrarre clienti (per acquistare, partecipare, donare, ecc.).
* Il desiderio di semplificazione - spostando i clienti da modalità di contatto più costose o complicate, come il telefono, a modalità meno costose come il self-help sul web.
* Il desiderio di aumentare la soddisfazione generale del cliente.

Queste forze motrici sono ciò di cui avete bisogno per cavalcare l'onda. Affiancando queste iniziative e collaborando con gli individui o le iniziative che le stanno guidando, aumentano le possibilità di successo nell'educazione al valore di una strategia linguistica unificata (o almeno ben pensata) e nella sua vendita.

### Costruire la strategia

Quando si definisce una strategia linguistica, è necessario prima di tutto concentrarsi sugli obiettivi di business dell'azienda e dare loro priorità. Considerate quanto segue:

* **Tipo di attività**

    Siate consapevoli del tipo di business in cui si colloca la vostra azienda. A seconda che si tratti di un business di tipo B2B o B2C, la strategia può essere totalmente diversa. I requisiti linguistici differiscono in base a una vasta serie di fattori commerciali e culturali, locali e internazionali.

* **Esperienza del cliente**
    * Analizzate l'esperienza del cliente e identificate le lacune nel suo percorso, dalla prevendita al supporto. Quali sono i punti dolenti? In quale fase del customer journey state perdendo clientela, senza riuscire a convertire un contatto in un lead e in una vendita? L'esperienza del cliente si modifica e cambia nel tempo, insieme ai principali cambiamenti aziendali (la digital transformation, per esempio)?
    * Collegate il supporto linguistico alle iniziative Go To Market; capite cosa ci vorrà per coinvolgere e supportare realmente i clienti che parlano le lingue in cui localizzate il vostro prodotto o applicazione.
* **Vincoli di bilancio**
    * I costi sono diversi a seconda dell'approccio. È possibile sostenere la strategia linguistica attraverso un mix di traduzione umana, MTPE (traduzione automatica e post-editing) e traduzione automatica non modificata (Raw MT). Questi metodi possono essere combinati in vari modi, a seconda della tolleranza del mercato per i contenuti tradotti automaticamente e il livello di visibilità per i diversi tipi di contenuto. Siate flessibili:
    * negoziare nel tempo con gli stakeholder per raggiungere il risultato finale, sulla base del budget e delle risorse disponibili. Assicuratevi di avere più dati possibili per le vostre trattative. Assicuratevi che gli stakeholder si impegnino con voi a raggiungere il risultato finale.
    * Se la strategia linguistica è stata approvata dagli stakeholder dirigenziali (o da qualsiasi senior executive della società), il Globalization team ha un ottimo strumento su cui far leva nelle discussioni con le unità aziendali e gli stakeholder che hanno bisogno di localizzare i loro prodotti.
* **Livelli di lingua**
    * Adottate una strategia flessibile per le vostre scelte linguistiche, in modo da adattarle alla crescita del mercato, ai vincoli aziendali interni (come il budget), ai requisiti aziendali e normativi esterni e alle preferenze dei clienti. Questi livelli possono diventare più complessi con l'espansione e la maturità dell'azienda. 

        L'obiettivo della traduzione, talvolta, differisce a seconda delle singole lingue. Nelle regioni in cui un prodotto non è venduto, potrebbe per esempio non essere necessario tradurre le informazioni sul prodotto. Una delle best practice, tuttavia, è quella di ridurre la personalizzazione per lingua in favore della scalabilità delle operazioni.

    * Considerate le lingue di economie di nicchia o long tail. Quale dovrebbe essere l'approccio alle lingue long tail? Per le lingue ad alto volume, il business case è spesso solido, ma man mano che ci spostiamo verso i mercati tier 2, tier 3 e quelli più piccoli, la giustificazione diventa più difficile. 

        Per prodotti o domini specifici, tuttavia, la necessità è reale (considerate per esempio, Translators Without Borders o altre ONG coinvolte in operazioni di salvataggio su scala globale, che potrebbero prioritizzare le lingue o costruire una strategia linguistica in modi diversi).
    * Dovreste considerare il divario digitale tra le lingue. Un aspetto di questo elemento è la terminologia: per molte lingue di economie long tail, tradurre le tecnologie d'avanguardia non è facile. Anche se queste lingue long tail hanno creato nuove terminologie, i clienti potrebbero avere difficoltà a comprenderle, potrebbero non essere facili da capire per i clienti. 
    * Il livellamento linguistico può aiutare il vostro modello di coinvolgimento dei fornitori e di consegna. Per le lingue di alto livello si potrebbe prendere in considerazione l'assunzione di linguisti dedicati e language lead, o un processo di selezione dei fornitori e dei requisiti diverso e più rigoroso. Per ottenere i risultati desiderati nel mercato di destinazione, potreste aver bisogno di un fornitore per ogni lingua o sottoinsieme di lingue.
* **Le eccezioni**

    Nonostante l'esistenza di una strategia linguistica ufficiale, essa dovrebbe essere considerata più un ideale a cui aspirare che un obbligo. Nelle grandi e complesse organizzazioni commerciali, alcune unità aziendali o filiali potrebbero avere esigenze commerciali specifiche o un pubblico limitato. Di conseguenza potrebbero decidere di supportare un set di lingue che differisce dal POR (plan of record) ufficiale. In genere, tradurranno meno lingue, poiché gestirne un numero maggiore potrebbe rivelarsi problematico (dal momento che aumenterebbe i rischi di lacune nel customer journey). D'altra parte, quando i prodotti sono strettamente correlati, e molti clienti hanno installato più prodotti, allineare la strategia linguistica per i prodotti è ragionevole.

### Componenti e allineamento 

Quando si progetta una strategia linguistica, pensare e progettare in senso ampio produrrà una strategia più solida e duratura. La copertura di una vasta gamma di criteri, l'allineamento delle componenti linguistiche e la definizione delle best practice di governance contribuiscono alla creazione di un approccio globale flessibile. 

Alcuni esempi di componenti della vostra strategia linguistica sono:

* La conformità con i requisiti legali regionali (per esempio, UE) o nazionali (vedere questo [articolo di Slator](https://slator.com/what-you-need-to-know-about-eu-language-law/) o l'applicazione del regolamento di forza maggiore per la copertura linguistica in Francia).
* Requisiti specifici del Paese, che potrebbero dettare elementi della strategia linguistica (se fate affari in Canada, ad esempio, potreste aver bisogno di supportare sia il francese che l'inglese).
* Il tipo di azienda e il mix di prodotti che possono guidare parti della strategia linguistica. 
* Requisiti specifici del cliente che potrebbero dettare aspetti della strategia linguistica. Per esempio, i driver preinstallati sui sistemi HP o Dell devono essere localizzati dai loro fornitori in 20 lingue. Ecco un altro esempio: fare affari con entità governative, università e sistemi scolastici potrebbe richiedere una localizzazione completa.
* Un sistema di "giustificazione" per aggiungere o eliminare una lingua. Potrebbe essere abbastanza semplice, o più complesso:
    * Raggiungere il 98% degli utenti del web nella loro lingua madre
    * Aggiungere il supporto per la lingua X quando le entrate dei Paesi in cui si parla la lingua X raggiungono € xxx
    * Aggiungere il supporto per la lingua X se la lingua X è supportata anche dai principali concorrenti, ecc.
* Un modello di dati e una raccolta di dati per la misurazione e l'allineamento della vostra strategia linguistica (vedere il modello di strategia linguistica nel capitolo ["Data Analytics per la strategia di globalizzazione"](#chapter-6-data-analytics-for-globalization-strategy)). Per costruire una strategia linguistica robusta, questo tipo di modello combina vari punti dati, come dati sul Paese, dati sugli utenti, dati sulla concorrenza, dati sui costi, dati sulle vendite, dati normativi, ecc. 

Alla fine, la strategia linguistica dovrebbe sostenere una solida storia di ROI, minimizzare i rischi legali e geopolitici e migliorare l'esperienza complessiva del cliente su scala globale.

Diverse lingue potrebbero essere supportate per ragioni completamente diverse (aspetto sociale, buone PR, come nel caso di Apple, Google, e Microsoft che offrono supporto per il cherokee nei loro sistemi operativi) - poiché ovviamente la motivazione del ROI è scarsa (a meno che non si consideri una quantità significativa di avviamento).

Infine, per la governance è necessario capire che la strategia linguistica non è statica né fissata a vita. Le esigenze aziendali, l'ambiente e le condizioni esterne si evolvono, quindi anche la strategia deve adattarsi ed evolvere nel tempo. Questo richiede un processo di aggiornamento della strategia, nonché una chiara comprensione dell'aggiunta o della rimozione del supporto per una o molte lingue.

La governance costruita attorno alla strategia linguistica è più semplice, e potenzialmente più efficace, quando c'è una forma base di accordo organizzativo interfunzionale sulle linee guida aziendali e di gestione (per esempio, la manutenzione) delle lingue.

Una volta in funzione le componenti della strategia linguistica, potrebbero essere necessari dei perfezionamenti per personalizzare e mantenere in modo appropriato i casi d'uso.

* Rafforzate la flessibilità per una varietà di formati di consegna del contenuto, come ad esempio video, chat, text-to-speech, immagini grafiche, ecc.
* Praticate "rollout organizzati" per la vostra copertura linguistica.
* Capire che la vostra strategia linguistica potrebbe aver bisogno di adattarsi, anche a livello di paese, alla popolazione target. Per esempio, se il vostro pubblico è composto principalmente da professionisti urbani in India, potrebbe essere accettabile utilizzare solamente l'inglese. Tuttavia, se il vostro pubblico è più rurale, per raggiungere il pubblico in una lingua ad esso comprensibile potreste aver bisogno non solo dell'hindi, ma di altre cinque, dieci o più lingue locali.

### Governance: best practice per la supervisione della strategia linguistica

Una soluzione che un'azienda può adottare per solidificare la propria strategia linguistica è la creazione di una commissione direttiva di supervisione o di governance. Questa commissione ha gli occhi puntati sul business generale dell'azienda e rivede la strategia generale dei prodotti, il portfolio e le relazioni con i partner, compresa la strategia linguistica, considerata parte di questo sforzo. In un contesto di supervisione più ampio, la commissione può assumere la forma di un consiglio di governance. 

La missione di un tale commissione, o consiglio, non è l'elaborazione di una strategia linguistica: questa funzione è di solito svolta da un team di strategia, da un Globalization o Localization team o forse da qualche altra organizzazione. L'obiettivo che il consiglio ha all'interno della società è quello di garantire la conformità con le strategie ratificate e supervisionare la governance per le iniziative aziendali. 

Andando oltre l'attenzione al solo prodotto, un consiglio di governance, _rivede_ e _controlla_ la conformità, la strategia generale (come la strategia linguistica o le condizioni U/X), la strategia di mercato, finanziaria, normativa e legale per le offerte aziendali. Per assicurarsi la maggiore efficacia, nel consiglio dovrebbe sedere anche il personale esecutivo che rappresenta il prodotto, il Marketing, l'area Sales/Field, l'IT, il Customer Support, le funzioni Legal e Finance nonché Globalization.

Come parte del processo del prodotto aziendale, può esistere una funzione di gruppo parallela, spesso chiamata New Product Introduction. Su una scala più limitata, una commissione per l'introduzione di un nuovo prodotto mira a garantire che per ogni prodotto o nuovo rilascio di prodotto vi sia un piano aziendale in atto e che per ogni parte del piano siano ad esso assegnati i fondi appropriati. 

L'obiettivo della commissione è quello di fornire una supervisione nel coordinamento degli sforzi relativi al rilascio attraverso tutti i gruppi rilevanti, come Ricerca & Sviluppo (Product owner, UX Design), Strategy, Sales, Marketing, Customer Success, TechSupport, rappresentanti del CTO e team legali. Pertanto, normalmente i rappresentanti di questi gruppi vengono inclusi in questa commissione. Dal punto di vista internazionale, questo gruppo controllerebbe, tra le altre cose, la conformità all'internazionalizzazione dei prodotti, le questioni normative e le condizioni del mercato internazionale. 

Per entrambe queste funzioni di gruppo, è estremamente importante per un leader della globalizzazione ottenere un posto a quel tavolo. In questo modo, potrà essere in grado di esprimere qualsiasi dubbio relativo alla strategia linguistica. Per esempio, quando una nuova lingua viene aggiunta alla prossima versione del prodotto e si stanziano i fondi per questo progetto, il compito della commissione è quello di controllare che tutte le altre attività relative al lancio del prodotto in un nuovo mercato non siano solamente state pianificate, ma anche finanziate. 

Tali attività possono includere l'assunzione di personale di vendita e di risorse di marketing nel nuovo mercato, ma anche l'assegnazione di budget per le attività di marketing, oltre alla localizzazione del sito Web e di qualsiasi materiale collaterale nella nuova lingua. Potrebbero anche sorgere preoccupazioni di carattere legale connesse alla mancata localizzazione di certi materiali o all'accesso al prodotto in mercati specifici. 

Un'organizzazione matura può disporre di un modello che favorisce un approccio olistico al lancio del prodotto in un nuovo mercato. Il più delle volte, tuttavia, garantire che tali questioni siano sollevate e affrontate è un compito che spetta a un globalization leader.

### Comprensione approfondita della strategia linguistica

Mentre definite e perfezionate la vostra strategia linguistica, è utile avere una comprensione di base delle differenze tra le varie lingue o famiglie linguistiche, i luoghi, gli alfabeti e altri aspetti culturali che potrebbero avere un impatto sul modo in cui implementate la vostra strategia.

#### Lingua parlata o scritta

Una prima differenza da tenere in considerazione è quella tra le lingue parlate e quelle scritte. Potremmo naturalmente distinguere le lingue che esistono per lo più in una forma solo parlata, alcune delle quali classificate come in pericolo, da quelle che esistono sia in forma parlata che scritta. 

Secondo i dati di Ethnologue[(https://www.ethnologue.com](https://www.ethnologue.com/)), circa 4.000 delle 7.150 lingue parlate oggi nel mondo, cioè circa la metà, hanno sviluppato un sistema di scrittura. Solo 100 di queste possono essere considerate "lingue veicolari", e solo una decina di esse vi permetterà di raggiungere il 90% della popolazione mondiale in una lingua da essa parlata, sia come lingua nativa che lingua ufficiale: queste lingue sono il cinese e inglese, insieme ad hindi, arabo, spagnolo, bengalese, portoghese, russo, urdu, francese, giapponese e tedesco. Ciononostante, alcune di queste lingue vengono ancora ignorate da molte aziende internazionali, che però supportano altre lingue capaci di raggiungere una popolazione relativamente più piccola (anche se probabilmente più ricca, in termini di PIL pro capite).

Le ragioni per cui menzioniamo qui le lingue parlate e scritte sono:

* Storiche, poiché nell'area della localizzazione di software o contenuti si lavorava soprattutto con testi scritti. Tuttavia, ci aspettiamo che nel prossimo futuro la globalizzazione abbia sempre più a che fare con applicazioni vocali e interfacce di conversazione, il che richiederà al nostro settore di diventare più efficiente nella gestione del testo parlato. 

    Ad oggi, gli assistenti vocali come Alexa, Cortana o Siri supportano solo alcune lingue, comprese alcune varianti (accenti), ma con l'avanzare delle capacità di AI, ML e NLP, saranno supportate più lingue. Le interfacce di conversazione multilingue sono fondamentali per i chatbot utilizzati nell'assistenza clienti o per gli assistenti vocali che mettono in collegamento gli esseri umani a un mondo sempre più digitale, compresi i veicoli autonomi.

* Il testo scritto significa che vi è un alfabeto, e conservare dati scritti necessita di una codifica adeguata. Questo è stato storicamente un problema delicato per la localizzazione, ma oggi, grazie allo standard Unicode, gestire e conservare le stringhe di testo è diventato molto più facile.
* Ogni forma, parlata o scritta, ha le sue specificità: la permanenza del linguaggio scritto si contrappone all'immediatezza del linguaggio parlato; la complessità e intricatezza del primo, poi, sono contrarie alla semplicità e tonalità del secondo. Ovviamente, dal punto di vista della complessità o dell'uso grammaticale, il discorso scritto o registrato può assomigliare molto al linguaggio scritto.

Le lingue scritte possono essere classificate in due gruppi principali in base ai loro sistemi di scrittura: un gruppo è quello delle lingue con caratteri che rappresentano consonanti e vocali (ossia alfabeti) e l'altro è quello delle lingue con caratteri rappresentanti sillabe (ossia sillabari).

Tra le scritture alfabetiche possiamo includere:

* L'arabo, il farsi (persiano), l'ebraico e l'urdu, tutte lingue scritte da destra a sinistra, considerate anche lingue consonantiche (lingue Abjad).
* Tutte le lingue basate sulla scrittura e alfabeto latino, nella sua forma estesa che include gli accenti diacritici, oggi comprendono la maggior parte delle lingue dell'Europa occidentale e centrale (alcune delle quali possono anche usare la scrittura cirillica o araba), così come lingue come il vietnamita o lingue africane per le quali la scrittura è stata sviluppata dai colonizzatori europei, come è accaduto per lo zulu.
* Tutte le lingue basate sull'alfabeto cirillico.
* Il greco.
* Gli alfabeti Hiragana e Katakana spesso usati in giapponese, soprattutto per le parole prese in prestito da altre lingue.
* Il coreano (alfabeto hangul).
* L'armeno, il gaelico, il georgiano, il mongolo, N'Ko, Tifinagh, ecc.

Tra le lingue sillabiche, possiamo includere:

* Le lingue logo-sillabiche come il cinese e il giapponese (Kanji), in cui i caratteri rappresentano sia il suono (sillaba) che il significato, le cui parole sono composte da uno o più caratteri. In genere, ad ogni possibile sillaba corrispondono più caratteri, ognuno con un significato diverso.
* La maggior parte delle lingue del subcontinente indiano, come Bengali, Hindi (Devanagari), Malayalam, Punjabi, Tamil, Telugu, ecc;
    * Il birmano, lo Khmer, il Lao.
    * Il Thai. Una particolarità del thailandese è che nella sua forma scritta non usa separatori tra le parole (come facciamo ad esempio in italiano, per cui si utilizzano spazi per separare le parole). La funzione degli spazi, in tailandese, è equivalente a quella del punto in italiano, ossia segnalano la fine di una frase.
    * Il cree, l'etiope, l'inuktitut, il tibetano.

Citiamo qui il caso interessante del bamum, una lingua parlata in alcune parti del Camerun: storicamente, al momento della sua creazione, nel 1896, questa lingua ha iniziato ad utilizzare una scrittura sillabica, ma è poi passata ad una scrittura alfabetica durante l'era coloniale francese. Oggi si cerca di far rivivere il sillabario del bamum nonostante il fatto che molti libri, così come il corrispondente materiale di stampa, siano stati distrutti un secolo fa.

#### Considerazioni linguistiche e culturali che influiscono sulla localizzazione

Con così tante lingue, sistemi di trascrizione e località, ognuna con norme culturali specifiche, è necessario prendere in considerazione molte differenze, le quali potrebbero avere un impatto significativo sul successo di un progetto di localizzazione, o semplicemente sull'esperienza complessiva dell'utente. Tuttavia, non è generalmente possibile affrontare tutto, e si dovrebbe evitare che questa marea di dettagli vi confonda o vi paralizzi. Elencheremo alcune considerazioni abbastanza generiche, confidando che non avrete difficoltà ad espandere questa lista con argomenti che sono rilevanti per la vostra azienda o i vostri prodotti.

* **Espansione del testo - Se**avete mai confrontato diverse versioni dello stesso contenuto scritto in italiano, inglese, spagnolo, russo o cinese, saprete che la quantità di spazio necessario per ogni versione varia a seconda della lingua. Lo spagnolo e il russo, così come la maggior parte delle lingue dell'Europa occidentale o orientale, occupano più spazio dell'inglese. 

    Sarà quindi saggio tenere conto di un'espansione del testo del 30% o più, cosa che in un PDF o in una presentazione PowerPoint può avere un impatto sul layout. Tuttavia, per frasi o segmenti brevi, come il testo di un pulsante dell'interfaccia utente (una o due parole), l'espansione del testo può raggiungere il 300% o più. I vostri esperti di desktop publishing (DTP) potrebbero ovviamente trovare il modo di regolare la dimensione del carattere o giocare con le impostazioni di kerning e tracking nel vostro documento, ma l'approccio migliore è quello di chiedere ai vostri creatori di contenuti di lasciare un po' di spazio bianco. In sostanza, evitate di stipare troppi contenuti nella stessa pagina o diapositiva. 

    Rispetto all'inglese, ad esempio, sull'asse orizzontale il cinese è normalmente più corto, ma potrebbe richiedere un po' più di spazio in verticale. Potreste anche essere limitate dalle misure dei caratteri, dato che, mentre la maggior parte dei caratteri inglesi potrebbe essere ancora leggibile con una dimensione di 7 punti, alcuni caratteri cinesi sarebbero così più difficili da decifrare. Ancora una volta, concedetevi un po' di spazio; questo renderà in ogni coso il vostro contenuto più piacevole per il lettore.

* **Bi-direzionalità - Anche se**spesso si parla di lingue da sinistra a destra o da destra a sinistra, nella pratica è più preciso parlare di lingue bidirezionali, come l'arabo o l'ebraico, che hanno preso in prestito parole inglesi. Le difficoltà sorgono quando all'interno del testo italiano, tipicamente caratterizzato da una forte direzionalità da sinistra verso destra, viene ad esempio incorporato un paragrafo arabo, che dà al contenuto una forte direzionalità da destra a sinistra. 

    Per complicare le cose, alcuni caratteri possiedono quella che viene definita una direzionalità "debole"; il che significa che il loro posizionamento a destra o a sinistra di un'altra parola dipenderà dalla lingua del testo che li circonda. Qui, l'opzione migliore per voi è quella di affidarvi alla competenza dei vostri linguisti arabi o ebraici e, quando necessario, utilizzare i caratteri di controllo invisibili Unicode per assegnare a un carattere debole una forte direzionalità.

* **Moduli utilizzati per la raccolta di informazioni personali - Qui**, il problema principale riguarda le norme culturali. Idealmente, la maggior parte dei moduli dovrebbe essere dinamica. Dovrebbero esserlo soprattutto i moduli di registrazione, in cui si chiede all'utente di fornire le sue informazioni di contatto, tra cui, un indirizzo, un numero di telefono e un codice postale, o di selezionare uno Stato da un menu a tendina. 

    Tradurre alcuni di questi concetti da un paese all'altro è faticoso. Ma, per favore, non costringete le persone a specificare un codice postale, o a dover inserire un numero di telefono di 10 cifre con un prefisso di 3 numeri. Questo vi segnerà come 'americano-centrici' 

    Evita di eseguire controlli che potrebbero rifiutare come non valida una lettera c con cediglia (ç), una lettera n con tilde (ñ), o una lettera u con umlaut (ü), poiché tutte queste lettere sono perfettamente valide in altre lingue e si trovano in nomi e cognomi, o nomi di città. E se li accettate per l'input, assicuratevi che i vostri sistemi interni non li corrompano ad un certo punto, trasformando un nome o un indirizzo perfettamente valido in una stringa di caratteri senza senso.

* **Raccolta:** di solito usato per significare "ordinamento", in realtà, molte lingue hanno le loro norme per ordinare le liste, il che può essere utile quando si ha bisogno di selezionare una voce in un lungo menu a discesa, o in una lunga lista di termini. Da un punto di vista UX, è necessario ordinare il contenuto, che potrebbe essere bilingue (ad esempio, una biblioteca digitale che include centinaia di titoli sia in inglese che in coreano), in un modo che abbia senso per l'utente. Altrimenti, potreste anche visualizzare tutti gli elementi di quella lista in modo casuale, ma se lo fate con il vostro contenuto inglese, potreste non trattenere i vostri utenti molto a lungo o raggiungere un alto grado di soddisfazione degli utenti con il vostro prodotto.
* **Genere e forme possessive:** anche se le persone hanno un genere, l'inglese è fondamentalmente una lingua neutra dal punto di vista del genere. Cioè, la lingua inglese non ha bisogno di preoccuparsi di nessun tipo di accordo di genere (né di numero) tra aggettivo e nome. Ma tradurre il segmento "Dear <firstname>" è problematico con la lingua per la quale l'aggettivo deve concordare nel genere con il genere della persona che si saluta, così "Dear Georges, Dear Elizabeth" diventerebbe, in francese, "Cher Georges, Chère Elizabeth" o in spagnolo, "Querido Georges, Querida Elizabeth". 

    In modo simile, le stringhe "His car | Her car | His boat | Her boat", dove il pronome possessivo si riferisce al proprietario della cosa, si tradurrebbe in francese come "Sa voiture | Sa voiture | Son bateau | Son bateau", dove il pronome possessivo concorda nel genere con la cosa posseduta, indipendentemente dal genere del suo proprietario.

* **Forme plurali:** l'inglese è anche abbastanza semplice quando si tratta di forme plurali, con solo due opzioni: hai una unità di qualcosa, o zero, due o più unità di qualcosa. Altre lingue possono avere un modo molto più complicato di gestire tutto questo, con fino a cinque o anche sei forme plurali diverse. Anche qui, il Consorzio Unicode è vostro amico, dato che hanno documentato tutto quello che c'è da sapere in uno dei loro report tecnici.
* **Concatenazione e variabili (segnaposto):** Consideriamo una frase come "Results 11~20 of 136", posta all'inizio di una pagina in cui la vostra applicazione mostra i risultati di una query, 10 risultati alla volta. In giapponese, questa frase diventerebbe "結果136の11~20", e si nota subito che 136 viene prima di 11~20, contrariamente alla struttura inglese. 

    Ora, immaginate che la frase che inviate alla traduzione sia in realtà composta da due segmenti, "Results" e "of", concatenati a runtime come "Results + <displayed\_range> + of <total\_number\_of\_results>". Non solo rischiereste di ottenere una traduzione per la parola "of" che potrebbe non essere corretta nel contesto, ma la vostra frase giapponese imiterebbe l'ordine del costrutto inglese, il che sarebbe scorretto. 

    L'ideale sarebbe inviare per la traduzione una frase come "Results {0} of \\1\\", che rende possibile ai traduttori di collocare correttamente {0} e \\1\\ nella versione tradotta. Tuttavia, perché questo funzioni, dipendete dai vostri sviluppatori che usano variabili (segnaposto) invece di "hack intelligenti" che funzionano solo per alcune lingue. 


    Anche se molte lingue usano costrutti grammaticali basati sull'ordine Soggetto-Verbo-Oggetto (SVO) usato in inglese, il giapponese usa Soggetto-Oggetto-Verbo (SOV), che è in realtà il tipo più comune tra le lingue naturali con una preferenza di ordine delle parole.


### Una strategia linguistica di successo

Chiaramente, visto che abbiamo appena scalfito la superficie, il diavolo è nei dettagli quando si tratta di capire come le differenze tra le lingue possono influire su un progetto di localizzazione. Queste sono considerazioni da valutare nella costruzione della vostra infrastruttura e strategia linguistica. 

La verità è che non siete soli. Tutti i vostri colleghi del settore hanno già sperimentato questi problemi, e voi avete un fantastico pool di risorse che possono fornire una guida esperta: i vostri traduttori, linguisti ed esperti di localizzazione. Anche l'esperienza aiuta, ma nessuno si aspetta che voi ricordiate aspetti specifici che potrebbero significare problemi per una qualsiasi delle lingue multiple che supportate. 

Dovete identificare i problemi, valutare l'impatto e discutere le possibili risoluzioni con il vostro team esteso, il che significa che dovete rendere gli "autori" di contenuti parte di questa discussione, specialmente se avete bisogno che adottino nuove pratiche di scrittura o codifica. 

Col tempo, potreste notare che i problemi più evidenti, quelli che hanno un impatto sui vostri più grandi mercati esteri, o forse i meno complessi da risolvere, smettono di comparire nei vostri prodotti inglesi. Questa sarebbe una buona indicazione che state facendo qualcosa di giusto e che siete riusciti a influenzare i vostri stakeholder ad adottare un approccio più favorevole alla localizzazione. Prendetevi una pausa, ve la siete guadagnata, e festeggiate!

>***Volere approfondire l'argomento?*** * [Global Language Hotspots](https://www.swarthmore.edu/SocSci/langhotspots/fastfacts.html) * [Differences between writing and speech](https://omniglot.com/writing/writingvspeech.htm) \* David Bellos (2012), Is That a Fish in Your Ear?, Faber and Faber Inc. * [Bamum Script](https://en.wikipedia.org/wiki/Bamum_script) * [The Unicode Standard, Bamum](https://www.unicode.org/charts/PDF/UA6A0.pdf) * [The Unicode Standard, Bamum supplements](https://www.unicode.org/charts/PDF/U16800.pdf) * [Plural Rules](http://cldr.unicode.org/index/cldr-spec/plural-rules) * [Soggetto Verbo Oggetto](https://en.wikipedia.org/wiki/Subject%E2%80%93verb%E2%80%93object)



## Capitolo 5: Strategia tecnologica

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Nel ruolo di Localization Technology leader in una grande azienda di software, Diana ha gestito uno strumento di localizzazione di importanza fondamentale, un Translation Management System (TMS) che inviava automaticamente i contenuti dai repository dei prodotti tramite un ciclo di traduzione. Il TMS collegava fornitori e revisori e forniva ai project manager uno stato aggiornato di ogni tipo di lavoro come software, help center, marketing e materiali di vendita. 
>
>Diana era molto orgogliosa del successo del lavoro del suo team sulle integrazioni e la capacità di supportare molti tipi di contenuti. Il sistema centralizzato ha ridotto significativamente i costi di localizzazione aumentando l'utilizzo di contenuti simili tradotti in precedenza e ha permesso un tempo di completamento più veloce. 
>
>Un giorno ha incontrato un dirigente di marketing in un corridoio che le ha raccontato casualmente che il Marketing Team stava firmando un contratto per acquistare un diverso TMS per supportare la traduzione del sito Web. È riuscita a convincere il dirigente che sarebbe stato utile organizzare una riunione per discutere i pro e i contro prima di firmare il contratto. 
>
>Nel corso di quella riunione, Diana ha scoperto il principale vantaggio del nuovo TMS: avrebbe permesso ai revisori di apportare modifiche in un ambiente facile da usare. Di contro, il nuovo ambiente ha reso tutte le altre fasi del flusso di lavoro più complicate per gli altri partecipanti, compresi i fornitori. 
>
>Poiché i principali stakeholder della dirigenza erano i revisori, il ragionamento di Diana cadde nel vuoto e alla fine della riunione la dirigenza procedette con il suo piano di acquisto di un TMS separato. Avere due Translation Management System è davvero sbagliato?
>
>Scoprite più avanti in questo capitolo cosa fa Diana.

Benvenuti nel mondo di un globalization technology leader, il cui compito è quello di rispondere a queste domande e sviluppare una strategia tecnologica che si adatti agli obiettivi di business, rifletta le esigenze del momento e supporti la crescita futura dell'impresa. 

La strategia tecnologica di globalizzazione deve essere vista come parte di una strategia globale di Go to Market, in grado di soddisfare le richieste aziendali di time to market, esperienza utente, risparmio dei costi e crescita globale in tutte le aree dell'azienda, compresi reparti Product, Marketing, Legal, Customer Suppor, ecc. Al centro, gli strumenti di globalizzazione, quando combinati e strettamente integrati con lo stack tecnologico utilizzato dai team di stakeholder, permettono di rendere il costo per parola una merce e di concentrarvi sulla strategia, invece che sull'esecuzione. 

### Cos'è una strategia tecnologica di globalizzazione?

Una strategia tecnologica di globalizzazione è un piano basato su principi, obiettivi e tattiche per usare la tecnologia per raggiungere obiettivi aziendali strategici. Sviluppare la vostra strategia tecnologica comporta l'identificazione di tecnologie specifiche e delle risorse responsabili della loro gestione, così come dettagliare la scalabilità futura e assicurare che le tecnologie scelte siano allineate agli obiettivi di business. 

Una suite tecnologica che soddisfi tutti o alcuni di questi obiettivi può richiedere un investimento significativo sia di tempo che di denaro e può essere molto costosa da implementare, dal momento che bisogna considerare i costi del fornitore, del team interno e dell'infrastruttura. In particolare, a causa della mancanza di uno standard nella tecnologia di parsing TMS e dei requisiti di integrazione CMS specifici dell'azienda, passare da un TMS a un altro può richiedere uno sforzo molto costoso. 

Pertanto, l'acquisizione di una tecnologia TMS dovrebbe essere vista come un investimento a lungo termine (almeno da cinque a dieci anni). Gli obiettivi generali di business della vostra azienda esercitano la maggiore influenza sulla strategia tecnologica e cambieranno nel tempo, quindi la vostra strategia dovrà adattarsi all'evoluzione degli obiettivi di business. Ma volete anche essere in grado di approfittare delle nuove tecnologie che possono far progredire il vostro programma di globalizzazione e funzionare man mano che diventano disponibili.

Il processo di sviluppo della strategia qui descritto può essere visto come un processo ideale passo dopo passo, ma sappiamo che il mondo reale è molto più disordinato. Ad esempio, gli obiettivi dell'azienda cambiano, avvengono acquisizioni, ci sono diversi marchi da considerare e i finanziamenti non vengono approvati. Prendete da questo processo ciò che funziona meglio per voi e la vostra organizzazione.

Oltre a sviluppare la strategia, considerate altri fattori che influiscono sul suo successo. Questi fattori includono quanto segue:

* Sostegno a livello esecutivo per la strategia globale. Vedere ["Stakeholder - coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication)
* Relazioni solide con i team tra cui Procurement, Finance, IT, fornitori. Vedere ["Stakeholder - coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication)
* Talento per identificare, implementare e gestire la tecnologia (in particolare il talento ingegneristico che risolverà i problemi nel modo adeguato).
* Business case valido per qualsiasi investimento tecnologico.

Le strategie tra le aziende possono essere simili, ma non esistono due strategie uguali: esistono differenze negli obiettivi strategici di business, nei livelli di maturità dell'organizzazione di globalizzazione, nella disponibilità di finanziamenti e risorse, nei principi di globalizzazione, così come in altre questioni specifiche della vostra organizzazione e azienda. Gli approcci che hanno un impatto sulla vostra strategia includono:

* Costruire vs comprare
* Resourcing in-house vs outsourcing
* Localizzazione centralizzata vs decentralizzata 

In genere una strategia tecnologica di globalizzazione è guidata da quattro obiettivi di business:

* Crescita globale
* Time-to-market più rapido
* Risparmio di costi ed efficienza
* Esperienza utente fantastica

### Creare e implementare la vostra strategia tecnologica

La creazione e l'implementazione della vostra strategia tecnologica comporta diverse fasi cicliche, come illustrato nel diagramma di seguito, iniziando con "Dimostrare il valore" e procedendo attraverso le sette fasi di un ciclo che costruisce e rafforza la vostra strategia tecnologica. 

<img src="/media/Chapter%205_Create-Implement%20Technology%20Strategy.png" alt="Immagine creare-implementare la strategia tecnologica" width="700"/>

#### Dimostrare il valore

Il primo aspetto sul quale concentrarsi quando si definisce la propria strategia tecnologica di globalizzazione riguarda gli obiettivi di business della propria azienda. Dovete essere in grado di dimostrare il contributo della vostra strategia tecnologica al raggiungimento degli obiettivi. Dovrete mappare gli obiettivi per dimostrare il ROI e ottenere il supporto di cui avete bisogno. 

Inoltre, dovete dimostrare il valore degli investimenti che avete già eseguito. Dovete definire come la tecnologia ha un impatto sul business e come la vostra tecnologia porta valore al business. 

Gli esempi includono:

* Risparmio sui costi, o meglio ancora, scalabilità dei costi: come la vostra tecnologia vi permette di fare di più con le stesse risorse (più lingue, più contenuti originali tradotti, ecc.).
* Utilizzo di contenuti simili tradotti in precedenza dalla memoria di traduzione ("TM"): come si guadagna non solo dal risparmio sui costi, ma dalla coerenza che la TM porta tra i tipi di contenuto.
* Soddisfazione del cliente: come l'applicazione della traduzione automatica ("MT") non modificata quando nessuna traduzione sarebbe altrimenti disponibile soddisfa le esigenze del cliente.
* Entrate globali: come rendere disponibile una lingua permette la crescita delle entrate in nuovi mercati. 

Avrete anche bisogno di un campione a livello dirigenziale, come menzionato nel capitolo ["Stakeholder - coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication)

#### Mappatura degli obiettivi aziendali agli strumenti

Una volta che avete chiarezza sugli obiettivi di business della vostra azienda e su come la vostra strategia tecnologica vi contribuisce, pensate alla visione e agli obiettivi del vostro Globalization Team. La tecnologia è un investimento significativo, quindi la vostra pianificazione deve essere a lungo termine. 

I fattori da considerare sono:

* Dove volete che arrivi la vostra tecnologia di localizzazione tra tre o cinque anni? 
* Il contenuto e i formati sorgente (piattaforme mobili, contenuti rich media) sono in continua evoluzione e la vostra tecnologia deve essere sufficientemente flessibile da supportare questi cambiamenti.
* La vostra tecnologia vi permette di integrarsi con altre tecnologie e formati di input/output?
* La localizzazione è centralizzata o decentralizzata nella vostra azienda? È più facile sviluppare una strategia per una funzione di localizzazione centralizzata. Anche se è più impegnativo per una funzione decentralizzata, vale ancora la pena considerare la tecnologia di localizzazione centralizzata.
* Quali risorse di gestione della tecnologia, se ce ne sono, sono in-house e quali sono in outsourcing? Chi si occuperà della gestione e della guida delle tecnologie?
* Lavorerete con più di un fornitore di traduzioni? C'è la possibilità di un cambiamento in futuro?
* Ragionate sul lungo termine. Come potete lavorare per costruire la tecnologia di localizzazione come una piattaforma profondamente integrata, piuttosto che un insieme di strumenti disparati? Come potete sfruttare le nuove tendenze tecnologiche come l'intelligenza artificiale (IA) e l'apprendimento automatico (ML)?

Dovrete valutare quali strumenti contribuiranno a o guideranno specifici obiettivi di business. La seguente matrice vi aiuterà a determinare quanto indicato.

![Immagine di mappatura degli obiettivi di business](/media/Chapter_5_Business_Objectives_Mapping.png)

Vedere l'Appendice A: ["Fattori che influenzano le decisioni tecnologiche e obiettivi strategici"](#appendix-a-technology-decision-drivers-and-strategic-objectives) per una descrizione dettagliata di queste tecnologie.

La mappatura degli obiettivi di business alla tecnologia con complessità e integrazione crescenti può essere descritta in quello che si potrebbe chiamare un modello di maturità tecnologica. Il diagramma di seguito mostra i pilastri o le fasi di maturità tecnologica. 


#### Modello di maturità tecnologica

![Immagine del modello di maturità tecnologica](/media/Chapter%205_Technology%20Maturity.JPG)

#### Capire a che punto siete nel modello di maturità tecnologica

Siate realistici su dove siete e dove potete arrivare; non è realistico passare da principiante ad esperto in un anno. Allo stesso tempo, il vostro avanzamento tramite il modello potrebbe non essere del tutto lineare ed è giusto così.

Capire dove vi trovate sul modello di maturità tecnologica richiede di fare un passo indietro e catalogare i vostri strumenti, quindi catalogare separatamente i vostri obiettivi chiave e le esigenze tecnologiche. Infine confrontate i due per capire dove avete lacune. Lo stato finale ideale dipenderà dai vostri bisogni e dalle vostre esigenze specifiche. Avrete bisogno di strumenti di internazionalizzazione? La coerenza della terminologia è importante nel vostro caso d'uso? 

Usando il modello fornito, strutturate la vostra visione dello stato finale ideale, non importa quanto irraggiungibile possa sembrare all'inizio. In base alla portata e alla scala della vostra organizzazione, prendete in considerazione la tecnologia di analisi che vi permetterà di aiutare a prendere decisioni che sono influenzate o supportate dai dati dei clienti e del business. Una volta che avete tutti questi componenti, potete capire dove vi trovate da un punto di vista di maturità tecnologica e usarlo come un punto di conversazione mentre negoziate per il prossimo lavoro. 

Anche la cultura aziendale gioca un ruolo importante. Se la vostra azienda dà un elevato valore all'innovazione, potreste essere in grado di fare investimenti più aggressivi nella tecnologia.

Il solo possesso degli strumenti non è indice di piena maturità; il livello di interoperabilità e/o integrazione tra gli strumenti è un fattore chiave. Probabilmente dovrete trovare il giusto equilibrio tra l'automazione perfetta e il funzionamento dell'80% delle volte. 

Gli aspetti da considerare sono i seguenti:


* Un'integrazione migliore consente di migliorare l'acquisizione dei dati, la tracciabilità e l'efficienza, mantenendo un ambiente coerente. Ad esempio, accedere a uno strumento termbase per aggiornare i termini è meno efficiente che gestirlo all'interno del TMS.

* Molti TMS dispongono di API (Application Programming Interfaces) per l'integrazione degli strumenti e alcuni hanno stretto partnership con altri fornitori di strumenti che offrono funzionalità complementari come la gestione dei termini, la valutazione della qualità e la traduzione automatica.

* L'integrazione può richiedere l'impiego di un gestore middleware che aiuti a integrare più tecnologie originarie con il vostro TMS e altre tecnologie secondarie. 


#### Identificare quale tecnologia adottare 

Non tutte le aziende o i team hanno bisogno di tutte le tecnologie elencate, né tutte le aziende saranno in grado di implementare tutte le tecnologie necessarie in una sola volta. Per decidere di quale tecnologia avete bisogno è necessario fare un inventario degli imperativi aziendali e del vostro atto costitutivo.  

Quindi chiedetevi: quali sono i vostri punti deboli che la tecnologia può risolvere? Cosa vi impedisce di realizzare il vostro atto costitutivo? Di quale tecnologia avete bisogno per ottenere successo più rapidamente? Quale di queste ha più priorità? Per cosa avete budget? Come potete condividere l'onere dell'investimento o del budget con gli altri stakeholder? Che cosa si può ottenere da un LSP (fornitore di servizi di localizzazione) che non conviene possedere e gestire internamente? L'utilizzo della tecnologia LSP può fornire una soluzione a breve termine, ma occorre assicurarsi che la soluzione si inserisca nell'ecosistema tecnologico complessivo e che si disponga di una strategia di uscita. 

Create una roadmap tecnologica. Iniziate dalla tecnologia più critica e pensate a come integrarla nel vostro ecosistema e nei vostri processi in corso. Affrontate prima le esigenze più critiche, nel rispetto dei vincoli di budget e risorse. Monitorate le tendenze tecnologiche e siate pronti a rivedere la vostra strategia in futuro se dovessero apparire innovazioni importanti, soprattutto in relazione all'IA e all'ML. 

#### Creare un business case e ottenere il consenso all'acquisto

Una volta stabilita la tecnologia che supporta il vostro obiettivo di business, dovete giustificare la spesa per assicurarvi il budget. Come si definisce il ritorno sull'investimento (ROI)? Prevedete di compensare l'investimento con un risparmio o una riduzione dei costi? Quali altre considerazioni non finanziarie si applicano, ad esempio l'eliminazione di attività soggette a errori, l'ottimizzazione dell'utilizzo delle risorse o la riduzione di potenziali difetti? 

Chiedete a un fornitore di tecnologia di aiutarvi a costruire il vostro ROI. Molti fornitori dispongono di calcolatori di ROI. Il grafico seguente mostra le fasi tipiche della creazione di un business case. 

<img src="/media/Chapter%205_Build%20business%20case%20process.png" alt="Immagine della creazione del processo del business case" width="850"/>

Cominciate ad ampliare la vostra visione. Il Globalization Team sarà l'unico utilizzatore della tecnologia? In caso contrario, quale sarà l'impatto della tecnologia sugli altri team? 

Quando si crea un business case per una soluzione terminologica, non bisogna dimenticare gli sviluppatori e gli scrittori il cui aiuto è necessario per definire i nuovi termini. La tecnologia aiuterà il team User Experience a essere più coerente con la terminologia di più prodotti? Consultate il capitolo ["Stakeholder - coinvolgimento e comunicazione strategici"](#chapter-3-stakeholdersstrategic-engagement-and-communication) per assicurarvi che non manchi nessuno. 

L'identificazione di questi reparti o individui è fondamentale per il vostro successo. Anche se la funzione di localizzazione è centralizzata nella vostra azienda, lavorate in sinergia con altri team per costruire collettivamente la strategia tecnologica, mettere in comune i fondi ed elaborare un approccio comune. Ad esempio, mentre la funzione di localizzazione dei prodotti è spesso centralizzata, i Marketing Team sono spesso indipendenti e hanno la libertà di impostare i propri processi e strumenti (vedere la storia di Diana riportata in precedenza). Un sistema di questo tipo può creare una duplicazione degli sforzi e uno spreco di risorse per l'impresa. 

Pensate a chi beneficerebbe maggiormente dello stack tecnologico, a chi sarebbe il vostro più probabile alleato nella creazione del business case e a quale reparto finanzierà l'investimento dal budget aziendale tramite l'IT, il reparto Localization, Marketing o tutti questi? Coinvolgete questi dipartimenti e individui fin dall'inizio e cercate di ottenere un campione o, meglio ancora, uno sponsor.

Come per ogni business case, iniziate a valutare la situazione attuale e a stilare un elenco di tutte le lacune riscontrate, sia materiali che immateriali. Qual è l'impatto di non avere alcuni o tutti gli strumenti più importanti elencati nel modello di maturità tecnologica? 

L'impatto varia in base alla configurazione dell'azienda, ma strumenti di base come un TMS sono essenziali. In caso di mancanza di automazione, sarebbe necessario assumere altre risorse? I compensi del vostro LSP per la gestione del lavoro aggiuntivo aumenterebbero? Spiegate come la tecnologia aiuterà a colmare le lacune individuate. Ad esempio, un Translation Management System aiuterebbe a ridurre la spesa consentendo il riutilizzo, la traduzione automatica taglierebbe i costi di traduzione e una suite di gestione dei programmi ridurrebbe i costi generali dei project manager grazie all'aumento dell'efficienza. 

Date un prezzo a tutti questi vantaggi. Alcuni, come quelli elencati sopra, sono facili da calcolare. Altri, come le mancate entrate o il danno al marchio, sono molto più difficili da valutare. Una volta stabilito l'ammontare del risparmio, è necessario analizzare i costi della soluzione. Ci sono alcuni aspetti da considerare:

* Dovete costruire la vostra soluzione o acquistare uno strumento già pronto?
* Considerate le offerte disponibili sul mercato. Alcune delle tecnologie di localizzazione più complesse e importanti, come i TMS e la traduzione automatica, sono in uso da almeno un decennio ed esistono offerte ben sviluppate in questi campi. Gli acquirenti hanno una varietà di strumenti tra cui scegliere per numerosi casi d'uso e requisiti diversi. Altri prodotti, come gli strumenti di gestione dei costi o di internazionalizzazione, hanno un'offerta limitata e possono o meno soddisfare le esigenze specifiche dell'acquirente. 
* Qual è la cultura dell'azienda a questo proposito? Lavorate in un'azienda che dispone di risorse ingegneristiche e che ama costruire le proprie soluzioni o che in genere acquista soluzioni standard? Spesso le aziende scelgono di acquistare soluzioni già disponibili sul mercato e di concentrare le risorse interne sulle attività di integrazione. Tuttavia, se le soluzioni esistenti non sono all'altezza delle vostre specifiche in termini di funzionalità o non sono sufficientemente innovative, potreste decidere di sviluppare la vostra tecnologia indipendentemente dalle offerte del mercato.
* Calcolare i costi di manutenzione per entrambi gli scenari. Ricordate che lo sviluppo di uno strumento interno rappresenta un investimento ingegneristico: il prodotto richiederà la presenza di un manager, dovrà essere aggiornato regolarmente, potrebbe essere necessario aggiungere e testare nuove funzionalità da parte degli ingegneri per supportare le esigenze di un'azienda in crescita, e così via. 
* Considerate i potenziali costi di personalizzazione e le risorse necessarie. Acquistate un sistema a scatola chiusa e costruite i componenti che si integrano tra loro? Il sistema è aperto con supporto API e un SDK (kit di sviluppo software)? Quali competenze di programmazione sono necessarie? Anche con un TMS maturo, potreste trovarvi di fronte a estensioni che non sono disponibili e ciò richiede una certa personalizzazione. 
* Consultate l'IT in merito ai requisiti di sicurezza per le vostre soluzioni e assicuratevi di includere questo punto nella RFP (richiesta di offerta) per i fornitori di tecnologia.
* Dovete possedere la tecnologia o farla gestire al vostro LSP? Molti LSP hanno sviluppato i propri strumenti di localizzazione, tra cui Translation Management System, e consentono ai clienti di caricare manualmente i file e di connettersi al CMS del cliente, nonché di monitorare l'avanzamento della traduzione. 

    È importante considerare la vostra strategia complessiva di LSP quando si effettua questa determinazione. Questa soluzione può funzionare bene quando si utilizza un singolo LSP per tutte le esigenze di traduzione. Tuttavia, questa strategia potrebbe diventare piuttosto macchinosa quando si utilizzano più LSP per la traduzione di prodotti diversi o per incarichi di traduzione e revisione. 

    Inoltre, l'utilizzo di un LSP sia per le traduzioni che per le esigenze tecnologiche vi toglie il controllo e indebolisce la vostra proposta di gestione del rischio: cosa succede se perdete la fiducia nell'LSP o se quest'ultimo aumenta in modo significativo i prezzi? 

* Se state acquistando un prodotto, dovreste scegliere una soluzione on-premise o una soluzione hosted? Dovreste scegliere un modello di licenza tradizionale o un abbonamento?

    Per alcuni, questo potrebbe anche non essere un elemento da prendere in considerazione, in quanto la cultura aziendale e il team di sicurezza informatica potrebbero prendere questa decisione. Tuttavia, è importante tenere a mente alcuni concetti quando si risponde a questa domanda:

  * La soluzione in hosting consentirà un'integrazione con altri sistemi, come CMS, MT, approvvigionamento o un sistema middleware che colleghi tutti questi sistemi? Considerate la protezione e la sicurezza dei dati, soprattutto se chiedete al vostro fornitore di tecnologia di ospitare un ambiente che volete collegare ai repository di codice sorgente. 

    L'ambiente ospitato dal fornitore potrebbe non essere in grado di connettersi direttamente con repository di codice sorgente che hanno autorizzazioni di accesso molto limitate. Coinvolgete i vostri stakeholder di IT e Data Security fin dalle prime fasi del processo decisionale.

  * Avete esigenze di personalizzazione per questa tecnologia? Se sì, la soluzione in hosting lo consente?
  * Se optate per una soluzione on-premise, considerate i costi dell'hardware, del supporto informatico e applicativo interno, della manutenzione e degli aggiornamenti, che in genere sono inclusi nel costo dell'abbonamento e dell'hosting in un ambiente ospitato da un fornitore. 
* Considerate le vostre esigenze future. Potrebbe essere difficile prevedere quali saranno le vostre esigenze a lungo termine, ma non dimenticate la scalabilità. Rivedete la vostra strategia linguistica (vedere il capitolo ["Strategia linguistica"](#chapter-4-language-strategy)). L'azienda ha in programma di espandersi in altri mercati e quindi sarà necessario aggiungere il supporto per più lingue e più utenti? La vostra azienda è attiva nel campo delle acquisizioni e quindi dovrete potenzialmente supportare ulteriori integrazioni di CMS? Assicuratevi che la tecnologia sia in grado di sostenere la vostra crescita potenziale almeno per diversi anni. 

    Tenete presente che alcuni strumenti, come un Translation Management System, sono difficili da migrare, come già detto, e possono anche richiedere costi maggiori. Ad esempio, i costi di spostamento possono essere significativi quando un nuovo TMS segmenta i contenuti sorgente in modo diverso, con conseguente riduzione delle corrispondenze In-Context-Exact (ICE) e del 100%. Pertanto, l'acquisto di un TMS rappresenta un investimento per il futuro.

* Considerate il modo in cui impiegherete le risorse per la vostra strategia tecnologica. Sia che abbiate deciso di implementare una tecnologia come soluzione on-premise, di utilizzare una configurazione cloud di un fornitore di tecnologia o di affidarvi al vostro LSP, pensate alle risorse interne che devono supportare la vostra strategia in futuro, sia tecniche che operative. 

    Le risorse tecnologiche possono avere diverse varianti, da un ruolo puramente strategico, che consiste nel tenersi aggiornati sulle tendenze del settore e nell'assicurarsi che il fornitore utilizzi le tecnologie più recenti, a un ruolo di Chief Architect, che mette a punto un piano di integrazione e personalizzazione, fino alle risorse ingegneristiche vere e proprie, che costruiscono le soluzioni, sviluppano le integrazioni e le personalizzazioni, si occupano dell'implementazione e delle attività di manutenzione come descritto in precedenza. 

    Oltre alle risorse tecniche vere e proprie, assicuratevi che siano presenti anche le risorse operative. Ad esempio, prima ancora di implementare una soluzione terminologica, potreste dover assumere un terminologo, che centralizzi tutto il lavoro terminologico per i termini sorgente e target e che, una volta acquisita una tecnologia, si occupi di implementarla e di assicurarsi che il sistema venga utilizzato come progettato. Per maggiori informazioni sul resourcing della vostra strategia tecnologica, consultate la sezione ["Evoluzione tecnologica"](#technology-evolution).


#### Implementare la soluzione

Quando si tratta di scegliere e implementare la tecnologia giusta, i requisiti dettagliati sono fondamentali. È proprio come quando si acquista un'auto: non entrate in un concessionario a caso, dicendo che volete un'auto e prendendo quella mostrata per prima. Vi presentate in negozio dopo aver fatto delle ricerche, sapete quali caratteristiche sono importanti per voi, quali sono indispensabili e di quali potete fare a meno. Avete un'idea di quanto volete pagare e di quanto margine avete prima di andarvene. 

La scelta della tecnologia da implementare va più o meno nello stesso modo, con la differenza che l'elenco dei requisiti sarà più lungo, ci sarà disaccordo su quali siano le caratteristiche indispensabili rispetto a quelle piacevoli da avere e non saranno il portafoglio o il rapporto di credito a determinare l'acquisto, ma un percorso più contorto che coinvolge gli appalti.

Quindi, vi starete chiedendo, devo iniziare a elaborare una lista? Forse, ma le risorse sono disponibili. Potete contattare i colleghi che hanno già affrontato il processo e che potrebbero essere disposti a condividere le loro esperienze. Potete anche rivolgervi agli analisti della globalizzazione e alle società di consulenza per ottenere report e ricerche sull'argomento o per effettuare la selezione delle tecnologie per vostro conto. 

Questi sono tutti buoni punti di partenza, ma dovrete comunque impegnarvi molto con il team. Le diverse parti del vostro team avranno prospettive diverse. Se utilizziamo un esempio di TMS, i PM si concentreranno sulle funzionalità che riducono il lavoro manuale di inserimento e disinserimento dei contenuti negli strumenti e di comprensione dello stato. Tuttavia, il vostro team di qualità sarà più interessato alla gestione delle query, al punteggio di qualità, ecc. Un team di internazionalizzazione si concentrerà sulle integrazioni con i repository di codice e sulla gestione dei file di risorse. Dovrete assicurarvi che tutte le voci siano ascoltate e considerate. 

Inoltre, dovrete comprendere le esigenze dei vostri stakeholder, in particolare se avete stakeholder in un modello self-service che interagiscono con il TMS. 

Spesso si trascurano i requisiti della vostra base di fornitori, ma sono essenziali per la decisione. I fornitori utilizzano la tecnologia più di chiunque altro nell'ecosistema, quindi saranno influenzati in modo significativo dalle decisioni che prenderete. I vostri fornitori hanno anche molta esperienza di lavoro con diverse tecnologie, alcuni possono anche fornire la tecnologia, quindi sono ben posizionati per agire come consulenti sui requisiti e le best practice.

Ora che avete preso una decisione tecnologica, è fatta, giusto? No, avete appena iniziato, ora dovete concentrarvi sull'implementazione, cioè sulla formazione delle risorse all'uso degli strumenti, sulla gestione delle modifiche, sull'integrazione con altre tecnologie e, probabilmente, sul reporting.

#### Creare report e monitorare i risultati

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Eva era piuttosto frustrata dai tempi di consegna di uno dei suoi fornitori. Anche dopo mesi di discussioni, non vedeva ancora un reale miglioramento. Lei e il suo analista hanno analizzato i dati, in particolare quelli relativi alle fasi del processo: quanto tempo impiegava il fornitore per tradurre i lavori, per fare il DTP, per autorizzare il lavoro, ecc. 
>
>Hanno scoperto che il fornitore aveva ottenuto buoni risultati in tutte le fasi tranne una, il DTP. Dati alla mano, Eva è tornata dal fornitore, che non aveva esaminato quella parte del processo, perché nemmeno lui aveva analizzato i dati. Nel giro di poche settimane, dopo aver modificato i processi, i tempi di consegna sono tornati a essere in linea con gli obiettivi. 
> 
> Anche se sembra scontato, spesso non facciamo un passo indietro e non guardiamo i dati dalla giusta prospettiva, ma facciamo ipotesi su quale possa essere il problema senza convalidarle con i dati. La tecnologia, in particolare la capacità di reporting e i dati acquisiti, hanno consentito a Eva di avere visibilità sul processo e comprensione delle prestazioni impreviste per poterle affrontare.

Sebbene vi sia la possibilità che disponiate di diverse metriche sui risultati del vostro lavoro, spesso dimentichiamo di misurare l'efficacia degli strumenti e dei processi che utilizziamo per raggiungere tali risultati. Occorre istituire metriche e strumentazioni per rilevare le prestazioni della tecnologia:

* Tempo di attività
* Reattività
* Tassi di errore (come i lavori che non hanno successo nel vostro sistema TMS)

Occorre che qualcuno si occupi di monitorare queste metriche e di analizzare le tendenze. Questo può essere il fornitore di strumenti, ma non tutti i fornitori ne dispongono, oppure non dispongono di dati relativi al cliente. Dovrete spingerli a renderlo disponibile e chiedere trasparenza. Vedere il capitolo ["Data Analytics per la strategia di globalizzazione".](#chapter-6-data-analytics-for-globalization-strategy)

### Evoluzione della tecnologia 

Avete appena messo tutto in funzione e integrato come avevate immaginato, ma non è ancora il momento di abbassare la guardia. Probabilmente la vostra tecnologia è già obsoleta o non è più adatta all'evoluzione della vostra organizzazione e/o azienda. La tecnologia richiede costantemente aggiornamenti o addirittura sostituzioni complete. 

È fondamentale restare aggiornati sull'evoluzione degli strumenti e della tecnologia sul mercato. Per questo è necessario essere al passo con i tempi:

* Abbonatevi alle newsletter e ai blog delle società di ricerca e di analisi 
* Consultate i siti Web di notizie sul settore
* Iscrivetevi a un forum nella vostra area di interesse
* Partecipate a conferenze di settore 
* Seguite i principali fornitori di tecnologia del settore
* Assicuratevi di parlare spesso di questo argomento con i fornitori

L'ideale sarebbe assegnare a qualcuno del vostro team il ruolo di tecnologo. Questo ruolo può essere assegnato a qualcuno nelle organizzazioni più grandi. Oppure, in un team di dimensioni ridotte, può essere parte del ruolo di qualcuno. O forse potreste essere voi a occuparvi di tale funzione, se siete in un'azienda più piccola. 

Le vostre tecnologie devono andare di pari passo con l'evoluzione dei requisiti. I cambiamenti del TMS possono avvenire ogni 5-15 anni, a seconda delle esigenze, della crescita, dei cambiamenti di strategia, ecc. Tuttavia, altre tecnologie del vostro stack possono cambiare più frequentemente. Non pensate mai di aver finito, ma piuttosto pensate di raggiungere un altopiano, fare un bel respiro e puntare alla prossima vetta.

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> La situazione di Diana è stata descritta per la prima volta [in questo capitolo](#chapter-5-technology-strategy). Non è riuscita a convincere un dirigente del reparto Marketing a utilizzare la sua tecnologia e l'azienda si è ritrovata con due soluzioni TMS. 
> 
> Dopo aver sfogato le sue frustrazioni, come ha agito la nostra amica Diana? La sua azienda aveva ora due diversi sistemi TMS: uno per la gestione dei contenuti di marketing e un altro per tutto il resto. 
>
>Ha deciso di utilizzare più tattiche. In primo luogo, ha elaborato la sua strategia coinvolgendo più stakeholder (nel suo caso i team Product, Marketing e Sales). Poi ha riflettuto su tutti i requisiti tecnologici ed è tornata sul mercato per ricercare e trovare sistemi TMS che si adattassero a tutte le esigenze degli stakeholder, compresi i revisori. Si è anche tenuta in contatto con il direttore marketing e ha appreso i problemi di implementazione del TMS e i problemi di qualità della traduzione. In sostanza, al Marketing Team non piaceva gestire il rapporto con il fornitore di localizzazione. 
>
> Una volta individuati alcuni buoni candidati TMS che rispondevano a questi requisiti, Diana ha lavorato a stretto contatto con gli stakeholder dei team Product, Sales, Marketing e Localization per scegliere un sistema che potesse soddisfare la maggior parte dei requisiti. 
>
>È stato piuttosto facile creare il business case, perché l'azienda avrebbe risparmiato denaro passando da due sistemi TMS a uno solo. Il ROI è stato evidente, anche se il cambiamento del sistema e l'implementazione hanno richiesto molto tempo. I revisori erano soddisfatti del nuovo sistema e il Marketing Team si è sentito sollevato nel riaffidare il processo al Globalization team. 

### Come incorporare diverse tecnologie nella vostra strategia

Molte tecnologie attuali ed emergenti porteranno il settore nella prossima era, tra cui l'IA/ML, la traduzione automatica adattiva e la RSI (Remote Simultaneous Interpretation), solo per citarne alcune. Queste tecnologie sono troppo complesse e si evolvono troppo rapidamente per essere trattate in modo esaustivo in questa sede, ma una rapida panoramica ne aumenterà la conoscenza. Voi o il vostro tecnologo dovreste osservare queste tecnologie in evoluzione e pensare a come possono contribuire a sostenere la strategia della vostra azienda. 

* **MT**. Sebbene la traduzione automatica sia abbastanza diffusa, le forme avanzate di traduzione automatica, come quella adattiva e multimodale, sono meno disponibili e più personalizzate. Possono richiedere la modifica dell'intero stack tecnologico e talvolta anche dei LSP, per trarne vantaggio. Una tale mossa può sembrare impensabile, ma alcune grandi aziende hanno fatto il salto e altre le seguiranno sicuramente. 
* **IA**. È da tempo che sentiamo parlare della promessa dell'IA e ogni giorno spuntano nuove applicazioni nel settore della localizzazione. La chiave per una soluzione IA adeguata sono i dati, tanti, puliti e accessibili. I requisiti dei dati frenano l'adozione più della tecnologia stessa. 

    Oggi l'IA si concentra sull'analisi del sorgente e sull'ottimizzazione dei processi di base, come l'RPA (automazione robotica dei processi). Tuttavia, domani scoprirete che l'IA si sta estendendo alle decisioni sulla qualità del sorgente e sul tipo di flusso di lavoro da utilizzare, ad esempio se applicare o meno la MT. Il sistema esaminerà quindi l'output e determinerà se è sufficientemente buono o se necessita di un post editing o di una revisione della qualità. Infine, tutti i dati vengono reinseriti nel modello per prendere decisioni migliori la volta successiva. 

* **Chat**. L'IA multilingue è una parte importante della globalizzazione. La comprensione del linguaggio naturale (NLU) e l'automazione guidata dall'IA sono a portata di mano. Le aziende possono disporre di agenti virtuali multilingue che automatizzano i processi e indirizzano le richieste verso conclusioni soddisfacenti o processi di assistenza umana. L'obiettivo è fornire un servizio self-service e ridurre la dipendenza dagli esseri umani per fornire assistenza ai clienti. 

    Il NLU consiste nel comprendere l'intento del richiedente e nel compiere i passi successivi sulla base di uno script definito. Gli ingegneri di NLU popolano il sistema con esempi di linguaggio naturale - le espressioni - in modo che il sistema sia in grado di comprendere i significati delle parole (intenti) e i contesti (entità). Sulla base di questa comprensione, deduce le azioni dell'utente o del sistema. 


    Gli agenti virtuali multilingue seguono lo stesso processo dell'inglese per ogni lingua. Se il vostro team si occupa dell'aspetto NLU della globalizzazione, i ruoli, le competenze e i processi del team sono molto diversi da quelli del tradizionale charter di traduzione. 

* **RSI.** La pandemia di COVID-19 ha portato con sé, tra le altre cose, un'impennata dell'automazione in materia di interpretazione a distanza, trascrizione automatica, text to speech, speech to text, ecc. Tutte queste tecnologie erano già disponibili prima della pandemia, ma l'adozione è stata lenta. Oggi ci sono innumerevoli aziende e offerte che hanno una soluzione per ogni aspetto delle esigenze remote. 

Molte grandi aziende nominano un architetto della globalizzazione per guidare la visione e l'implementazione dello stack tecnologico della globalizzazione. Ciò contribuisce a garantire l'allineamento di tutti gli stakeholder.

### Concetti chiave

Se state iniziando il vostro viaggio nella tecnologia di localizzazione o state pensando di apportare modifiche a una configurazione esistente, assicuratevi di prendere in considerazione i seguenti approcci descritti in questo capitolo: 

* Coinvolgete gli stakeholder fin dalle prime fasi. Sincronizzatevi con gli stakeholder che interagiscono con la tecnologia e coinvolgeteli regolarmente.
* Dimostrate il valore della tecnologia creando un solido business case. Includete i dati sui risparmi nei report periodici per illustrare non solo il ritorno economico, ma anche l'efficienza operativa. Includete i costi di manutenzione.
* Creare una roadmap tecnologica basata sulla visione e la strategia della vostra azienda. 
* Pensate a come la tecnologia si integra nello stack, evitate applicazioni standalone che richiedono lavoro manuale. 
* Acquistate ciò che potete e concentrate le risorse interne sull'integrazione.
* Ove possibile, integrate la tecnologia in linea con gli standard del settore. L'integrazione e il porting della tecnologia saranno più agevoli. 
* Date priorità agli strumenti. Non cercate di fare tutto e subito.
* Prima i dati. In futuro i dati saranno alla base dell'automazione e dell'IA. Assicuratevi di includere la strategia di analisi di business nella vostra roadmap tecnologica.
* Affidatevi a ricerche di settore e parlate con i vostri colleghi.
* Mantenete i processi semplici e la personalizzazione al minimo.
* Assicuratevi che i componenti di diversi fornitori e integrazioni possano essere sostituiti senza dover dipendere in modo significativo da un unico fornitore.
* Siate consapevoli del rischio quando utilizzate un LSP per i servizi di traduzione e la tecnologia.

**Note:**

Riconosciamo che alcuni degli incarichi menzionati possono essere gestiti con tecnologie di livello inferiore, come fogli di calcolo ed e-mail. Tuttavia, ai fini del presente documento, tali soluzioni low-tech non sono considerate una "tecnologia" secondo la definizione del capitolo in oggetto. Ai fini di tale guida, la tecnologia è definita come una soluzione tecnica designata, dotata di funzionalità integrate per rispondere a un'esigenza specifica. 

Alcuni degli strumenti descritti possono essere parte o collegati a un TMS, a seconda della tecnologia.


## Capitolo 6: Data Analytics per la strategia di globalizzazione

"Se non si può misurare, non si può migliorare."

_-Peter Drucker_

Tutti sanno che servono dati per prendere decisioni. È come dire: ho bisogno di cibo per sopravvivere. Ma quali dati? Mentre passiamo in rassegna i nostri metodi preferiti per selezionare i dati importanti per le nostre aziende, troverete alcuni suggerimenti pertinenti e altri non pertinenti. Quando si pensa ai propri dati strategici, l'unica regola universale è sapere perché i dati selezionati sono significativi, in che modo influiscono sulle proprie azioni e raccomandazioni e cosa ci fa essere certi di poterci fidare. 

In qualità di globalization leader, avete il ruolo di creare una visione e una storia stimolanti per allineare tutti gli stakeholder intorno a un insieme comune di obiettivi e traguardi. I dati giocano un ruolo fondamentale nella definizione di questa strategia di globalizzazione. Evidenzierà le attuali lacune e opportunità. Aiuterà il vostro programma di globalizzazione a rimanere in carreggiata e a raggiungere gli obiettivi dell'organizzazione.

Inutile dire che i dati sono un aspetto fondamentale per la gestione di qualsiasi azienda. Negli ultimi anni, la richiesta di data scientist ed analisti ha subito un'impennata. Naturalmente, la stessa esigenza si applica alla globalizzazione, come dimostra la creazione di posizioni dedicate all'ingegneria dei dati e agli analisti della globalizzazione nelle aziende globali. Questi ruoli sono responsabili dello sviluppo di un'infrastruttura di dati sulla globalizzazione da cui estrarre informazioni chiave.

In questo capitolo affronteremo come pensare ai dati sulla globalizzazione in modo strategico:

* Perché i KPI selezionati sono importanti per le vostre decisioni e perché potete fidarvi dei dati
* Come il vostro lavoro si inserisce nell'attività dell'azienda e come utilizzare i dati per dimostrare il vostro contributo
* Come tenere traccia di tutto ciò di cui dovete essere consapevoli e preparati. 


### Strategia dei dati di globalizzazione

In qualità di globalization leader, vi affidate a dati essenziali per definire e monitorare la vostra strategia di globalizzazione. Dovete comprendere la natura dei dati e il loro ciclo di vita. Dovete inoltre essere selettivi e critici nei confronti di questi dati. Quando analizzate i dati, ponetevi le seguenti domande: cosa rappresentano veramente i dati? I dati hanno senso? Qual è il valore atteso? È in linea con i benchmark del settore?

Non limitatevi ai dati quantitativi. Sia i dati qualitativi che quelli quantitativi sono fondamentali e devono essere allineati per sviluppare una solida strategia di globalizzazione. Se i dati quantitativi mostrano un comportamento inaspettato degli utenti, contattate gli utenti reali (eventualmente tramite un sondaggio) o i vostri uffici internazionali per confermare la giusta interpretazione dei dati.

I dati sulla localizzazione sono molto vasti e riguardano clienti, mercati, finanza, qualità, efficienza operativa, assistenza e altre metriche fondamentali per l'azienda. Pertanto, i dati devono essere classificati in base alla criticità e agli sforzi per raccoglierli. I dati devono essere significativi, non solo disponibili. 

Si consiglia di iniziare a costruire partendo da un insieme di dati di piccole dimensioni. Si noti che i punti dati critici per alcune aziende possono non essere altrettanto rilevanti per altre. Ad esempio, un'azienda di e-commerce può fare molto più affidamento sulle analisi web rispetto a un'azienda che fornisce principalmente materiale di marketing, documentazione e supporto sul proprio sito aziendale.

Esistono anche diversi livelli di granularità dei dati, tra cui le prestazioni aziendali, regionali, di prodotto, ecc. La valutazione di questi punti dati porterà a priorità e focus diversi, ma tutti contribuiranno al fatturato e alla quota di mercato dell'azienda. È probabile che la prestazione del Paese sia più rilevante per le metriche di globalizzazione. 

Quando un'azienda entra in un mercato, ha delle aspettative di guadagno che giustificano l'investimento. Se le aspettative non vengono soddisfatte, la dirigenza aziendale potrebbe concludere che la prestazione non è stata soddisfacente. La raccolta dei dati relativi alle prestazioni aiuterà a capire il motivo di eventuali discrepanze tra le previsioni e le prestazioni effettive. È possibile che le metriche utilizzate nelle proiezioni non corrispondano alla realtà: non ci sono abbastanza clienti nel Paese, non sono stati venduti abbastanza prodotti, i punteggi di soddisfazione del cliente (CSAT) sono pessimi, la quota di mercato è inferiore alle aspettative, i tassi di adozione sono bassi, i tassi di rinnovo sono bassi, le metriche non sono adatte allo scopo, ecc. 

Anche le metriche di localizzazione come l'uso della lingua dovrebbero essere tracciate e analizzate in modo da poter influenzare le prestazioni. Ad esempio, se si conclude che il tasso di adozione del prodotto è basso perché le traduzioni sono scadenti, la strategia sarebbe quella di migliorare le traduzioni. Una migliore qualità delle traduzioni accelererà il tasso di adozione che, a sua volta, aumenterà la quota di mercato e le vendite dei prodotti e si rifletterà sui ricavi dell'azienda nel Paese. 

Trovate i dati che tracciano lo stato di ogni fase e potrete eventualmente calcolare il contributo diretto alle entrate. La sfida principale, tuttavia, è dimostrare che le traduzioni sono effettivamente migliorate: come si fa a saperlo? Il modo migliore per scoprirlo è lavorare direttamente con i team locali e ottenere il supporto degli stakeholder strategici. In molti casi di attribuzione della globalizzazione, è impossibile calcolare il contributo diretto. Se i vostri stakeholder sostengono i vostri metodi di misurazione dei progressi, vi daranno credito nei loro dati per aver moltiplicato il loro successo.  

In qualità di globalization leader, vi troverete spesso, se non sempre, ad affrontare la sfida di dover prendere decisioni critiche sulla base di dati incompleti o imprecisi. Per colmare questa lacuna, osservate le tendenze, usate il vostro miglior giudizio, fate ipotesi ragionevoli, seguite i risultati e, se necessario, cambiate rotta.

Infine, per prendere decisioni informate occorre mettere insieme più punti dati. Basarsi su un singolo punto dati non racconta l'intera storia. Se il tasso di adozione del prodotto in una lingua è inferiore alle aspettative, smettete di fornire il vostro prodotto in quella lingua? Se i visitatori del sito Web non scaricano i materiali di marketing tradotti, la colpa è della loro conoscenza dell'inglese o dell'incapacità di trovare la versione localizzata? Come si fa a conoscere il vero motivo e a prendere decisioni? 

Fate un'ipotesi e confermate le vostre conclusioni. Utilizzate più punti dati, riconoscete le tendenze, parlate con gli utenti finali e i team locali per corroborare le vostre ipotesi, prendete decisioni strategiche e convalidatele con i leader strategici dell'azienda (aziendali e locali). Ricordate che non siete soli. La strategia è uno sport di squadra.

### Considerazioni chiave

Ci sono diversi aspetti da considerare quando si costruisce la propria strategia di globalizzazione dei dati; alcuni di questi sono descritti in dettaglio nel presente documento:

* **Definizione delle priorità dei dati:** ci sono vari punti dati che potrebbero essere monitorati, ma in ultima analisi è necessario stabilire quali sono i più critici per la vostra organizzazione. Ponetevi le seguenti domande:
    * Perché i dati sono fondamentali per la globalizzazione?
    * Come scegliere i giusti dati sulla globalizzazione e la relativa granularità? Come convalida la vostra strategia? 
    * Che storia raccontano i dati e come informano le vostre decisioni, voce per voce?
* **Raccolta dei dati:** una volta identificati i dati chiave, è necessario raccoglierli con cadenza regolare e su larga scala. Ad esempio:
    * Qual è il processo per raccogliere i dati ed elaborare report e dashboard?
    * Quali sono gli strumenti necessari per raccogliere, trasformare ed elaborare i dati?
    * Dove si trovano i dati e con chi si può collaborare per raccoglierli automaticamente?
* **Presentazione dei dati:** infine, occorre presentare i dati ai dirigenti e agli altri leader. Considerate i seguenti punti:
    * Quali dati sono convincenti per le altre unità aziendali quando si espongono i contributi commerciali degli sforzi di globalizzazione nella vostra azienda? 
    * Qual è la vostra strategia di globalizzazione dei dati? A chi lo comunicate e come? Qual è il vostro elevator pitch sul valore della globalizzazione? Come fate a sapere se siete riusciti a comunicarlo con successo, soprattutto al livello C? Quali sono i risultati previsti? 

In definitiva, nell'ambito della vostra strategia di globalizzazione dei dati, il vostro desiderio sarà sviluppare un circolo virtuoso con le seguenti fasi:

1. Scegliere i dati rilevanti
2. Raccogliere i dati
3. Identificare le informazioni chiave
4. Prendere decisioni
5. Intraprendere azioni
6. Misurare l'impatto
7. ... E ricominciare da capo

![Immagine del cerchio di dati](/media/Chapter%206_Data%20Circle.jpg)

### Report e dashboard strategici

Un modo per conquistare i fan e costruire efficaci team strategici interfunzionali di sostenitori e sostenitrici è rappresentato da report e dashboard. Il loro scopo è essere utili. Non belli o pieni, ma semplicemente utili.

I report utili si concentrano su uno scopo e hanno metriche che tracciano i progressi verso un obiettivo che si ritiene possa avere un impatto migliore sull'azienda (vedere l'[illustrazione del dashboard tattico](#tactical) qui di seguito). 

I dashboard utili devono essere guidati da informazioni chiave reali che spingano ad azioni reali, in modo da ottenere e realizzare un impatto reale sull'azienda. Un dashboard ha l'obiettivo principale di presentare tendenze e raccomandazioni attuabili. I dashboard sono brevi visualizzazioni di una sola pagina delle informazioni più importanti per comprendere a colpo d'occhio lo stato dell'azienda (vedere l'[illustrazione del dashboard strategico](#strategic) di seguito).

Idealmente, un dashboard utile di globalizzazione strategica mostra le tendenze e le informazioni chiave principali, le raccomandazioni e l'impatto sul business. Presenta una visione end-to-end del successo: l'acquisizione di clienti (internazionali), il loro comportamento quando utilizzano il vostro prodotto e il valore commerciale di tale comportamento (ovvero le entrate). 

Ad esempio, se state cercando di ottenere maggiori entrate dai mercati francofoni, il vostro approccio strategico potrebbe essere quello di migliorare l'esperienza utente per il pubblico francofono. Creereste un dashboard strategico che fornisce una visione completa delle prestazioni del mercato francese e dell'impatto aziendale del vostro programma. Potrebbe avere le seguenti metriche che indicano miglioramenti nell'esperienza utente per il vostro pubblico target:

* Crescita degli utenti francofoni mese su mese (acquisizione)
* Tasso di adozione degli utenti francesi rispetto al tasso di adozione degli utenti inglesi in un periodo di sei mesi (comportamento)
* Aumento/diminuzione mese dopo mese del fatturato dei mercati francofoni (impatto commerciale)
* Feedback sulla qualità del francese per le vostre pagine di documentazione

Le raccomandazioni e l'analisi riguardano le azioni che l'azienda deve intraprendere per raggiungere l'obiettivo nel modo più rapido ed efficiente, migliorando l'intera attività, non solo una parte di essa. Le informazioni chiave potrebbero includere suggerimenti su quali programmi interrompere, continuare o concentrarsi nel contesto della strategia aziendale complessiva. Le osservazioni potrebbero identificare lacune e disallineamenti e raccomandare nuove tattiche per ottenere risultati più favorevoli.

A volte, l'assenza di qualcosa può indicare un processo interrotto. Come nella storia di Diana (vedere il capitolo ["Panoramica sulla strategia"](#chapter-2-strategy-overview), l'assenza di ticket dei clienti non significa che il prodotto sia perfetto. Il numero di ticket aperti potrebbe essere basso a causa della disponibilità della funzionalità solo in lingua inglese,che i vostri clienti non conoscono. In questo caso, se si risolve il problema traducendo l'interfaccia utente e rendendola così utilizzabile per il pubblico francese, ci si aspetta un aumento del numero di ticket in francese. Sebbene l'aumento del numero di ticket in francese sia un dato positivo, la raccomandazione potrebbe essere quella di potenziare il personale del team di assistenza clienti francese per gestire l'aumento del volume. 

Quando si dice "conoscere il proprio pubblico", si intende sapere cosa gli interessa. Le vostre osservazioni e raccomandazioni, supportate da dati, devono riflettere il livello appropriato del pubblico. 

I dirigenti di livello CEO sono interessati a metriche e informazioni chiave aziendali di alto livello. Cercano team interfunzionali per gestire un programma che influisce direttamente sui profitti dell'azienda. Per questo motivo, i dashboard strategici sono i più adatti per loro. 

Gli imprenditori rispondono alle raccomandazioni e alle azioni che li aiutano a ottenere risultati migliori. I dashboard tattici sono più utili per loro, perché si concentrano sull'esecuzione. 

Un esempio di dashboard tattico finalizzato a un obiettivo è il miglioramento del tasso di adozione.

<a name="tactical"></a><img src="/media/Chapter%206_Tactical%20Dashboard.png" alt="Immagine del dashboard tattico" width="650"/>  

Un dashboard strategico utilizza diverse metriche e illustra uno stato completo, end-to-end, dell'azienda. Include una panoramica, analisi, raccomandazioni e impatto aziendale delle prestazioni. 

Esempio di un dashboard strategico:

<a name="strategic"></a><img src="/media/Chapter%206_Strategic%20Dashboard.png" alt="Immagine del dashboard strategico" width="650"/>  

### Comprendere i dati

Prima di usare i dati, dobbiamo capire e chiarire le nostre ipotesi e segnalare i limiti dei dati. Ecco alcuni suggerimenti:

* Categorizzate i dati con cataloghi adeguati.
* Pulite i dati raccolti. Escludete alcuni valori anomali o metriche irrilevanti, per garantire un'elevata qualità dei dati. Trattate con sensibilità i dati riservati dei clienti. Rimuoveteli dai vostri report per proteggere la privacy dei clienti. 
* Comprendete il ciclo di vita dei dati.
* Evitate di considerare solo un'unica fonte di dati. È sempre bene collegare tra loro diversi tipi di dati, per evitare errori. 
* Costruite una base cronologica e cercate le tendenze utilizzando lo stesso processo di raccolta dei dati.

Questa è una panoramica dei diversi tipi di dati disponibili:

<img src="/media/Chapter%206_Types%20of%20Data.png" alt="Immagine dei tipi di dati" width="750"/>  


#### Dati incompleti

In molte aziende gli insiemi di dati sono incompleti. Le ragioni per cui ciò accade sono molteplici. GDPR, DPA, PIPL, LGPD, PDPA e altre leggi sulla protezione dei dati in tutto il mondo limitano le possibilità delle aziende di memorizzare e utilizzare i dati. Alcune aziende consentono ai clienti di bloccare la condivisione dei dati. Potrebbero essere in vigore norme interne che consentono di vedere solo una parte dei dati raccolti. I dati possono essere danneggiati, persi o non raccolti. 

Nel mondo reale, raramente, se non mai, si dispone di dati perfetti. La buona notizia è che non occorre aspettare che i dati diventino perfetti per ricavarne informazioni chiave. Quando ricevete un insieme di dati, occorre che ne comprendiate le limitazioni o i difetti e ne definiate il significato in relazione alla vostra capacità di prendere decisioni. La vostra analisi può ancora mostrare le tendenze anche con tutti gli avvertimenti che avete scoperto. 

In alternativa, potete prevedere come sarebbero stati i vostri dati se aveste avuto il set completo e condividere i dati proiettati nella vostra analisi, se ha senso. Fate ipotesi. Utilizzate in modo creativo ciò che avete. Conoscete i vostri dati e migliorerete l'accuratezza delle vostre previsioni. Non aspettate che vi arrivino dati perfetti. Non lasciatevi sommergere dai dati. 

Ecco alcune raccomandazioni su come gestire le imperfezioni e le incompletezze dei dati:

* Costruite la Data Analytics in modo incrementale 
* Applicate alcune ipotesi ragionevoli
* Collaborate e utilizzate una mentalità di connessione dei punti
* Siate trasparenti nei confronti degli stakeholder per condividere la logica della Data Analytics.
* Cercate di selezionare i dati/KPI giusti per scoprire la verità

#### Lacune nei dati

È molto importante iniziare il percorso di analisi di business analizzando le lacune dei dati. Quali dati vi mancano e quanto è importante che li abbiate? Se stabilite che questi dati sono essenziali per l'analisi dei fatti (ad esempio, in quale lingua il prodotto viene servito agli utenti), occorre che troviate un modo per tracciarli. Identificate il proprietario dell'azienda e convincetelo che questi dati devono essere raccolti e analizzati in futuro. Questo processo può richiedere mesi, oltre che pianificazione e risorse. 

Inoltre, non sarete in grado di trarre conclusioni dai dati finché non ne avrete raccolti per almeno qualche mese. Se state già raccogliendo i dati, ma non sono catalogati o non sono normalizzati, la vostra analisi potrebbe non essere fattibile o addirittura possibile. Anche la pulizia dei dati non è un'impresa facile. Pertanto, un globalization leader dovrebbe investire tempo nell'identificazione delle lacune nella raccolta dei dati e quindi assegnare risorse per analizzare e comprendere l'integrità dei dati. 

Consultate l'[inventario dei dati](#appendix-b-data-inventory) e la matrice decisionale per identificare rapidamente l'insieme di dati di cui avete bisogno e come costruirlo:


<table>
  <tr>
   <td><strong>Che tipo di decisione aziendale devo prendere/quale tipo di problema devo risolvere/per quale tipo di domanda potrebbero servire i dati per rispondere</strong>
   </td>
   <td><strong>Che tipo di Data Analytics potrebbe aiutarmi </strong>
   </td>
  </tr>
  <tr>
   <td>Qual è l'opportunità di business internazionale?
   </td>
   <td>• Benchmark con altri prodotti localizzati all'interno dell'azienda
<p>
• Benchmark rispetto alle aziende del settore
<p>
• Dati TAM (Total Addressable Market) (ricerca di terzi) 
   </td>
  </tr>
  <tr>
   <td>Qual è il motivo della localizzazione? (qual è il valore della localizzazione per la mia azienda)
   </td>
   <td>• Aumentare le entrate in un mercato
<p>
• Migliorare la soddisfazione dei clienti, misurata attraverso sondaggi e feedback dei clienti.
<p>
• Ottenere un maggior consumo di contenuti, misurato attraverso le visualizzazioni di pagina e i tassi di abbandono
<p>
• Risparmiare sui costi della funzione di supporto, grazie alla riduzione delle chiamate di assistenza.
   </td>
  </tr>
  <tr>
   <td>In quali lingue di destinazione devo localizzare?
   </td>
   <td>• Impostazioni linguistiche dei visitatori per l'interfaccia utente del software, le pagine web e la documentazione
<p>
• Requisiti legali (es. Canada, Francia)
<p>
• Opportunità di business della regione, TAM, entrate, feedback dei clienti
<p>
• Tolleranza inglese
<p>
• Stato del concorrente
<p>
• Allineamento strategico con altri prodotti dell'azienda
   </td>
  </tr>
  <tr>
   <td>In presenza di più prodotti, quale prodotto deve essere localizzato per primo? O dovrebbero essere localizzati tutti insieme?
   </td>
   <td>• Budget di localizzazione disponibile (eventuale strategia pluriennale)
<p>
• Prontezza all'internazionalizzazione del prodotto (quanto impegno richiederà)
<p>
• Organico interno di globalizzazione a supporto dell'impegno
<p>
• Impegno/priorità del Product Team
<p>
• Analisi dei ricavi per Paese
<p>
• Approfondimento TAM per Paesi
   </td>
  </tr>
  <tr>
   <td>Qual è il costo dell'aggiunta/manutenzione di una nuova lingua e della funzionalità di internazionalizzazione?
   </td>
   <td>• Complessità di internazionalizzazione + costo di localizzazione + frequenza di rilascio
<p>
• Prima volta o localizzazione successiva?
   </td>
  </tr>
  <tr>
   <td>Qual è il costo di NON aggiungere una lingua?
   </td>
   <td>• Perdita di opportunità di business (i numeri delle entrate regionali di solito sono forniti dall'organizzazione Sales)
<p>
• Soddisfazione e fidelizzazione dei clienti 
   </td>
  </tr>
  <tr>
   <td>Quale tipo di contenuto ha il maggiore impatto sui clienti e dovremmo considerare di localizzarlo per primo? (KB, UI, documenti, materiali di formazione, ecc.)
   </td>
   <td>• Dati sull'utilizzo dei contenuti/sul traffico
   </td>
  </tr>
  <tr>
   <td>Come misurare l'impatto commerciale/l'efficacia della localizzazione su ciascun prodotto e sul suo contenuto?
   </td>
   <td>• Benchmark di dati storici (prima e dopo la localizzazione): fatturato della regione, traffico e fidelizzazione dei clienti, costi di supporto. 
   </td>
  </tr>
  <tr>
   <td>Quale modello di resourcing dovrei utilizzare (interno o fornitore, distribuzione del team)?
   </td>
   <td>• Costo (costi interni o del fornitore)
<p>
• Tempo di completamento
<p>
• Costo di funzionamento (gestione del fornitore, formazione, cambio di fornitore)
<p>
• Volume e scalabilità
   </td>
  </tr>
  <tr>
   <td>Quali sono i KPI per misurare l'efficienza del team di localizzazione? 
<p>
Team interno e team di fornitori
<p>
Automazione/fazione della catena degli strumenti e della pipeline
   </td>
   <td>• Numero di release di prodotti o progetti di contenuti per persona;
<p>
• Tempo medio di consegna
<p>
• Percentuale di automazione dei compiti
<p>
• Metriche per il rilevamento precoce della conformità i18n 
   </td>
  </tr>
  <tr>
   <td>Come misurare la qualità della localizzazione
   </td>
   <td>• QA operativo interno (numero di bug, parole chiave di globalizzazione standard)
<p>
• Feedback/valutazione dei clienti (interni ed esterni), potenziali escalation
   </td>
  </tr>
  <tr>
   <td>Qual è il livello di preparazione alla globalizzazione/localizzazione del prodotto/dell'azienda?
   </td>
   <td>• Scheda di valutazione dell'internazionalizzazione
<p>
• Matrice della lingua
<p>
• Heatmap dell'esperienza del cliente internazionale end-to-end
   </td>
  </tr>
  <tr>
   <td>Qual è il valore aziendale della localizzazione nel tempo (prima e dopo la localizzazione)?
   </td>
   <td>Tracciamento di questi dati della regione target prima e dopo il completamento della localizzazione
<p>
• Entrate 
<p>
• Soddisfazione del cliente
<p>
• Consumo di contenuti
   </td>
  </tr>
  <tr>
   <td>Come misuriamo l'utilizzo dei contenuti localizzati
   </td>
   <td>• Conteggio delle pagine di contenuti localizzati, 
<p>
• Percentuale di visualizzazione di pagine con contenuti localizzati
<p>
• Feedback dei clienti sulle pagine localizzate
   </td>
  </tr>
</table>


### Ruoli di Globalization Data Engineering e Globalization Data Analyst

Negli ultimi anni, un numero sempre maggiore di aziende globali ha aggiunto ai propri Globalization team ruoli di ingegneria dei dati e di analisi dei dati. Questi ruoli lavorano in tandem per identificare i dati chiave sulla globalizzazione che devono essere monitorati. Collaborano anche alla strumentazione dei contenuti (interfaccia utente del software, documentazione, pagine Web, ecc.) per comprendere il comportamento dei clienti internazionali. 

L'automazione è un altro aspetto chiave della pipeline di dati sulla globalizzazione e un requisito fondamentale per riportare i risultati in modo automatico e frequente. Infine, gli analisti della globalizzazione sono responsabili dell'interpretazione dei dati, dell'identificazione e della presentazione di informazioni chiave e azioni.

Ecco una descrizione del lavoro per Senior Analytics Engineer, Globalization Data Science and Engineering, pubblicato da una società di streaming globale:

>> Siamo alla ricerca di un **Senior Analytics Engineer** fortemente motivato che collabori a stretto contatto con i team aziendali per definire, misurare e visualizzare le metriche che consentono una localizzazione efficace ed efficiente. In questo ruolo di grande impatto, avrete un'influenza diretta sulle decisioni relative alla globalizzazione attraverso la collaborazione tecnica e commerciale.
>>
>>**Di cosa vi occuperete:**
>>
>>* Guidare la ricerca per lo sviluppo di nuove metriche per quantificare l'esperienza dei membri locali.
>>* Costruire e mantenere solidi aggregati e pipeline di dati.
>>* Analizzare in modo creativo i dati per generare informazioni chiave a supporto delle decisioni aziendali e identificare nuove opportunità.
>>* Progettare e analizzare test A/B per sostenere le innovazioni di prodotto.
>>* Costruire e rinnovare rapidamente dashboard e altri strumenti di visualizzazione.
>>* Comunicare i propri contributi (in forma scritta, verbale e di presentazione) a tutti i livelli dell'azienda con diversi livelli di preparazione tecnica.
>>
>>**Il vostro background e le vostre caratteristiche:**
>>
>>* Comprovata capacità di trasformare grandi quantità di dati complessi in informazioni chiave, guidando la creazione end-to-end di prodotti di dati intuitivi.
>>* Esperti nell'elaborazione di query e nella manipolazione di insiemi di dati utilizzando SQL e Python e strumenti di visualizzazione come Tableau (o strumenti simili)
>>* Familiarità con i metodi statistici e i test A/B
>>* Entusiasmo nella creazione di relazioni solide con gli stakeholder
>>* Self-starter con un elevato livello di autonomia
>>* Vi sentite a vostro agio con l'ambiguità e la traduzione di domande aziendali astratte in informazioni chiave attuabili e prodotti di dati ad alto impatto
>>* Entusiasta della cultura aziendale

### Partnership

Per preparare al meglio i dati e massimizzare l'impatto della Data Analytics, lavoriamo con diversi stakeholder e costruiamo solide partnership, soprattutto in questi settori:

* **Raccolta dati**. I team locali forniscono i dati della regione (ad esempio, i numeri delle vendite) che il team globale può utilizzare nell'analisi. Condividiamo con loro le nostre analisi e le nostre informazioni chiave perché aggiungono una prospettiva globale alla loro parte di business e danno loro accesso a dati che altrimenti non avrebbero ottenuto. Si tratta di un rapporto win-win, che facilita lo scambio di dati e la collaborazione all'interno dell'azienda.

* **Collaborare alla Data Analytics e alle discussioni per giungere a conclusioni d'impatto.** Quando condividiamo il dashboard o il report, includiamo i metadati, ovvero le informazioni sulla fonte dei dati, su come sono stati raccolti e sui loro limiti. Includiamo le ipotesi e le condizioni di utilizzo dei dati, il modo in cui abbiamo eseguito i calcoli e raggiunto le conclusioni. In questo modo, i nostri utenti che si occupano di Data Analytics comprendono il contesto e lo sfondo della raccolta e dell'analisi dei dati, il che consente loro di offrire suggerimenti per migliorare la nostra analisi. Questa collaborazione rende il lavoro di analisi più significativo e le informazioni chiave e le raccomandazioni più affidabili. 

* **Processo decisionale basato sui dati.** L'unico modo efficace per presentare la vostra analisi è sapere come il vostro pubblico prende decisioni basate sui dati; cosa cercano nella vostra presentazione. 
    * Al management superiore (o ai dirigenti), presenteremo slide formali, aperte con analisi, impatto sul business e raccomandazioni. Prevedete backup con dati dettagliati. E non dimenticate la conclusione e la call-to-action alla fine.
    * Per il team operativo interno, abbiamo inserito tutti i dati e le analisi in un dashboard, che fornisce dettagli e consente di analizzare le metriche rilevanti per le prestazioni quotidiane.
    * È importante comprendere le specifiche di raccolta dei dati e le loro limitazioni per poter prendere decisioni migliori e intraprendere azioni più efficaci. 


### Strumenti di analisi

* **Foglio Excel.** Excel è la base di tutte le analisi e il più versatile degli strumenti. Le capacità di calcolo del programma, abbinate alla funzionalità dei grafici, lo rendono lo strumento preferito e indispensabile per qualsiasi analista. Con Excel si può fare praticamente tutto. Ad eccezione, forse, dell'analisi di insiemi molto ampi di dati. A tal fine, sono necessari strumenti più potenti.
* **Adobe Analytics e Google Analytics.** Gli strumenti Web Analytic vengono utilizzati per tracciare l'utilizzo dei contenuti e delle pagine web in diverse località. Con questi strumenti potete comprendere meglio il percorso del cliente e il suo comportamento/preferenza. La conoscenza cumulativa dei vostri clienti vi permetterà di progettare siti Web più efficaci con un migliore coinvolgimento dei clienti, di produrre contenuti che risuonino con i visitatori del sito, di creare interazioni che migliorino la soddisfazione dei clienti e di misurare il valore dei contenuti localizzati. 

    Sia Adobe Analytics che Google Analytics sono ampiamente utilizzati per tracciare gli utenti nelle proprietà digitali, analizzare il comportamento sul sito e misurare i risultati aziendali. Ad esempio: * Traffico/download dei clienti per regione/località * Analisi dei referral (da dove i clienti trovano i contenuti, ad esempio motori di ricerca, un altro sito Web aziendale, ecc. * Flusso di clic del percorso dei clienti sulle pagine * Popolarità dei contenuti in base a diverse granularità * Tracciamento di obiettivi e risultati con una varietà di modelli di attribuzione * Test A/B e multivariati

  *Esempio di report da Adobe Analytics* 
  
  ![Esempio di report da Adobe Analytics](/media/Chapter%206_Adobe%20Analytics%20Example.png)    
                
  *Esempio di report da Google Search Console*
  
   ![Esempio di report da Google Search Console](/media/Chapter%206_Google%20Console%20Example.png)

* **Report/analisi del Translation Management System (TMS).** Gran parte dei dati delle transazioni di traduzione quotidiane gestite tramite il TMS, così come i dati commerciali associati, sono in genere archiviati nel database di backend del TMS. Questo include progetti, lingue, prezzi, tempistiche e scadenze, informazioni sui fornitori e molto altro ancora. Questi dati sono importanti per definire le metriche sui dati di produzione, ad esempio:
    * volume tradotto mensilmente
    * volume tradotto dal fornitore
    * volume per tipo di contenuto
    * cliente interno, lingua
    * informazioni su costi e prezzi
    * Utilizzo di contenuti simili tradotti in precedenza dalla memoria di traduzione, ecc. 

    Queste metriche vi aiuteranno a valutare lo stato di salute della pipeline di localizzazione e del modello di business implementato. Queste informazioni sono preziose se si è in grado di fare un benchmark con organizzazioni simili in altre aziende. 

    I dashboard aiutano gli stakeholder a tenere traccia dei processi in corso. In qualità di project manager, potreste disporre di un dashboard di progetto che vi consente di approfondire dettagli specifici. In qualità di product manager o product owner, un dashboard potrebbe mostrare lo stato del prodotto in un determinato momento. In qualità di Globalization o QA Engineer, potreste vedere cosa vi aspetta. 


    Un TMS può essere dotato di funzionalità di reporting e dashboarding robuste e scalabili, oppure fornire l'integrazione o la connettività con uno strumento di reporting di terze parti che può essere utilizzato per il reporting e l'analisi dei dati. Poiché la maggior parte dei TMS memorizza i dati di produzione in un formato di database comune (ad esempio SQL, MySQL, Oracle), gli strumenti di reporting di terze parti offrono flessibilità. Le esigenze di un'azienda possono essere diverse in base all'infrastruttura, ai linguaggi di query e ai livelli di automazione (ad esempio, Jenkins). Si consiglia di utilizzare uno strumento di visualizzazione (ad esempio Power BI, Tableau) per analizzare e visualizzare meglio i dati non elaborati che uno strumento di reporting potrebbe fornire.

* **Analisi del sentiment**. L'analisi del sentiment è fondamentale per trasformare i feedback in informazioni chiave sui clienti. 

    L'analisi del sentiment prevede l'utilizzo di tecniche di analisi del testo per interpretare e classificare le emozioni (positive, negative e neutre), i sentimenti (rabbia, felicità, tristezza, ecc.) e persino le intenzioni (ad esempio, interesse o non interesse) nell'ambito dei dati testuali. Il linguaggio umano è complesso e insegnare a una macchina ad analizzare le varie sfumature grammaticali, le variazioni culturali, lo slang e gli errori ortografici che si verificano nelle menzioni online è un processo difficile. 

    È possibile ottenere informazioni chiave da grandi insiemi di dati (ad esempio, milioni di tweet o commenti su Facebook). Molti sistemi di rilevamento delle emozioni utilizzano lessici (cioè elenchi di parole e delle emozioni che esse trasmettono) o complessi algoritmi di apprendimento automatico. Si tratta di un insieme di regole create dall'uomo per aiutare a identificare la polarità attraverso varie tecniche sviluppate nella linguistica computazionale, come lo stemming, la tokenizzazione, il part-of-speech tagging e il parsing. I sistemi ibridi che combinano approcci basati su regole e approcci automatici sono i più accurati. 

    Esistono diversi strumenti che si occupano di fornire l'analisi del sentiment. Per scegliere l'uno o l'altro, occorre porsi le seguenti domande: * Lo strumento dispone di funzioni di rilevamento della lingua, di traduzione automatica e di scomposizione automatica dei dati (creazione di dashboard)? * Le lingue e i mercati a cui volete rivolgervi sono tutti coperti dallo strumento? * Lo strumento è in grado di discernere mercato e lingua (ad esempio, se il testo è in spagnolo e la provenienza geografica può essere rilevata e monitorata)? * Utilizzerete lo strumento essenzialmente per il sentiment dei prodotti o per il sentiment del marketing?

Una volta che i Globalization team hanno raccolto i dati analitici, questi possono essere presentati su vari dashboard. Ogni dashboard può rivolgersi a una persona o a un'area aziendale specifica. I dashboard sono più dinamici delle diapositive di presentazione e consentono agli analisti di dati sulla globalizzazione di estrarre più facilmente tendenze e informazioni chiave. 

È possibile creare semplici grafici e dashboard in Microsoft Excel. Excel è anche un valido strumento di sandbox per verificare l'integrità dei dati e identificare le informazioni chiave iniziali. Oltre a Microsoft Excel, le aziende di medie e grandi dimensioni hanno solitamente accesso a soluzioni più robuste per la gestione dei dati e dei dashboard, come Microsoft Power BI (tramite licenza Microsoft Office 365) o Tableau. Un vantaggio fondamentale di questi strumenti di dashboard è la loro capacità di collegarsi a più fonti di dati. 

Infine, all'inizio ci si potrebbe sentire sopraffatti dai dati sulla globalizzazione. Consigliamo di iniziare con insiemi di dati e dashboard di piccole dimensioni e di farli crescere nel tempo.

### Come creare un business case

La direzione strategica basata sull'analisi dei dati è solo l'inizio. È necessario che il team esecutivo creda che il piano migliorerà l'esperienza del cliente e porterà benefici all'azienda. Per far sì che le vostre raccomandazioni diventino realtà, avete bisogno di una sponsorizzazione e di finanziamenti da parte dei dirigenti. Dovrete creare un business case. 

"Quale problema del cliente sto risolvendo?" è la domanda a cui dovreste rispondere nel momento in cui mettete insieme la vostra proposta. Il problema del cliente di solito emerge dai colloqui con i clienti. I dati aiutano a convalidare il problema e aggiungono un aspetto di impatto commerciale alla storia. Le proiezioni di miglioramento o le entrate future saranno il vostro parametro di successo una volta trovata una soluzione per risolvere il problema. 


#### Utilizzare i dati per creare un business case

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> David era appena stato assunto come responsabile della localizzazione per una startup pronta a uscire dal suo mercato nazionale. Analizzando i dati relativi al mercato europeo, è emerso chiaramente che il tedesco doveva essere una delle lingue supportate dalla sua azienda. 
> 
> Purtroppo la traduzione in tedesco non era inclusa nel budget. I Product Manager gli dissero che in Germania tutti parlavano comunque inglese. 
> 
> David si è messo al lavoro sulla sua proposta commerciale. Ha trovato i dati sul mercato tedesco totale indirizzabile (TAM) in una delle presentazioni di vendita, ha ottenuto informazioni sulle operazioni commerciali locali in corso e ha calcolato approssimativamente il valore potenziale di tali operazioni. David ha scoperto che tutti i concorrenti diretti nella regione supportavano il tedesco. I team locali hanno raccontato di aver perso un paio di contratti a causa della mancanza di un supporto in lingua madre e che un prodotto localizzato avrebbe permesso di ottenere altre 100.000 dollari di vendite nei 12 mesi successivi. 
> 
> David ha presentato la sua proposta ai dirigenti della sua startup e ha esposto il problema: le aspettative dei clienti nel loro settore richiedono che il software sia disponibile in tedesco; la loro azienda deve tradurre il loro prodotto in tedesco per essere competitiva. 
> 
> David ha dichiarato che a fronte di un investimento iniziale di 70.000 dollari per le traduzioni, l'azienda avrebbe potuto ottenere circa 300.000 dollari di ricavi da accordi in fase di definizione nel Paese nel primo anno. 
> 
> Inoltre, non solo aumenterebbero la loro quota di mercato nella regione, ma sarebbe anche un buon inizio per la riconoscibilità del loro marchio. Se ritardassero di un altro anno o due, sarebbe molto più difficile espandersi sul mercato a causa della reputazione consolidata di un'azienda che comunica solo in inglese. 
> 
> Concentrarsi sul problema di business ha reso l'argomentazione di David convincente e rilevante per la crescita dell'azienda. Ha ottenuto i finanziamenti.

Non basta dare raccomandazioni sulla direzione da seguire e spiegare come dovrebbe apparire l'esperienza dell'utente a livello internazionale. La creazione di un business case per queste raccomandazioni definirà perché è importante per l'azienda e per i clienti. L'analisi dell'impatto sul business semplifica la definizione delle priorità e contestualizza la soluzione.

Le seguenti best practice e casi d'uso illustrano: * come si possono utilizzare le metriche * come possono influenzare le decisioni * quali sono i limiti dei dati e delle metriche * quali sono le best practice per gestire le informazioni chiave dai dati che si stanno raccogliendo * come altri fattori, come gli aspetti geo-politici e geo-culturali, influenzano i dati e le informazioni chiave * come si può influenzare il risultato.

  > <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Negli ultimi anni, l'azienda di Bill ha aggiunto diverse nuove linee di prodotti a seguito di fusioni e acquisizioni. La maggior parte dei nuovi prodotti acquisiti non è stata ancora localizzata. 
  >
  >Bill voleva collaborare con il Product Team per valutare l'opportunità commerciale di globalizzare/localizzare i prodotti, nel caso in cui fosse prevista la vendita in Paesi in cui l'inglese non è la lingua principale. Bill ha pianificato di raccogliere e studiare questi dati utilizzando uno dei prodotti appena acquisiti per guidare la globalizzazione e la localizzazione. 
  >
  >Domanda: esiste un'opportunità di business valida per questo prodotto al di fuori degli Stati Uniti? Il 40% del fatturato dell'azienda X proviene dai mercati esteri. 
  >
  >Bill ha raccolto i dati di fatturato del prodotto A dell'anno fiscale precedente, suddivisi per Paese. Ha scoperto che quasi il 90% delle entrate per questo prodotto proveniva dal mercato statunitense, mentre la percentuale di prenotazioni dal mercato estero era piuttosto bassa. Questa scoperta ha dato a Bill l'indicazione che per questo prodotto ci sarebbe stata una buona opportunità di espandere l'attività nei mercati globali al di fuori degli Stati Uniti. 
  >
  >Oltre ai dati sui ricavi, Bill ha consultato i rapporti di ricerca del settore (Gartner o IDC) per verificare il mercato totale indirizzabile (TAM) e le opportunità di mercato (MO) in ciascun paese. Questo potrebbe far luce su quale regione/località dovrebbe concentrarsi e su quale potrebbe non rappresentare un'opportunità significativa dopo tutto. 
  >
  >Il prodotto A è un prodotto di sicurezza software e il Giappone e la Germania hanno un rating TAM più alto rispetto alle altre regioni. Inoltre, a causa delle politiche di regolamentazione in Cina, il TAM per i prodotti di sicurezza delle aziende straniere è ridotto. 
  >
  >Un altro fattore chiave era l'impatto sui clienti di Bill, poiché sapeva che i clienti di ogni Paese hanno un ETI (English tolerance index, ovvero indice di tolleranza dell'inglese) diverso, che può dipendere anche dal settore. Ad esempio, la tolleranza dell'inglese in Giappone e la competenza in settori specifici sono inferiori rispetto ad altri Paesi. La mancanza di localizzazione dei prodotti potrebbe essere un ostacolo per i clienti. Nei Paesi europei, invece, sebbene i clienti preferiscano utilizzare i prodotti nella loro lingua, possono convivere con l'uso dell'inglese. 
  >
  >Esistono diversi istituti e società che forniscono risultati di ricerca sulla tolleranza e sulla competenza in inglese, ad esempio l'EPI (English proficiency index, ovvero indice di conoscenza dell'inglese), che potrebbe aiutarci a classificare i Paesi in base all'impatto sui clienti. 
  >
  >Bill ha anche studiato il panorama competitivo del prodotto A (CSR), prima che il suo team lanciasse il prodotto in regioni non anglofone. Bill sperava che le loro offerte di localizzazione potessero portare un vantaggio al prodotto A al momento del lancio in mercati non anglofoni. Ha inserito tutti questi dati in una formula per calcolare l'Effectiveness Score (ES) di ogni località per ottenere una classifica di priorità per le varie località. ![Immagine della formula](/media/Chapter%206_Formula%20ES.png)          
  >  CC: coefficiente di costo della globalizzazione (indicatore dei costi di internazionalizzazione e localizzazione) 


### Misurare la qualità e l'efficacia della MT

Esistono diverse metriche per misurare la qualità e l'efficacia della traduzione automatica. Uno di questi è quello di ottenere un feedback immediato dei clienti sull'utilità dei contenuti tradotti. In questo caso, il Localization Team ha lavorato con i propri stakeholder per identificare una metrica di successo che fosse significativa per loro e che funzionasse per il reparto Localization. 

Il monitoraggio delle risposte dei clienti alla domanda "queste informazioni ti hanno aiutato a risolvere il tuo problema" ci permette di valutare l'utilità dei nostri articoli tradotti, utilizzando la stessa metrica che usiamo per i nostri articoli in inglese. Potremmo ritenere che, fintanto che otteniamo un punteggio che non supera il 5% di quello ottenuto in inglese, la qualità dell'output della traduzione automatica sia accettabile e l'articolo in lingua locale rappresenti un valore aggiunto per i nostri clienti. Questa metrica potrebbe anche essere utilizzata insieme alla frequenza di rimbalzo per valutare se gli utenti rimangono sulla pagina tradotta automaticamente o passano all'inglese.

In qualità di globalization leader, avete la responsabilità di creare prodotti localizzati che corrispondano all'esperienza originaria (solitamente in inglese). Occorre inoltre dimostrare l'eccellenza operativa soddisfacendo i vari vincoli di costo, risorse e tempo. Per raggiungere i vostri obiettivi, la dipendenza dai Product Team è fondamentale, poiché sono responsabili dell'internazionalizzazione. Il team di sviluppo può evitare di affrontare i numerosi difetti delle versioni localizzate producendo innanzitutto software internazionalizzato. Questo approccio faciliterà anche l'automazione del processo di localizzazione. 

D'altra parte, se un prodotto è scarsamente internazionalizzato, dovrete sviluppare molti work-around, i problemi saranno replicati in tutte le località e gli sforzi per risolverli in seguito saranno amplificati. Quindi, come potete responsabilizzare i Product Team in materia di internazionalizzazione? Come si tiene traccia della conformità e dei progressi nel tempo? Come fate a motivare i Product Team a migliorare la preparazione al mondo senza un'autorità diretta?

Una best practice del settore per affrontare questi problemi ha previsto lo sviluppo di schede di punteggio sulla preparazione al mondo e comunicare questi dati in riunioni, e-mail e newsletter per aumentare la visibilità e la motivazione. Un aspetto positivo dei dati è che lasciano poco spazio alla discussione. È difficile sostenere che un prodotto sia scarsamente internazionalizzato quando si fornisce un punteggio di preparazione al mondo supportato da un elenco di difetti di internazionalizzazione. I dati eliminano le emozioni dall'equazione.

Per elaborare una scheda di valutazione sulla preparazione al mondo, raccomandiamo i seguenti passi:

1. **Definire chiari requisiti di internazionalizzazione**. I requisiti di internazionalizzazione devono essere documentati in modo che i Product Team comprendano le vostre aspettative. Questi requisiti serviranno anche come base per misurare il punteggio associato a ciascun prodotto. Più alto è il punteggio, più il prodotto soddisfa i requisiti.

2. **Creare un sistema di schede di valutazione**. Nello sviluppo di applicazioni internazionalizzate è necessario considerare diversi aspetti. Alcuni aspetti riguardano l'abilitazione, altri la localizzabilità. L'abilitazione si riferisce allo sforzo di internazionalizzazione che garantisce che tutte le funzionalità incluse nel prodotto principale (inglese) continuino a funzionare a livello globale, supportando l'input/output di dati da vari script, formati di data, valute, ecc. La localizzabilità rappresenta le attività di internazionalizzazione che si concentrano sul rendere possibile la localizzazione, come l'esternalizzazione delle stringhe, la configurazione di un ambiente di compilazione multilingue, la possibilità di cambiare facilmente locale, ecc.

3. **Usare parole chiave standard per i difetti**. Quando i prodotti non soddisfano i requisiti di internazionalizzazione, i difetti devono essere registrati in un database di bug utilizzando una classificazione standard (ad esempio INTL-LAYOUT, INTL-HARDCODED, ecc.). Questo vi permetterà di generare schede di valutazione della globalizzazione, auspicabilmente in modo automatico.

4. **Pubblicare i risultati**. Una volta che i prodotti sono stati valutati, è possibile iniziare a pubblicare i loro punteggi di preparazione al mondo. Inizialmente, è importante istruire i Product Team sul processo e sulla metodologia utilizzati per ottenere il punteggio di preparazione al mondo. In questo modo si evitano brutte sorprese. Una volta che tutti sono informati sul programma, è possibile condividere i risultati in modo più ampio e lavorare con i Product Team per migliorare il loro punteggio, se necessario.

5. **Preparare piani di recupero**. Ogni Product Team avrà una propria serie di problemi di internazionalizzazione e chiederà al Globalization Team indicazioni su come affrontarli. Il piano di recupero serve a questo scopo. Documenta le aree in cui il prodotto non soddisfa i requisiti di internazionalizzazione e fornisce suggerimenti su come affrontare tali lacune. Il piano di recupero può anche includere liste di controllo di internazionalizzazione per le aree più problematiche.

6. **Sviluppare un programma educativo di preparazione al mondo**. Se i Product Team sono impegnati nello sviluppo di prodotti ben internazionalizzati, consigliamo di creare un corso di internazionalizzazione per evidenziare le insidie generali e le best practice.

7. **Fornire librerie per la globalizzazione e promuovere gli standard**. Alcuni Product Team possono avere difficoltà con la globalizzazione perché si affidano a librerie interne che non offrono un forte supporto internazionale. Per ridurre questi problemi, si consiglia di utilizzare librerie standard con supporto integrato per l'internazionalizzazione, come ICU, MomentJS, Int'l React, ecc.

Implementando un programma di preparazione al mondo basato sui punteggi, sarete in grado di valutare i prodotti e misurare i progressi nel tempo. Implementerete anche un meccanismo di gamification. I Product Team competeranno tra loro per ottenere un punteggio elevato di preparazione al mondo. Questo ridurrà la pressione sul vostro team per inseguire i Product Team. Si rivolgeranno a voi per cercare una guida e un sostegno.

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> L'azienda di Susan voleva aumentare la propria impronta globale e la base di utenti. Susan, Globalization Lead di un'azienda tecnologica, ha deciso di valutare i vantaggi del lancio dell'app aziendale in un'altra località.  
> 
> Per creare un business case, Susan doveva definire i criteri per l'applicazione delle risorse a un determinato mercato (definito da variabili che includono dimensioni, crescita, rischi per il governo, rischi per gli utenti e valore per la nostra azienda). Susan aveva bisogno di dati per informare in modo adeguato e guidare il processo decisionale. 
> 
> Di seguito sono riportate le domande che Susan ha utilizzato per qualificare i dati disponibili come rilevanti per la sua valutazione del mercato:
> 
> * Abbiamo già un pubblico in questo mercato?
>     * Raccogliere dati sugli utenti attivi mensili e settimanali, sulle iscrizioni settimanali e sul tasso di attivazione, sulle località degli utenti e sull'uso mensile dei prodotti/caratteristiche.
> * Il pubblico è pronto per il nostro prodotto?
>     * Raccogliere dati sul comportamento degli utenti, ad esempio il numero di utenti dei social media, i possessori di smartphone, la quota di mercato digitale e la concorrenza. Combinare con dati gratuiti sullo stile di vita degli utenti (livello di istruzione, partecipazione alla forza lavoro uomo-donna, distribuzione del PIL pro capite, ecc.), spesa pubblicitaria digitale, conoscenza dell'inglese.
> * Che tipo di coinvolgimento ha mostrato il pubblico attuale sul nostro prodotto?
>     * Raccogliere dati sul numero di ticket che riceviamo in media da questa regione e sul sentiment espresso dagli utenti di questa regione.
> * Esistono analogie storiche e/o proiezioni sul successo dell'azienda in quel mercato?
>     * Raccogliere i dati dei mercati che possono essere utilizzati come analogie per modellare il numero previsto di nuovi utenti se forniamo un'esperienza localizzata, e formulare una misura percentuale di crescita potenziale, possibilmente in un tasso di attivazione a basso e alto livello.
> * Quali sono i rischi associati al lancio in questa regione?
>     * Fare un benchmark se altre aziende hanno già avuto successo sul mercato. Quali sono gli obiettivi che intendiamo raggiungere entro un determinato periodo di tempo? Qual è la quota di mercato che vogliamo raggiungere?
>    * Considerate la tempistica: cosa deve essere vero per andare in quella regione? Quali sono i principi guida della strategia GTM? E se non cominciassimo ora, quali sarebbero le perdite? Se non ora, quando?
>     * Raccogliere schede di valutazione nazionali sulla stabilità politica della regione, sulle restrizioni legali legate ai contenuti/app, sui costi da dedicare alla riduzione del rischio della regione (creare un'entità legale, lavorare con Trust and Safety per perfezionare i contenuti che condividiamo nella regione, ecc.).
> * Quali sono i costi aggiuntivi e/o i debiti tecnici associati a questo lancio?
>     * Raccogliere dati per capire se il supporto di una nuova lingua introdurrebbe complessità tecniche (come nel caso delle lingue da destra a sinistra), se necessita di un lavoro di base sulla qualità del prodotto.

A volte i dati possono suggerire una risposta netta: sì o no. Tuttavia, in alcuni casi o per alcune regioni, i dati sono controversi o incoerenti e la loro interpretazione è fondamentale. Ad esempio, mentre tutti i dati sembrano rassicuranti e suggeriscono di investire in un mercato specifico, la situazione politica in continuo mutamento potrebbe richiedere un po' di cautela, oppure una scarsa infrastruttura internet potrebbe consigliare di lanciare una versione leggera dell'app, se non addirittura di non lanciarla affatto. 

I dati non sono in grado di prendere una decisione e non spiegheranno tutto in modo esauriente, ma possono informare su quali sono le probabilità di successo o di insuccesso. Potrebbe esservi utile la regola 40:70 di Colin Powell per il processo decisionale: come regola empirica, ogni volta che ci troviamo di fronte a una decisione difficile dovremmo avere non meno del 40% e non più del 70% delle informazioni necessarie per prendere una decisione. La regola ci permette di essere informati e allo stesso tempo di fidarci del nostro intuito.

> <img src="/media/story_icon.png" alt="immagine del libro" width="30"/> Il team centrale di Business Site e il Globalization Team hanno ricevuto una richiesta dal team di Singapore di supportare l'inglese-india come locale aggiuntivo disponibile su Business Site. Il pubblico di lingua inglese che visita il Sito aziendale accede attualmente a una delle due lingue inglesi disponibili sul sito: inglese USA o inglese UK. 
> 
> Tuttavia,
> 
> * il sito in inglese USA mostra contenuti rilevanti per gli utenti degli Stati Uniti (tutte le campagne, le funzionalità, i prodotti disponibili negli Stati Uniti);
> * il sito in inglese UK mostra contenuti rilevanti per gli utenti del Regno Unito/Gran Bretagna (tutte le campagne, le funzionalità e i prodotti disponibili in quel Paese).
> 
>  La disponibilità dei prodotti e servizi offerti sono molto diversi nel Regno Unito/Stati Uniti e in India.\** \*\*Per questo motivo, agli utenti indiani vengono mostrati prodotti e servizi non ancora disponibili nella loro regione, nonché informazioni chiave specifiche per il Regno Unito/Stati Uniti. Questo può portare a un'esperienza utente negativa quando gli utenti notano che il sito promuove contenuti che sono irrilevanti per loro. 
> 
> Gli obiettivi sono:
> 
> * Migliorare l'esperienza del sito business per gli utenti indiani (e per gli utenti asiatici di lingua inglese in generale) e aumentare la pertinenza dei contenuti.
> * Creare le basi per consentire ai team locali di comunicare con gli utenti degli account aziendali in base al marchio (ad esempio, attivando un blog in inglese per l'India/SEA (Sud-Est asiatico), separato dal blog del Regno Unito o degli Stati Uniti).
> * Per estendere questa esperienza all'intera regione SEA è sufficiente reindirizzare il traffico proveniente da queste aree geografiche verso la nuova sede del sito.
> * Aumentare il traffico verso il sito consentendo al team locale di promuovere attivamente il sito aziendale, perché l'esperienza sarà più rilevante per il loro pubblico.
> * Definire come misurare il successo e misurare l'impatto nell'esecuzione degli obiettivi. Ad esempio, come si fa a sapere che l'esperienza del sito aziendale è migliorata per gli utenti indiani e come la misuriamo?
> 
>  In che modo si può formulare una raccomandazione su come migliorare l'esperienza dell'utente per il nostro pubblico in India? E quali dati saranno utili per informare il processo decisionale? L'analisi può essere suddivisa in due parti: il dimensionamento delle opportunità e la valutazione della fattibilità operativa.
> 
> **Dimensionamento dell'opportunità:**
> 
> * Raccogliere dati sul traffico in lingua inglese proveniente dall'India sia per l'acquisizione che per il comportamento del pubblico;
> * Numero di sessioni, nuove sessioni, nuovi utenti, utenti, frequenza di rimbalzo, sessione della pagina, tempo medio per sessione, ecc.
> * Numero di PMI e di grandi imprese in India.
> * Eseguire un'analisi della concorrenza per capire chi serve un sito en-IN per il pubblico business.
> * Raccogliere i risultati SEO che portano traffico verso l'India (parole chiave uniche, ecc.).
> * Chiedere informazioni sulla strategia a lungo termine nella regione (monetizzazione, lancio di nuovi prodotti, ecc.).
> 
> In caso venisse rilevata un'opportunità, si passerebbe all'analisi della **fattibilità operativa**:
> 
> * Supporto tecnico, di progettazione e di localizzazione necessario per il lancio e la manutenzione del sito.
> * Costo dell'ottimizzazione SEO.
> * Elenco dei prodotti disponibili e non disponibili per l'India, per citare il numero di ore di redazione necessarie per adattare il sito al mercato.
> * Eseguire un'analisi dei costi per l'adattamento di informazioni chiave editoriali e il lancio di un blog separato.
> 
> In una situazione come questa, i dati sono informativi, ma non risolutivi. I dati ci informano e ci permettono di prendere le decisioni più razionali, ma non garantiscono un successo al 100%.


### Concetti chiave

Indipendentemente dal punto in cui vi trovate nel vostro percorso di analisi di business della localizzazione, ecco i principali elementi da tenere a mente:

* Promuovete una cultura orientata ai dati e creare una strategia orientata ai dati.
* Capite i dati e la storia che raccontano. Conoscete il vostro pubblico e create partnership con altre unità aziendali.
* Fornite ai vostri stakeholder informazioni chiave e una storia, non una valanga di dati.
* Utilizzate insiemi di strumenti esistenti per creare dashboard. 
* Assegnate la responsabilità a un individuo o a un team per la gestione dei dati e dei report.
* Iniziate a raccogliere dati il prima possibile.
* Semplificate la raccolta dei dati. La raccolta dei dati deve essere facile da eseguire regolarmente.
* Evitate di creare processi per raccogliere i dati manualmente. Idealmente, i dati devono essere estratti dalla produzione senza doverli prima inserire manualmente.
* Assicuratevi di poter raccogliere dati cumulativi senza dover manipolare i rapporti precedenti quando siete pronti a eseguire un nuovo report.
* Non affidatevi mai a una sola metrica.

E infine, il modo in cui presentate i dati conta. È un modo di comunicare e il vostro pubblico deve essere in grado di capirlo. Rendete la vostra presentazione semplice: 

* Rendete i dati leggibili. Utilizzate 1.000.000 invece di 1000000. Per presentare un formato numerico (1M), utilizzate la stessa abbreviazione (0,1M invece di 100K). Saltate i decimali a meno che non siano davvero importanti (15,34% diventa 15%). Allineate i numeri a destra. Non ripetete le stesse informazioni. Rimuovete barre e colonne, assi e linee di griglia, legende e bordi. L'idea è rendere i dati di facile lettura e di concentrarsi sul messaggio giusto.
* Non utilizzate grafici 3D. Il cervello ha difficoltà ad elaborarli. Utilizzate il 2D.
* Evitate i grafici a torta. Sembrano carini, ma è difficile giudicare le differenze relative nell'area o nei cerchi. Potrebbero avere troppi pezzi che creano molta confusione. Se avete più di tre articoli, utilizzate un'altra tabella.
* Non affidatevi esclusivamente al colore nella presentazione dei dati. Pensate alle persone daltoniche. Quando utilizzate i colori, dategli un significato, ad esempio separando i giorni della settimana da quelli del fine settimana. Utilizzate i colori in modo coerente in tutto il report.
* Siate coerenti. Utilizzate gli stessi riferimenti temporali su tutti i grafici (da lunedì a domenica, ad esempio). Utilizzate lo stesso ordine di voci per tutti i grafici di una categoria. Anche l'ordine degli articoli dovrebbe avere un significato. 


## Epilogo: la nostra conclusione

Ci sono letteralmente milioni di libri, articoli, guide e corsi online e di persona dedicati agli argomenti di strategia. La maggior parte di essi riguarda un approccio tattico alla strategia, suggerimenti e trucchi. Alcuni accennano al processo di riflessione, ma raramente ci sono risposte alle domande poste.

Anche le domande che solleviamo in questo libro potrebbero non avere tutte le risposte. Tuttavia, ora sapete dove cercarle e come convalidare le risposte trovate. Potete articolare il problema che state risolvendo e dimostrare con i dati che è il problema giusto da risolvere per l'azienda. Potete creare il vostro piano, comprensivo di risorse, tecnologia e lingue, giustificarlo e impostare metriche e report per gestire le aspettative dei numerosi stakeholder che ora sapete di avere.

In questa guida abbiamo cercato di collegare il processo di pensiero strategico a situazioni reali. Vi abbiamo mostrato come la strategia di globalizzazione si inserisce nella strategia aziendale, amplifica il vostro business nei mercati internazionali e guida l'esecuzione e la tecnologia. Ci sono grafici, tabelle ed esempi per aiutarvi ad applicare i modelli di pensiero della globalizzazione alla vostra organizzazione e ai vostri ruoli attuali.

I consigli e le best practice che abbiamo condiviso potrebbero o meno applicarsi al vostro team e alla vostra organizzazione. Dovrete pensare alla vostra strategia utilizzando questo libro come base, come guida da oggi al futuro.

I dodici collaboratori di questo libro risolvono enigmi strategici ogni giorno, in diversi ruoli, in diverse aziende, con diversi risultati. Non esiste un solo modo di agire quando si parla di strategia di globalizzazione. Ma c'è sempre il _modo giusto per voi_ e per la vostra organizzazione. Dovete essere pronti a prendere le decisioni giuste al momento giusto. Era nostra intenzione prepararvi a questo momento.

Questo libro è la bussola da portare con voi per il percorso della vostra strategia di globalizzazione verso il successo globale per i vostri clienti multilingue e la vostra azienda. Siate eccezionali e fateci sapere come questo libro vi ha aiutato nel vostro percorso.

Contattate il Globalization Strategy Navigation Team all'indirizzo [StrategyPlaybook@gmail.com](mailto:strategyplaybook@gmail.com)


## Appendice A: Fattori che influenzano le decisioni tecnologiche e obiettivi strategici


<table>
  <tr>
   <td><strong>Tecnologia</strong>
   </td>
   <td><strong>Descrizione</strong>
   </td>
   <td><strong>Fattori chiave decisionali</strong>
   </td>
   <td><strong>Obiettivi strategici</strong>
   </td>
  </tr>
  <tr>
   <td>Translation Management System (TMS)
   </td>
   <td>Un hub centrale collega vari strumenti come CMS, MT, gestisce le risorse, sfrutta le traduzioni esistenti, ecc. (si sconsiglia l'uso di più TMS)
   </td>
   <td>
<ul>

<li>Numero di lingue supportate

<li>Strategia del fornitore (singolo o multifornitore)

<li>Integrazione con il CMS: numero di sistemi a cui connettersi; out of the box o proprietario

<li>Automazione del flusso di lavoro del ciclo di vita del progetto

<li>Gestione degli asset (possesso di TM e TD)

<li>Tracciabilità del progetto/lavoro

<li>Reporting/dati per l'analisi

<li>Processo decisionale basato sui dati
</li>
</ul>
   </td>
   <td>
<ul>

<li>Time-to-market più rapido

<li>Consentono di risparmiare sui costi/efficienza

<li>Consentono la crescita globale

<li>Esperienza utente fantastica
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Traduzione automatica
   </td>
   <td>Tecnologia di traduzione automatica
   </td>
   <td>
<ul>

<li>Tipo di contenuto: è specializzato? La MT è adatta a quel tipo di contenuto?

<li>Volume del contenuto/costo della traduzione

<li>Tempo di completamento

<li>Qualità richiesta (abbastanza buona?)
</li>
</ul>
   </td>
   <td>
<ul>

<li>Consentono di risparmiare sui costi/efficienza

<li>Time-to-market più rapido

<li>Consentono la crescita globale

<li>Esperienza utente fantastica
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Terminologia
   </td>
   <td>Stabilire e gestire la terminologia, compreso il ciclo di vita (aggiungere, tradurre, aggiornare, rivedere, ritirare).
   </td>
   <td>
<ul>

<li>Numero di prodotti

<li>Ambito del programma (ad es. prodotti, marketing, web, contenuti didattici)

<li>Tipo di prodotti e industrie (tecniche, specializzate, regolamentate, ...) 

<li>Nomi di marchi
</li>
</ul>
   </td>
   <td>
<ul>

<li>Esperienza utente fantastica

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Gestione delle query
   </td>
   <td>Strumento che facilita l'efficace risoluzione delle query di traduzione.
   </td>
   <td>
<ul>

<li>Volume dei contenuti

<li>Complessità dei contenuti

<li>Numero di lingue supportate

<li>Numero di fornitori

<li>Numero di stakeholder

<li>Numero di prodotti

<li>Reporting/tracciamento
</li>
</ul>
   </td>
   <td>
<ul>

<li>Esperienza utente fantastica

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Gestione della qualità della traduzione
   </td>
   <td>Identificare, misurare, controllare e migliorare la qualità dei contenuti localizzati. 
   </td>
   <td>
<ul>

<li>Numero di marchi supportati

<li>Strategia del fornitore

<li>Volume dei contenuti

<li>Numero di lingue supportate

<li>Informazioni approfondite per informare la qualità del sorgente
</li>
</ul>
   </td>
   <td>
<ul>

<li>Esperienza utente fantastica

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Gestione dei costi in outsourcing 
   </td>
   <td>Tracciamento dei costi e budgeting per il lavoro in outsourcing, collegato agli strumenti di fatturazione/impegno utilizzati dal team finanziario - potrebbe far parte di una suite di gestione dei programmi.
   </td>
   <td>
<ul>

<li>Strategia del fornitore (singolo o multifornitore)

<li>Numero di prodotti/progetti

<li>Requisiti del reparto finanziario per la tracciabilità degli ordini e delle fatture, per il budgeting e per la rendicontazione degli ammortamenti.

<li>Requisiti per l'allocazione trasversale
</li>
</ul>
   </td>
   <td>
<ul>

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Devops e integrazioni 
   </td>
   <td>Software e servizi per le organizzazioni di ingegneria che consentono loro di sviluppare, testare e consegnare più velocemente, in modo più efficiente e a costi inferiori. Include ambienti di sviluppo, controllo dei sorgenti, automazione della compilazione, integrazioni tra strumenti di ingegneria del software e strumenti di pubblicazione.
   </td>
   <td>
<ul>

<li>Numero di prodotti

<li>Frequenza di build e rilascio (CI/CD, CL, mensile, ecc.)

<li>Complessità dell'ambiente di sviluppo (numero di repository SC diversi, piattaforme di sviluppo, piattaforme di prodotto) 

<li>ambiente di sviluppo hosted/on-prem

<li>Dimensione e complessità dell'ingegneria SW (distribuita, numero di ingegneri SW e QA)

<li>Requisiti di sicurezza e conformità (politiche di sviluppo

<li>Requisiti di alta disponibilità (HA)
</li>
</ul>
   </td>
   <td>
<ul>

<li>Consentono di risparmiare sui costi/efficienza

<li>Time-to-market più rapido

<li>Esperienza utente fantastica 
     
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Strumenti I18N
   </td>
   <td>
<ul>

<li>Analisi statica: analizza il codice per trovare problemi I18N.

<li>Pseudo localizzazione: test software delle stringhe dell'interfaccia utente localizzate
</li>
</ul>
   </td>
   <td>
<ul>

<li>Sviluppate il codice?

<li>Vendete/distribuite codice al di fuori degli Stati Uniti (o della lingua sorgente locale)?

<li>Modello in-house vs. fornitore per il test di localizzazione
</li>
</ul>
   </td>
   <td>
<ul>

<li>Time-to-market più rapido

<li>Consentono di risparmiare sui costi/efficienza

<li>Esperienza utente fantastica 
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Test di localizzazione (da classificare con gli strumenti i18n di cui sopra, e forse devops)
   </td>
   <td>
<ul>

<li>Tracciamento dei bug: tracciamento degli errori di localizzazione nell'interfaccia utente. 

<li>Strumenti di cattura dello schermo, utilizzati per facilitare i test in locale quando l'accesso al software non è possibile.

<li>Strumenti per la creazione di casi di test, test sulla persona per garantire un'adeguata targettizzazione del pubblico.
</li>
</ul>
   </td>
   <td>
<ul>

<li>Volume di localizzazione dell'interfaccia utente

<li>Accesso all'ambiente software/hardware per i test

<li>Utenti come personas

<li>Risorse interne e risorse di test del fornitore
</li>
</ul>
   </td>
   <td>
<ul>

<li>Esperienza utente fantastica 

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Suite di gestione dei programmi
   </td>
   <td>Dashboard: si colloca sopra il TMS e altri strumenti di localizzazione come punto centrale per la gestione di tutto il lavoro di traduzione.
   </td>
   <td>
<ul>

<li>L'80% di tutto ciò che un PM deve fare/accedere/rivedere in un giorno in un'unica posizione.

<li>Stato del lavoro

<li>Dati sui costi per commessa e PO/stakeholder

<li>Dati sulla qualità

<li>Link ai principali archivi di contenuti
</li>
</ul>
   </td>
   <td>
<ul>

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Strumento interno di gestione delle risorse/tracciamento del tempo
   </td>
   <td>Pianificazione e gestione delle attività per le risorse interne con tracciamento delle ore di lavoro
   </td>
   <td>
<ul>

<li>Modello in-house vs. fornitore

<li>Numero di prodotti/progetti

<li>Numero di lingue/risorse interne

<li>Requisiti per l'allocazione trasversale
</li>
</ul>
   </td>
   <td>
<ul>

<li>Consentono di risparmiare sui costi/efficienza
</li>
</ul>
   </td>
  </tr>
</table>



## 


## Appendice B: Inventario dei dati 

Ecco un inventario di tutti i dati e le metriche che un globalization leader potrebbe voler raccogliere:

* Sito Web
    * Dati dei visitatori e delle sessioni
    * Conversioni e tasso di conversione 
    * Visite alla conversione
    * Download
    * Visualizzazioni della pagina
    * Tasso di rimbalzo
    * Dati suddivisi per Paese e lingua
    * Dati suddivisi per fonte, cioè SEO, SEM, organico
    * Livello di accettazione della MT non modificata (tramite sondaggio nella pagina)
    * Lingua del browser contro lingua della pagina. Se il sito permette di visualizzare le pagine in più lingue, tracciate se la frequenza di rimbalzo migliora quando un utente cambia la lingua
* Dati aziendali
    * Fatturato
    * Obiettivi di fatturato per regione
    * N. di clienti
    * N. di utenti nella regione (probabilmente usando una lingua diversa)
    * Dimensione dell'operazione (con le lingue coinvolte)
    * Costo dell'aggiunta/mantenimento di una lingua al prodotto, alla documentazione, al sito web, al marketing, alla formazione, ecc.
    * ASU (unità di servizio attive), unità vendute all'anno, ricavi per unità
    * TAM (Mercato totale indirizzabile per prodotti/linee di prodotto)
    * Servizi-contatti, costo medio del contatto per canale (telefono, chat, e-mail, ecc.), costo della spedizione di ricambi/assistenza
    * Tolleranza dell'inglese (English Proficiency Index-EPI)
    * Analisi del sentiment (per il prodotto e il marketing: si tratta di un set informativo di dati soft)
    * Ricerca di mercato e valutazione complessiva del rischio (rapporto governativo, leggibilità del prodotto, infrastruttura, spesa pubblicitaria digitale, ecc.)
    * Soddisfazione del cliente
* Dati di utilizzo
    * Utilizzo del prodotto, telemetria
    * Documentazione e dati di utilizzo della formazione sui prodotti
    * Feedback del cliente/Intervista/CSAT
    * Dati di analisi web 
* Dati operativi (misurazione dell'efficienza interna)
    * Spese di bilancio
    * ROI del team/organico
    * Dati di produzione dal TMS





