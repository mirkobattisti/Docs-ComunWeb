
.. _h6e4d39105a64461f4f3377d353919:

Accesso al sistema
******************

Per accedere al sistema è necessario spostarsi in fondo alla pagina per trovare, vicino alle indicazioni sul Copyright, il link “Accedi con il tuo account”

\ |IMG1|\ 

Una volta effettuato l’accesso, si vedono i link “Profilo utente” (dove è possibile modificare i propri dati e la propria password), agli strumenti a disposizione, e per uscire dal sistema.

\ |IMG2|\ 

.. _h1f184e272f67487d30753a697b3c5351:

Gestione dei contenuti
**********************

Una volta effettuato l’accesso al sistema, si vedrà comparire in alto, la barra degli strumenti, che consente di operare sui contenuti del sito.


.. admonition:: L’albero dei contenuti

    Nel sistema Open City, i contenuti sono organizzati in una struttura ad albero. Ogni contenuto ha una sua collocazione nell’albero dei contenuti. Questo va tenuto in considerazione quando viene creato un nuovo contenuto, perché esso va creato nella posizione corretta all’interno di un albero. Fanno eccezioni le immagini, che idealmente vengono create in un unico contenitore (Media/Images) per poter poi essere riutilizzate all’interno dei contenuti del sito.

.. _h7c2b7466704f1f106c504a672c3d3750:

La barra degli strumenti
========================

La barra degli strumenti consente di disporre delle funzionalità di \ |STYLE0|\  direttamente sulle pagine del sito (senza bisogno di accedere all’interfaccia di amministrazione). In questo modo è possibile navigare il sito come un normale visitatore, e operare modifiche a contenuti esistenti, spostamento di contenuti, ordinamenti, creazione di nuovi contenuti.

.. _h80796f6531d141926653d426622443a:

\ |IMG3|\ ----------

\ |STYLE1|\ 


..  Important:: 

    Le azioni che è possibile svolgere attraverso l’uso della barra degli strumenti \ |STYLE2|\  in quel momento: ad esempio se si sta visualizzando un contenuto di tipo “Avviso” e si clicca sull’icona con la matita (modifica), verrà modificato esattamente quel contenuto, la stessa cosa vale per la creazione di nuovi contenuti, la cancellazione, e così via.

Le funzionalità principali che è possibile operare dalla barra degli strumenti sono:

* \ |STYLE3|\ 

* \ |STYLE4|\ 

* \ |STYLE5|\ : come visto in precedenza, ogni contenuto del sito ha una collocazione in una struttura ad albero. Questa funzionalità consente di rendere uno stesso contenuto visibile in più sezioni del sito;

* \ |STYLE6|\  prima di cancellare un contenuto, il sistema chiede conferma. Inoltre, è possibile fare in modo che il contenuto venga messo nel cestino, in modo che sia possibile recuperarlo eventualmente;

* \ |STYLE7|\  da una collocazione a un’altra all’interno dell’albero dei contenuti;

* \ |STYLE8|\  posizionandosi su un contenuto, è possibile definire la modalità di ordinamento dei contenuti “figli” (per nome, data di creazione, priorità, …);

* \ |STYLE9|\  è possibile caricare dei files dal proprio pc (immagini, documenti pdf), che vengono convertiti in contenuti (seguendo una mappatura file/contenuto definita a livello di configurazione);

* \ |STYLE10|\  nel caso in cui il menù non mostra le modifiche apportate, è possibile forzare un refresh della visualizzazione del menù stesso;

* \ |STYLE11|\  per copiare un contenuto;

* \ |STYLE12|\  per accedere all’interfaccia di amministrazione e guardare “dietro le quinte”;

* \ |STYLE13|\  consente di tradurre un contenuto;

* \ |STYLE14|\  apre (o chiude) il box con informazioni sul contenuto che si sta visualizzando (data di creazione,  autore, tipologia di contenuto, …)

.. _h20112a6435232c2ee1a474074635b31:

