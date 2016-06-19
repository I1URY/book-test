% Diario in Codice @ Game Over Room
% Nicola Ariutti
% 20 Giugno 2016

# Introduzione

Innanzi tutto mi presento: mi chiamo Nicola e sono da sempre un grande appassionato di suono e di tecnologie informatiche. Dopo la maturità scientifica mi sono specializzato in ingegneria del suono coltivando la mia passione per la programmazione e per la musica. 

Assieme alla mia compagna Valentina mi dedico a tempo pieno al progetto [limulo.net](http://www.limulo.net/it/templates/main-menu.php), un sito internet e un raccoglitore di idee e approfondimenti attorno al suono, alla computer science, ai videogiochi e alle nuove tecnologie!

Il 19 Maggio i ragazzi del gruppo _Game Over_ hanno organizzato un incontro presso la Game Over Room al Leoncavallo a Milano, dandomi la possibilità di presentare il mio ultimo progetto: **Diario in codice**.

Durante l'incontro ho parlato del progetto ai presenti e abbiamo discusso assieme sugli argomenti e le tematiche ad esso associate. Con questo piccolo riassunto vorrei poter raccontare anche a te quanto è stato detto durante quella serata.
 
## Di cosa si tratta?

Il progetto si chiama **Diario in Codice**, è un libro/manuale per imparare le basi della programmazione, pensato per chiunque voglia cominciare a scrivere i propri programmi per computer. 

Il libro è autoedito, la sua realizzazione è stata supportata dai futuri lettori ed inoltre sarà rilasciato con una licenza di tipo permissiva (fra poco maggiori dettagli).

## Come nasce?

Da sempre, quando studio un nuovo argomento sono solito prendere appunti, scrivere su carta i concetti più importanti e fissare in parole i miei ragionamenti. Questo mi aiuta a memorizzare meglio i diversi aspetti della materia e a mettere in risalto i collegamenti che possono esserci tra varie discipline.

Da alcuni anni mi sono avvicinato al mondo della programmazione e, così facendo, ho raccolto un discreto quantitativo di materiale, tanto che mi sono chiesto: "Perchè non condividerlo? In fondo, se questo materiale è stato utile per me potrebbe esserlo anche per altri!"

Con la **condivisione** si vince sempre in due. Il primo a goderne è chi riceve che si può basare sull'opera altrui guadagnando in tempo e fatica. Al contempo ne gode anche chi dà perchè, così facendo, crea un legame con gli atri da cui può nascere un confronto construttivo. L'autore che condivide, ricevendo feedback dall'utente, può imparare nuove cose e ottenere utili consigli su come migliorare la propria opera.

## Perchè Diario?

Il libro nasce quindi da un'esperienza personale: _diario_ mi è sembrato il termine più adatto. La parola _diario_ mi rimanda anche al susseguirsi dei giorni, ad una sorta di percorso, come quello che si intraprende ogni qualvolta si voglia imparare qualche cosa di nuovo; un percorso alle volte lungo altre volte meno, ma fatto sempre di tanti piccoli passi, uno dopo l'altro.

## Perchè programmare?

Tanto per cominciare, perchè è facile! 

Oggigiorno non potrebbe esserci momento migliore per imparare a programmare: le risorse per potersi avvicinare a questo mondo sono veramente tantissime. 

La rete è di sicuro la risorsa più ricca: si possono trovare blogs, articoli e forums dedicati all'argomento.
Grazie poi al web 2.0, con il solo ausilio di un browser, si può imparare a programmare direttamente sul web in modo interattivo, facendo esercizi e verificado subito i propri progressi.

In aggiunta a tutto ciò ci sono gli strumenti software veri e propri (i programmi) da installare sul proprio computer che permettono di ampliare le possibilità offerte dal web di sperimentare e applicare quanto si sta apprendendo. Eccoti una breve lista, solo per citarne i principali: [Processing](https://processing.org/), [Python](https://www.python.org/), [Scratch](https://scratch.mit.edu/) e [Arduino](https://www.arduino.cc/)). Ne parleremo meglio tra poco, ma è bene accennarlo fin da subito: la maggiorparte di questi strumenti sono **liberi**!

Infine, come non citare i libri; la rete è anche un vastissimo raccoglitore di informazioni su autori e pubblicazioni su qualsiasi aspetto legato alla programmazione.
Insomma, come puoi vedere siamo ormai immersi in una miriade di possibilità, adatte a qualsiasi gusto e preferenza.

Programmare ci fa capire fondamentalmente questo:

> [...] i computer sono [...] stupidi. A differenza degli esseri umani, possiedono la sincera e profonda stupidità degli oggetti inanimati.

E' una frase di Bruce Sterling, scrittore e giornalista statunitense che si occupa di tecnologia e informatica e non solo. La frase è tratta dal suo libro _Giro di vite contro gli hackers_ del 1992 ^[Bruce Sterling, "**Giro di Vite contro gli hackers**", Mondadori 2004. Titolo originale dell'opera "The Hacker Crackdown";].

Un'affermazione forte e chiara: il computer è una macchina stupida! Per quanto mi riguarda, fino a qualche tempo fa non avevo un'opinione in merito: ero solito lavorare al computer senza conoscerlo più di tanto. Mi bastava usarlo solo come strumento per le mie esigenze quotidiane, interagendo non più dell'indispensabile. 

Programmare ti insegna ad usare il computer in modi nuovi, ad esserne padrone e sfruttarlo a fondo. Quando l'ho scoperto è stato come accorgersi che la propria _cassetta degli attrezzi_ non conteneva soltanto un semplice martello, ma che al suo interno potevo trovare anche un intero set di cacciaviti, alcune pinze, chiavi, brugole e così via.

Il computer è una macchina dalle enormi potenzialità ma che - come dice Sterling - non sa che cosa fare. Se il computer fa qualcosa, lo fa soltanto perchè qualcuno gli ha spiegato **come** farlo, lo ha istruito, gli ha fornito delle istruzioni: in altre parole lo ha programmato.

Ci sono molti modi diversi per fornire istruzioni al computer, ma tutti condividono tra loro un set di regole di base, una sorta di **ABC**, gli stessi fondamenti che esamineremo a fondo durante il nostro percorso.

Hai mai avuto bisogno di completare un lavoro, magari nulla di troppo complicato, per il quale il computer di sicuro ti sarebbe stato d'aiuto e di dover constatare che:

1. il programma per computer che ti avrebbe fatto comodo non esisteva?
2. pur esistendo, il programma non funzionava sul tuo computer o non era nemmeno disponibile per il tuo sistema operativo?
3. pur disponibile e funzionante, avresti dovuto acquistarlo a caro prezzo e sottoscrivere una licenza d'uso molto restrittiva?

Ognuno di questi possibili scenari costituisce una barriera per colpa della quale il nostro lavoro è reso inutilmente più complicato o oneroso. 

E' solo un piccolo esempio ma è sufficiente a mostrare come proprio in simili situazioni l'_ABC_ di cui abbiamo parlato potrebbe essere d'aiuto. Conoscendo l'_ABC_, possiamo essere noi ad istruire il computer perché risolva il nostro problema al posto nostro.

Scrivere noi stessi i nostri programmi ci libera da ogni barriera, siamo liberi di fare potenzialmente tutto quello che ci passa per la testa (con il computer almeno).

Un'altra cosa che ho imparato grazie alla programmazione è che gli strumenti che siamo soliti utilizzare sul computer ogni giorno, sono di solito delle _scatole opache_, dei contenitori _chiusi_ ermeticamente.

Per noi non è possibile guardare al loro interno nè per soddisfare una nostra eventuale curiosità sui loro meccanismi di funzionamento nè tantomeno per modificarli in modo da adattarne il comportamento alle nostre esigenze.

A ben pensarci è come se la nostra automobile avesse il cofano motore completamente saldato al resto della carrozzeria: sarebbe impossibile aprirlo per sbirciare il movimento delle varie parti meccaniche, proprio come sarebbe impossibile intervenire per ripararlo in caso di guasto.

Perchè non si dovrebbe poterlo fare, mi chiedo? 

Fortunatamente, esistono moltissimi altri programmi progettati e rilasciati in modo che _ci si possa guardare dentro_. Questi programmi rispettano l'utente e garantiscono una maggiore libertà. 

Si tratta di strumenti che lasciano la possibilità non solo di esaminarli in profondità ma anche di agire sul loro comportamento, modificandone alcune istruzioni o aggiungendone di nuove. 

Questi programmi sposano la filosofia del **software libero** secondo la quale la condivisione (in questo caso delle istruzioni che costituiscono il programma), non può che migliorare il programma stesso, la nostra esperienza d'uso del computer e la nostra libertà come individui.

In passato (si parla dei primi anni '50) i computer non solo erano macchinari giganteschi, grandi quanto armadi che occupavano intere stanze, ma erano anche pochissimi, disseminati per lo più presso alcune università e i pochi istituti di ricerca che potevano permetterseli. 

Questi computer erano davvero molto particolari e dal funzionamento molto complesso; scrivere programmi per queste macchine era infinitamente più difficile rispetto ad oggi. Per fortuna, però, all'epoca il software era libero: i programmatori condividevano liberamente le proprie idee e intuizioni, i propri ragionamenti e allo stesso modo anche i propri programmi.

Per le aziende produttrici di hardware, il fatto che i ragionamenti e le intuizioni dei programmatori tradotte in codice si diffondessero, non costituiva un problema. D'altra parte, un programma scritto per uno di quei computer non avrebbe mai potuto funzionare su nessun altro: i meccanismi e le peculiarità di ciascuno li rendevano assolutamente incompatibili tra loro.

In seguito l'hardware cominciò ad uniformarsi, il computer si fece sempre più _personal_ ed entrò gradualmente nelle vite di un numero sempre crescente di persone. L'hardware, non più così diverso da computer a computer, permetteva ad un programma di funzionare molto più facilmente su macchine diverse e, quindi, di diffondersi in modo più rapido.

La vecchia abitudine dei programmtori di scambiarsi informazioni e condividere le istruzioni dei propri programmi stava ora diventando una minaccia per quelle stesse aziende che avevano appoggiato tale pratica in passato.

Con il progressivo calo di prezzo dell'hardware le aziende videro nel software il loro prossimo _core business_. Fu in questo momento storico che cominciarono a imbrigliare la libertà precedentemente accordata, dotando i software di licenze restrittive e perseguendo legalmente ogni abuso.
 
Il cambio di direzione colpì profondamente chi aveva sempre vissuto nello spirito di condivisione. Molti programmatori si trovarono in breve tempo imprigionati in una forzatura priva di senso, nociva per la libertà così come per la cultura. 

In questo frangente prese forma e vennero formalizzati i principi della filosofia del **software libero** ad opera di Richard Stallman.

## Libertà

> Se un programma mi piace lo devo condividere con altre persone cui piace.
<br/><span class="autore">da una mail di Richiard Stallman datata 27 Settembre 1983.</span>

Richard Stallman è un informatico statunitense, attivista e fondatore del progetto [GNU](https://www.gnu.org/) e della [Free Software Foundation](https://www.fsf.org/), organizzazione no-profit che supporta il movimento software libero. 

Tale movimento promuove l'universale libertà di studio, di distribuzione, creazione e modifica del software per computer. Se vuoi farti un'idea più completa a riguaro ti consiglio caldamente il libro _Software Libero, Pensiero Libero_ ^[Richard Stallman, "**Software Libero, Pensiero Libero**", Nuovi Equilibri, 2003. Titolo originale dell'opera: "Free Software, Free Society: The Selected Essays of Richiard M. Stallman";].

Dalla sua nascita, la filosofia del software libero e le idee da questa promosse si sono diffuse enormemente raggiungendo e influenzando tutti i campi delle arti e del sapere umano, non soltanto il mondo del software. 

Basta fare una veloce ricerca su Wikipedia per rendersi conto di quante siano oggi le declinazioni di questa filosofia di condivisione e di apertura. Eccoti solo alcuni esempi:

* [open content](https://en.wikipedia.org/wiki/Open_content) (un neologisno che descrive perfettamente quanto abbiamo appena detto e si usa per descrivere un lavoro creativo che altri possono copiare o modificare);
* [open learning](https://en.wikipedia.org/wiki/Open_learning) (si riferisce all'ampliamento e al potenziamento delle opportunità di imparare, sia tramite i sistemi tradizionali sia attraverso metodi interattivi basati sulle nuove tecnologie vedi, ad esempio, questi altri due termini interessanti, [OER](https://en.wikipedia.org/wiki/Open_educational_resources) e [MOOC](https://en.wikipedia.org/wiki/Massive_open_online_course));
* [open data](https://en.wikipedia.org/wiki/Open_data) (l'idea che anche i dati dovrebbero essere liberamente disponibili per chiunque e accessibili senza restrizioni di copyright, brevetti o meccanismi di controllo);
* [open acces](https://en.wikipedia.org/wiki/Open_access) (il termine applicato a tutti quegli articoli scientifici e risultati delle ricerche scientifiche che vengono rilasciati liberi da tutte le limitazioni d'accesso e liberi anche da molte delle restrizioni sul loro utilizzo);
* [open publishing](https://en.wikipedia.org/wiki/Open_publishing) (il processo di creazione di notizie o altri contenuti in modo trasparente per i lettori; un esempio su tutti è la stessa Wikipedia).

Restando in tema di apertura e condivisione, ti sarà di certo capitato di imbatterti in un simbolo come quello mostrato qui sotto

![Un tipico simbolo di una licenza Creative Commons](./illustrations/license-by-sa.png)

Si tratta del tipico simbolo che caratterizza una particolare tipologia di licenza chiamata **Creative Commons**. 

Prima ancora però, [Creative Commons](https://creativecommons.org/) è il nome dell'organizzazione no-profit fondata nel 2001 dal giurista statunitense Lawrence Lessig, la cui missione è quella di ampliare il numero di opere disponibili per la condivisione e l'utilizzo libero. 

Tutto questo è possibile grazie alla licenza omonima, lo strumento legale che Lessig ha creato appositamente strizzando l'occhio al movimento del software libero.

Creative Commons è il sistema, relativamente nuovo, che chiunque può utilizzare per licenziare il proprio lavoro e tutelare così i propri diritti sull'opera garantendo al contempo all'utente un certo grado di libertà nell'uso.

Sei musicista? Disegnatore, pittore, scrittore? Stai per pubblicare il tuo prossimo articolo? Magari un modello 3D oppure una bella fotografia? Potresti considerare di licenziare la tua opera con licenza Creative Commons, chiara, modulare e semplicissima. Dai un'occhiata al [tool disponibile on-line](https://creativecommons.org/choose/)! 

Così facendo permetterai agli altri di godere del tuo lavoro senza però perdere i tuoi diritti, innescando il così detto **circolo virtuoso** per liberare la cultura. A tale scopo ti consiglio caldamente il libro di Lessig intitolato _Cultura libera_^[Lawrence Lessig, "**Cultura Libera**", Apogeo 2005. Titolo originale dell'opera: "Free Culture";], praticamente il manifesto del Creative Commons! 

>Chi ricava una idea da me, ricava conoscenza senza diminuire la mia: come chi accende la sua candela con la mia riceve luce senza lasciarmi al buio.
<br/><span class="autore">Thomas Jefferson</span>

Ecco giusto un'altra frase secondo me interessante che riassume brevemente i principi di cui abbiamo discusso. Perchè ti annoio con tutto questo discorso sulla libertà e sulla condivisione? Presto detto: il libro _Diario in codice_ sarà rilasciato proprio con una licenza di questo tipo, nello specifico una licenza denominata [Creative Commons Attribuzione - Condividi allo stesso modo 4.0 Internazionale](http://creativecommons.org/licenses/by-sa/4.0/). 

Che cosa per metter di fare questa licenza? Con questa licenza il lettore, a patto di attribuire sempre all'autore la paternità dell'opera originale, sarà libero di condividere e ridistribuire copie del materiale attraverso quasiasi mezzo o formato, sarà libero inoltre di trasformare e adattare l'opera a propria discrezione a patto soltanto che il risultato, se ricondiviso, venga distribuito usando la stessa licenza dell'originale.

## Il libro

Con _Diario in codice_ mi piacerebbe condividere quanto ho appreso sulla programmazione. Le tematiche che andremo ad esaminare potrebbero a prima vista sembrare un po' astratte. Per questo ho pensato di affiancare al nostro percorso uno strumento per restituire maggiore concretezza: si tratta di [Arduino](https://www.arduino.cc/).

Se non lo conosci, Arduino è una piccola scheda elettronica, grande quando una carta di credito. Può essere collegata al nostro computer attraverso un semplice cavo USB e usata per ampliarne le capacità. 

Grazie ad Arduino il nostro computer sarà in grado di captare stimoli provenienti dal mondo esterno come l'umidità dell'aria, l'intensità luminosa o la forza meccanica attraverso diversi tipi di sensore.

Inoltre, grazie alla scheda, il computer sarà anche in grado di inviare segnali verso l'esterno, interagendo con il mondo fisico tramite dispositivi detti attuatori (led, motorini elettrici, piccoli altoparlandi o schermi LCD).

Se da un lato occorrerà imparare qualche nozione di base di elettrotecnica (_Diario in codice_ parlerà anche di questo), dall'altro vedremo come la piattaforma Arduino sia l'ideale per comprendere l'importanza dei programmi che in questo caso ci permetteranno di interagire direttamente con il mondo reale! 

Ciliegina sulla torta: il progetto Arduino è perfettamente allineato alla filosifia di libertà che ci sta tanto a cuore! Per di più Arduino ci fa conoscere due nuovi termini interessanti ovvero [open hardware](https://en.wikipedia.org/wiki/Open-source_hardware) e [open design](https://en.wikipedia.org/wiki/Open_design): i progetti e i disegni delle schede Arduino sono licenziati con licenza Creative Commons e permettono liberamente a chiunque disponga dei mezzi di produrle o crearne versioni alternetive.

## Selfpublishing

Dopo aver raccolto e dato forma a tutti i miei appunti sulla programmazione mi sono chiesto: come si fa a pubblicarli?

A quel punto mi è tornato alla mente [Daniel Shiffman](http://shiffman.net/) (un simpatico docente statunitense) e il suo progetto [Nature of Code](http://natureofcode.com/), un libro che lo stesso Shiffman ha pubblicato in seguito al successo di una campagna di raccolta fondi on-line. Anche io ho partecipato a quella campagna dando il mio contributo e ricevendo infine il libro. 

Mi sono ricordato che in quella circostanza l'autore aveva deciso di non rivolgersi ad un editore ma di provvedere autonomamente alla pubblicazione del proprio lavoro.

Da quanto ho potuto capire in questi mesi, il percorso di pubblicazione tradizionale prevede che l'autore si rechi presso un editore con il proprio manoscritto e glielo sottoponga per un esame. 

L'editore è colui che dispone dei mezzi tecnici per riprodurre l'opera e distribuirla capillarmente presso librerie e negozi sul territorio nazionale e non solo.

L'editore inoltre ha facoltà di agire attivamente sull'opera, modificandone in parte il contenuto e la struttura a propria discrezione.  Nella maggiorparte dei casi, egli applica all'opera una licenza tradizionale, del tipo _tutti i diritti riservati_. 

Seguire l'esempio di Shiffman mi avrebbe invece garantito il pieno controllo sul contenuto del mio libro; nelle mani di un editore esperto la gran mole di lavoro sarebbe stata velocizzata, ma mi sono reso conto che pubblicare autonomamente mi avrebbe permesso di applicare al libro la licenza permissiva con la quale volevo rilasciarlo.

E' stato così che ho scoperto il **self-publihshig** (o autoedizione in italiano): esistono una miriade di aziende on-line che mettono al servizio degli autori professionalità e strumenti per la stampa, vedita e distribuzione delle opere editoriali, e che, senza entrare nel merito dei contenuti, garantisco una grande autonomia ed indipendenza. 

Stando almeno alle informazioni che ho raccolto finora, quando si decide di pubblicare utilizzando uno di questi servizi di self-publishing, non è prevista alcuna esclusiva, per cui è possibile stampare e vendere il proprio libro usando contemporaneamente anche qualche altro servizio.

Ecco una lista delle principali piattaforme di selfpublishing:

* [Streetlib](https://www.streetlib.com/it/) (una piattaforma italiana fondata nel 2007, quella che userò per pubblicare il libro);
* [ilmiolibro](http://ilmiolibro.kataweb.it/pubblicare-un-libro/) (communuty italiana di lettori e scrittori, che si occupa anche di selfpublishing);
* [youcanprint](http://www.youcanprint.it/) (altra piattaforma di selfpublishing italiana);
* [lulu.com](https://www.lulu.com/it) (curiosità: nata in Canada nel 2002 ad opera di uno dei cofondatori del progetto RedHat, una particolare distribuzione del sistema operativo _GNU/Linux_, profondamente legato a quanto detto in merito al software libero);
* [pixalib](http://www.pixalib.com/it/) (specializzata soprattutto in libri di architettura e d'arte, libri che fanno ampio uso di immagini e grafiche);
* [createSpace](https://www.createspace.com/) (il servizio di self publishing di Amazon, lo stesso usato da Shiffman per il progetto _Nature of Code_);
* [Kindle Direct Publishing](https://kdp.amazon.com/signin) (la piattaforma di selfpublishing associata al famoso ereader di Amazon);
* [Kobo Writing Life](https://www.kobo.com/writinglife) (come la precedente ma associata all'ereader Kobo);

_Diario in Codice_ sarà pubblicato in formato digitale (ePub): sembra un'opzione davvero interessante e senz'altro sarà un esperimento molto istruttivo!

### DRM

Una cosa che purtroppo segue da vicino i prodotti digitali è il DRM, ovvero il sistema di controllo dei diritti digitali. Ogni file musicale che acquistiamo, ogni videogioco che downloadiamo da internet, ogni trasmissione video in streaming, così come ogni eBook che leggiamo è potenzialmente equipaggiato con uno di questi sistemi di controllo. 

Si tratta in pratica di piccoli programmi informatici inclusi all'interno dei file che gli stessi produttori inseriscono appositamente per controllarne l'uso da parte dell'utente.

Giusto per fare un esempio, i dispositivi DRM sono quelli che, nel caso di un libro in formato digitale, impediscono all'utente di trarne alcuni estratti attraverso il copia-incolla, oppure impediscono di crearne copie, fosse anche per la sola archiviazione di backup, oppure ancora ne obbligano la lettura soltanto su una specifica marca di lettori ereader.

L'uso dei sistemi DRM, introdotti dai distributori per preservare i diritti d'autore, non è accettato universalmente. I DRM superano talvolta i limiti della legalità, minando la libertà degli utenti e invadendone la privacy, riducendosi ad essere _manette digitali_, [come è li definisce lo stesso Stallman](https://www.mixcloud.com/francesco-luvisin/popolinux-missione-richard-stallman-monza-audio-completo/).

Prima dell'avvento di internet nessuno disponeva dei mezzi tecnici per creare copie: chiunque all'epoca avesse voluto condividere con l'amico il libro che stava leggendo, avrebbe dovuto privarsene per darglielo in prestito. 

Al giorno d'oggi, con la tecnologia di cui disponiamo, potremmo tranquillamente condividere la nostra esperienza con moltissime altre persone senza per questo interrompere la nostra fruizione; è l'immediatezza di un semplice gesto, basta fare un click e la copia è fatta!

Tutti questi sistemi DRM cercano di impedirlo, trasponendo nel presente e nel prossimo futuro le stesse difficoltà tecniche appartenenti ad un'epoca passata e annullando di fatto tutti i vantaggi che derivano dall'uso delle moderne tecnologie; ostacolando in altri termini la diffusione libera delle idee e della cultura.

Personalmente trovo che tutto questo suoni molto anacronistico: se una tecnologia comporta dei miglioramenti e dei vantaggi per tutti, perchè limitarla? Perchè non sfruttarla completamente? Evidentemente le logiche del profitto hanno la meglio in queste situazioni.

Se l'utente è consapevole della tecnologia che sta utilizzando è giusto che ne possa godere; questi sistemi di limitazione sembrano sottovalutare presuntuosamente l'intelligenza delle persone e considerare invece solo l'ottica di mercato per cui le esperienze dello scambio e della fruizione vengono limitate o eliminate perchè non se ne possa trarre profitto.

Nel rispetto di quanto abbiamo detto fino ad ora in merito alla libertà della cultura e della condivisione, cercherò, a tal proposito, di valutare attentamente quali canali di distribuzione utilizzare per metter in vendita il foramto ebook del mio libro. 

Possibilmente dovrò capire quali di questi canali pretendano l'applicazione di sistemi proprietari di controllo dei diritti e quali invece risultino essere più permissivi. 

Un altro punto di merito per StreetLib è il fatto che permette di usare un canale di distribuzione che richiede l'applicazione di un DRM cosìdetto _soft_ o _watermark_; una sorta di DRM non particolarmente molesto e che non dovrebbe limitare in alcun modo la libertà dell'utente nella fruizione dell'opera!

## Crowdfunding

Poco fa abbiamo parlato di Daniel Shiffman e del suo libro non solo autoedito ma anche finanziato da una campagna di raccolta fondi attraverso la rete.

Quando ho deciso di pubblicare ho deciso di provare anche io questa nuova modalità di finanziamento: **crowdfunding** è il termine che si usa, tradotto letteralmente in finanziamento dalla folla. Chiunque abbia un'idea per la testa o un progetto da realizzare può utilizzare questo strumento per rivolgersi direttamente a propri potenziali sostenitori tramite internet, e raccogliere così i loro contributi.

Avendo partecipato più volte a diverse campagne di crowdfunding in passato, passando da progetti editoriali a videogames a documentari e films, credo che sostenere i nostri progetti preferiti sia estremamente importante. 

Sostenere è da una parte un modo per supportare l'autore del progetto, non solo da un punto di vista economico.
Dare il proprio contributo è un po' come stringergli la mano, incoraggiarlo nel continuare il proprio lavoro, fargli capire che è sulla strada giusta e che ci sono persone che condividono e apprezzano il suo impegno. 

Allo stesso tempo è un modo per diventare parte integrante del progetto stesso dato che è anche grazie al nostro aiuto che il progetto ha potuto vedere la luce. Sostenendo diventiamo co-produttori dell'opera, una cosa di cui andare fieri!

Eccoti un lista delle principali piattaforme di crowdfunding sulle quali ho avuto modo di informarmi in questi mesi:

* [Produzioni Dal Basso](https://www.produzionidalbasso.com/) (fondata nel 2005 è stata la prima piattaforma italiana di crowdfunding, la piattaforma che ho scelto per il mio libro);
* [Kickstarter](https://www.kickstarter.com/) (americana nata nel 2009 e da poco disponibile anche per progettisti italiani);
* [Indiegogo](https://www.indiegogo.com/) (nata nel 2008, americana);
* [MusicRaiser](https://musicraiser.com/) (credo americana anche questa, nata nel 2012 e specializzata in progetti di tipo musicale);

Scelta la piattaforma, si è trattato di quantificare il budget da raggiungere, considerando non solo i costi per la stampa e distribuzione, ma anche quelli per la realizzazione delle ricompense per i sostenitori, preparare i contenuti testuali e video e avviare la campagna. 

Ad oggi, dopo 2 mesi e a campagna ultimata, abbiamo raggiunto un buon risultato, raccogliendo una somma che, seppur non mi consentirà di portare a termine tutto quello che avevo in mente, mi permetterà comunque di completare il libro, di pubblicarlo e renderlo disponibile per tutti.

Un ringraziamento speciale va a tutti coloro che hanno creduto nel mio progetto e per questo hanno sostenuto la campagna di crowfdunding.

## Note {#note}

Il libro sarà realizzato usando interamente strumenti liberi. Eccoti un elenco dei principali strumenti che sto usando:

* [LibreOffice](https://www.libreoffice.org/) - una suite per l'ufficio interamente libera;
* [GIMP](http://www.gimp.org/) ed [InkScape](https://inkscape.org/de/) - due potenti software per la manipolazione dell'immagine;
* [Scribus](https://www.scribus.net/) - software che fornisce strumenti di precisione per la stampa;
* [Calibre](http://calibre-ebook.com/) - potente programma per la gestione della propria libreria di eBook e per la conversione di files;
* [Pandoc](http://pandoc.org/) - potentissimo convertitore di files;

Mi preme sottolineare che si tratta di strumenti liberi, che rispettano cioè la filosofia di cui ti ho parlato poco fa. Li conosci? Li hai mai usati? Provali! Fai click sui link della lista per raggiungere le rispettive pagine web. 

Viva il software libero!
