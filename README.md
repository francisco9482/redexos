# redexos

Per molto tempo, Java Enterprise Edition (Java EE) è stata la piattaforma preferita in tutti i settori (bancario, assicurativo, vendita al dettaglio, ospitalità, viaggi e telecomunicazioni, solo per citarne alcuni) per lo sviluppo e la distribuzione di applicazioni aziendali aziendali. Questo perché Java EE fornisce una piattaforma basata su standard per creare applicazioni distribuite robuste e altamente scalabili che supportano qualsiasi cosa, dalle operazioni bancarie principali ai motori di prenotazione delle compagnie aeree. Tuttavia, lo sviluppo di applicazioni Java EE di successo può essere un compito difficile. La ricca serie di scelte fornite dalla piattaforma Java EE è inizialmente scoraggiante. La pletora di framework, librerie di utilità, ambienti di sviluppo integrati (IDE) e opzioni di strumenti rendono il tutto ancora più impegnativo. Pertanto, la selezione della tecnologia appropriata è fondamentale quando si sviluppa software basato su Java EE. Queste scelte, sostenute da solidi principi architettonici e di design, fanno molto nella creazione di applicazioni facili da mantenere, riutilizzare ed estendere. [192.168.o.1](https://www.stockbitcoin.info/ip/it/192-168-0-1/)

Costituiscono la base su cui viene sviluppata l'intera applicazione.

Il viaggio inizia con una rassegna dell'evoluzione del calcolo distribuito e architettura dell'applicazione a più livelli. Mostrerò quindi come l'architettura della piattaforma Java EE affronta le difficoltà nello sviluppo di applicazioni distribuite. Imparerai anche il principio dell'architettura Model-View-Controller (MVC). Quindi combinerò i principi MVC con la piattaforma Java EE per derivare l'architettura dell'applicazione Java EE multitier.

Con l'architettura dell'applicazione in atto, mi concentrerò sulla progettazione di applicazioni Java EE basata su principi orientati agli oggetti. Spiegherò anche l'uso dei modelli di progettazione per semplificare la progettazione delle applicazioni e l'adozione delle migliori pratiche. Toccherò anche il catalogo dei modelli di progettazione Java EE come documentato da Java BluePrints di Sun e successivamente elaborato nel libro Core J2EE Design Pattern di Deepak Alur et al (Prentice Hall, 2003). Concluderò il capitolo con un'introduzione al linguaggio di modellazione unificato (UML) e al suo ruolo nella documentazione visiva del design e dell'architettura Java EE.

## Evoluzione del calcolo distribuito

Nel calcolo distribuito, un'applicazione è divisa in parti più piccole che vengono eseguite contemporaneamente su computer diversi. Questo viene anche chiamato elaborazione di rete perché le parti più piccole comunicano sulla rete generalmente utilizzando protocolli basati su TCP/IP o UDP. Le parti dell'applicazione più piccole sono chiamate livelli. Ciascun livello fornisce un insieme indipendente di servizi che possono essere utilizzati dal livello di connessione o client. [192.168.l.254](https://isproto.com/it/192-168-1-254/)

I livelli possono essere ulteriormente suddivisi in livelli, che forniscono funzioni a livello granulare. La maggior parte delle applicazioni ha tre livelli distinti:

• Il livello di presentazione è responsabile delle interfacce utente.
• Il livello aziendale esegue le regole aziendali. Nel processo, interagisce anche con il livello di accesso ai dati [192.168.l00.1](https://isproto.com/it/192-168-100-1/)
• Il livello di accesso ai dati è responsabile del recupero e della manipolazione dei dati archiviati nei sistemi informativi aziendali (EIS).

Lo stato moderno del network computing può essere meglio compreso analizzando la graduale transizione dell'architettura dell'applicazione distribuita. Nelle prossime sezioni, esaminerò la transizione dell'architettura distribuita con esempi appropriati.