Modifica di un contenuto esistente
==================================

Per modificare un contenuto esistente, è sufficiente \ |STYLE15|\  attraverso i menù e i link del sito, esattamente come farebbe un visitatore. Una volta raggiunto il contenuto da modificare, \ |STYLE16|\  e si passa alla modalità di modifica del contenuto: viene mostrata l’\ |STYLE17|\ , \ |STYLE18|\  di quel particolare contenuto.

Ad esempio, modificando un oggetto di tipo “Avviso”, l’interfaccia sarà basata sugli attributi della classe “Avviso”.

\ |IMG4|\ 

\ |STYLE19|\  \ |STYLE20|\ 

.. _h2c316b717f547316a522c1143139e:

Creazione di un nuovo contenuto
===============================

La creazione di un contenuto avviene nel seguente modo:

Si naviga il sito fino a raggiungere il contenitore all’interno del quale si vuole creare il contenuto, ad esempio un calendario:

\ |IMG5|\ 

Dalla tendina nella barra degli strumenti (1), è possibile filtrare le tipologie di contentuo (2) e  selezionare il tipo di contenuto da creare (3). Infine si preme sul pulsante Crea qui (4):

\ |IMG6|\ 

\ |STYLE21|\  \ |STYLE22|\ \ |STYLE23|\ 

Una volta effettuate queste operazioni, il sistema presenta una interfaccia identica a quella di modifica di un contenuto, con la differenza che i campi (attributi) saranno tutti vuoti.


.. admonition:: Attributi obbligatori

    Nelle interfacce di creazione e modifica dei contenuti, alcuni degli attributi sono marcati con un asterisco. Questo significa che è obbligatorio compilare quegli attributi.

.. _h2939163554334774451b95757d5c2a:

Il menù principale
******************

Il menù principale viene gestito modificando la home page del sito. Bisogna quindi navigare verso la Home page, e poi premere sull’icona “Modifica” della barra degli strumenti.

\ |IMG7|\ 

Si apre l’interfaccia di modifica della Home page, che è di tipo “Homepage”.  Spostandosi verso il basso, si incontra l’attributo che consente di gestire il menu principale. Da qui è possibile ordinare le voci esistenti (1), cancellare alcune delle voci esistenti (2,3), aggiungere contenuti che diventeranno voci di menù in modalità sfoglia (4) o ricerca (5).

\ |IMG8|\ 

Nel menù vengono aggiunti di fatto dei link a contenuti già esistenti nel sito (e collocati nell’albero dei contenuti). Quindi il testo che compare nel menù è quello relativo ai nomi dei contenuti che sono stati aggiunti.


.. admonition:: Refresh dei menu

    Dopo aver apportato una modifica al menù, o ai contenuti che fanno parte del menù, potrebbe essere necessario effettuare un refresh dei menu per rendere effettive le modifiche. Questa operazione è possibile attraverso la funzione “refresh menù” presente nella barra degli strumenti. 

.. _h112e363548804723d644a25d2e5020:

Organigramma
************

Per gestire un organigramma in un sito basato su Open City è necessario creare un oggetto di tipo “Organigramma”. La visualizzazione è gestita partendo da una serie di oggetti e dalle relazioni che intercorrono tra di loro.

Tipicamente, nella struttura dei contenuti, sono presenti i seguenti contenitori

* Aree: contiene oggetti di tipo “Area”, che rappresentano le aree nelle quali è divisa l’organizzazione dell’ente.

* Servizi: contiene oggetti di tipo “Servizio”, che rappresentano i Servizi operanti all’interno dell’ente.

* Uffici: contiene oggetti di tipo “Ufficio”, che rappresentano gli uffici fisici dell’ente.

Ogni ufficio contiene un riferimento ad un servizio, ed ogni servizio contiene un riferimento ad un area. Attraverso questi riferimenti viene costruito l’albero che compare nell’organigramma.

\ |IMG9|\ 

\ |STYLE24|\ 

Potrebbero esserci casi (enti di piccole dimensioni) in cui non ci siano tre livelli organizzativi, in quel caso l’organigramma può essere generato seguendo i collegamenti tra servizi e uffici.

\ |IMG10|\ 

\ |STYLE25|\ 

Una volta inserite le Aree, I Servizi e gli Uffici, posizionarsi sul nodo dell’Organigramma, aprire le informazioni per l’editor con l’icona “i” in alto a destra sulla barra degli strumenti, e poi premere il pulsante “aggiorna organigramma”:

\ |IMG11|\ 


.. admonition:: Suggerimento

    Se la pressione del pulsante “aggiorna organigramma” non dovesse sortire l’effetto desiderato, provare a modificare il contenuto di tipo organigramma (premendo l’icona con la matita sulla barra strumenti) e poi salvare senza apportare modifiche. Una volta usciti dalla modalità di modifica, premere nuovamente il pulsante “aggiorna organigramma”.

.. _h642e1439c702c7635643e1d7545d59:

Pagina del sito e visualizzazione dei figli
*******************************************

La tipologia di contenuto più generica è la “Pagina del sito”. Viene utilizzata per contenuti generici, non molto strutturati, oppure come contenitore di contenuti. Una volta inseriti i contenuti dentro una pagina del sito, è possibile selezionare il tipo di visualizzazione da applicare ai figli: questo offre diverse possibilità a seconda dello scopo della pagina.

Ad esempio è possibile Creare una pagina del sito per mostrare un elenco di strutture di servizio dislocate sul territorio, strutturando i contenuti come segue:

* Servizi sul territorio [Pagina del sito]

    * Centro educazione ambientale [Punto di interesse]

    * Farmacia XX [Servizio sul territorio]

    * Biblioteca Comunale [Servizio sul territorio]

    * Parafarmacia [Servizio sul territorio]

    * …

La visualizzazione degli oggetti “figli” di una pagina del sito è impostata di default “lista”, ma è possibile scegliere tra diverse altre modalità: modificando la pagina (icona con la matita sulla barra degli strumenti), tra gli attributi della pagina si trova, in fondo, l’attributo “visualizzazione dei figli”

\ |IMG12|\ 

Le scelte possibili sono:

* \ |STYLE26|\  - la visualizzazione a lista;

* \ |STYLE27|\  -  una visualizzazione a tabella con informazioni minime su ogni contenuto;

* \ |STYLE28|\  - sulla destra vengono proposti dei filtri per effettuare delle ricerche sui contenuti (un filtro per ogni tipologia di contenuto) utile in caso di gran numero di contenuti dello stesso tipo;

* \ |STYLE29|\  - i contenuti “figli” vengono mostrati su una mappa (sulla mappa vengono mostrati solo gli oggetti per cui è stata specificata una geolocalizzazione);

* \ |STYLE30|\  - vengono mostrati dei pannelli, uno per contenuto;

* \ |STYLE31|\  - i contenuti vengono mostrati con dei pannelli, ma vicino al titolo viene mostrata una icona.

\ |IMG13|\ 

\ |STYLE32|\ 

.. _h1c7c136469373a66106eff3c436153:

La scelta delle immagini
========================

Immagini a buona risoluzione

Preferibilmente che si sviluppano in orizzontale 

Attenzione alle licenze

* Concetto di classi di contenuto

* Funzionamento del menu del sito (+ cache menu)

* Funzionamento Website toolbar

* Organigramma

* Pagina del sito e varie viste per i figli

* Frontpage e blocchi principali

* Come pubblicare una news

* Come pubblicare una determina

* Galleria immagini

* Folder virtuale

* Come funziona la colonna di destra

* Creazione ruoli dipendenti con openpa/roles

* Area tematica (esempi?)

* Consigli sugli allegati (file_pdf)

* Scadenze automatiche dei contenuti

* CSVimport

* opendata/console/1

Scadenze automatiche dei contenuti

    con  le sezione e con gli stati

    funzionamento degli allegati (file_pdf) e delle gallerie di immagini

    visualizzazione dei figli

Gestione delle traduzioni


.. bottom of content


.. |STYLE0| replace:: *content management*

.. |STYLE1| replace:: *La barra degli strumenti con le varie funzionalità*

.. |STYLE2| replace:: **sono contestuali al contenuto visualizzato**

.. |STYLE3| replace:: **Modifica di un contenuto esistente;**

.. |STYLE4| replace:: **Creazione di un contenuto;**

.. |STYLE5| replace:: **Aggiunta di una collocazione**

.. |STYLE6| replace:: **Cancellazione di un contenuto:**

.. |STYLE7| replace:: **Spostamento di un contenuto**

.. |STYLE8| replace:: **Ordinare i contenuti:**

.. |STYLE9| replace:: **Caricamento multiplo:**

.. |STYLE10| replace:: **Refresh menu:**

.. |STYLE11| replace:: **Copia:**

.. |STYLE12| replace:: **Interfaccia di amministrazione:**

.. |STYLE13| replace:: **Traduci:**

.. |STYLE14| replace:: **Informazioni sul contenuto:**

.. |STYLE15| replace:: **navigare verso quel contenuto**

.. |STYLE16| replace:: **si clicca sull’icona della matita**

.. |STYLE17| replace:: **interfaccia di modifica**

.. |STYLE18| replace:: **basata sugli attributi della classe di contenuto**

.. |STYLE19| replace:: *Interfaccia di modifica di un oggetto di tipo*

.. |STYLE20| replace:: **Avviso.**

.. |STYLE21| replace:: *Creazione di un nuovo oggetto di tipo*

.. |STYLE22| replace:: **Evento**

.. |STYLE23| replace:: *.*

.. |STYLE24| replace:: *Attraverso la struttura e le relazioni viene generato l’organigramma*

.. |STYLE25| replace:: *Esempio di organigramma a due livelli*

.. |STYLE26| replace:: **Default**

.. |STYLE27| replace:: **Datatable**

.. |STYLE28| replace:: **Filters**

.. |STYLE29| replace:: **Map**

.. |STYLE30| replace:: **Panels**

.. |STYLE31| replace:: **Icons**

.. |STYLE32| replace:: *Il sistema consente diverse tipologie di visualizzazione per gli oggetti contenuti in una pagina*

.. |IMG1| image:: static/Gestione_dei_contenuti_1.png
   :height: 48 px
   :width: 624 px

.. |IMG2| image:: static/Gestione_dei_contenuti_2.png
   :height: 49 px
   :width: 624 px

.. |IMG3| image:: static/Gestione_dei_contenuti_3.png
   :height: 153 px
   :width: 624 px

.. |IMG4| image:: static/Gestione_dei_contenuti_4.png
   :height: 916 px
   :width: 550 px

.. |IMG5| image:: static/Gestione_dei_contenuti_5.png
   :height: 193 px
   :width: 349 px

.. |IMG6| image:: static/Gestione_dei_contenuti_6.png
   :height: 134 px
   :width: 434 px

.. |IMG7| image:: static/Gestione_dei_contenuti_7.png
   :height: 261 px
   :width: 624 px

.. |IMG8| image:: static/Gestione_dei_contenuti_8.png
   :height: 306 px
   :width: 624 px

.. |IMG9| image:: static/Gestione_dei_contenuti_9.png
   :height: 257 px
   :width: 624 px

.. |IMG10| image:: static/Gestione_dei_contenuti_10.png
   :height: 550 px
   :width: 376 px

.. |IMG11| image:: static/Gestione_dei_contenuti_11.png
   :height: 185 px
   :width: 474 px

.. |IMG12| image:: static/Gestione_dei_contenuti_12.png
   :height: 102 px
   :width: 624 px

.. |IMG13| image:: static/Gestione_dei_contenuti_13.png
   :height: 646 px
   :width: 552 px
