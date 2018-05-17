
.. _h1f44664a402436677c1c1e2e3c7629:

Manuale OpenCity
****************

OpenCity è un \ |STYLE0|\  (basato sulla piattaforma Open Source eZ Publish) orientato alla strutturazione dei dati. Permette alle \ |STYLE1|\  di presentarsi con un \ |STYLE2|\ . I redattori (funzionari, dirigenti, amministrazioni, associazioni) possono inserire e organizzare facilmente i contenuti, che saranno visualizzati anche con calendari, mappe e grafici.

.. _h2878256a793dd584a14e7776663c4a:

Classi di contenuto
===================

La gestione dei contenuti avviene attraverso le cosiddette “classi di contenuto”. Si tratta di \ |STYLE3|\ .

Ad esempio, se un editor deve inserire una circolare sul sito web, in fase di creazione del contenuto utilizzerà la classe di contenuto “Circolare”.

\ |IMG1|\ \ |STYLE4|\ 

Ogni classe di contenuto è costituita da \ |STYLE5|\  (ad esempio “Titolo”, “Testo”, “Data di inizio validità”, “Ufficio proponente”) che vanno compilati in fase di creazione e/o modifica dei contenuti: le interfacce di creazione e modifica di un contenuto sono infatti basate sugli attributi specifici di ogni classe di contenuto.

Alcuni attributi sono di tipo “\ |STYLE6|\ ”, perché \ |STYLE7|\ . 

\ |IMG2|\ 

\ |STYLE8|\ 

Nel caso della circolare, ad esempio, uno degli attributi si chiama “Ufficio proponente”. In fase di compilazione di quel campo non si scriverà il nome dell’ufficio proponente, ma si cercherà tra gli oggetti di tipo “Ufficio” già censiti all’interno del sistema, per selezionare quello che rappresenta l’ufficio responsabile per quella circolare.

Uno dei vantaggi di questo approccio è che le informazioni vengono salvate e mantenute in un unico punto. Si pensi ad esempio al numero di telefono di un ufficio: esso è salvato nell’oggetto che rappresenta quell’ufficio. Quando viene pubblicato un avviso e si vuole indicare una modalità per richiedere maggiori informazioni, anziché scrivere un numero di telefono direttamente nell’avviso, viene inserito un link verso l’ufficio, che detiene l’informazione.

Se il numero dell’ufficio cambia, non è necessario eseguire un tedioso “trova e sostituisci” all’interno dei contenuti del sito, ma basta aggiornare i contenuti dell’oggetto ufficio.


.. admonition:: Un sistema per la mappatura della realtà

    Le classi di contenuto servono per avere una mappatura quasi uno a uno tra contenuti del sistema web e la realtà. Questo presenta numerosi vantaggio, come ad esempio la facilità di organizzare ricerche mirate (solo su determinate tipologie di contenuto) o l’esportazione dei contenuti in formato open data. 

In totale nel sistema sono presenti circa 200 classi di contenuto.

A titolo esemplificativo, vengono elencate sotto alcune delle più rilevanti classi di contenuto, suddivise per tipologia:

+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE9|\  |Bando di gara, Concorso, Deliberazione, Determinazione, Ordinanza                                     |
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE10|\ |Avviso, Calendario, Comunicato stampa, Evento                                                         |
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE11|\ |Area tematica, Cartella, Frontpage, Homepage, Pagina del sito                                         |
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE12|\ |Circolare, Disciplinare, Modulitstica, Procedura, Utilità                                             |
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE13|\ |Area, Organigramma, Ruolo, Servizio, Struttura, Ufficio                                               |
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE14|\ |Gruppo consiliare, Interpellanza, Interrogazione, Lista elettorale, Organo Politico, Politico, Sindaco|
+-------------+------------------------------------------------------------------------------------------------------+
|\ |STYLE15|\ |Associazione, Azienda, Punto di interesse, Servizio sul territorio, Struttura ricettiva               |
+-------------+------------------------------------------------------------------------------------------------------+

.. _h6f5150673f2401a4b21804d4b464224:

Aspetto estetico del sito web
=============================

Dal punto di vista del design, un sito web basato su \ |STYLE16|\  è allineato all’iniziativa \ |LINK1|\ . Il sito risulta accessibile e ottimizzato per la lettura da dispositivi mobili (smartphone, tablet)

\ |IMG3|\ 

\ |STYLE17|\ 

.. _h6e4d39105a64461f4f3377d353919:

Accesso al sistema
==================

Per accedere al sistema è necessario spostarsi in fondo alla pagina per trovare, vicino alle indicazioni sul Copyright, il link “Accedi con il tuo account”

\ |IMG4|\ 

Una volta effettuato l’accesso, si vedono i link “Profilo utente” (dove è possibile modificare i propri dati e la propria password), agli strumenti a disposizione, e per uscire dal sistema.

\ |IMG5|\ 

.. _h1f184e272f67487d30753a697b3c5351:

Gestione dei contenuti
======================

Una volta effettuato l’accesso al sistema, si vedrà comparire in alto, la barra degli strumenti, che consente di operare sui contenuti del sito.


.. admonition:: L’albero dei contenuti

    Nel sistema Open City, i contenuti sono organizzati in una struttura ad albero. Ogni contenuto ha una sua collocazione nell’albero dei contenuti. Questo va tenuto in considerazione quando viene creato un nuovo contenuto, perché esso va creato nella posizione corretta all’interno di un albero. Fanno eccezioni le immagini, che idealmente vengono create in un unico contenitore (Media/Images) per poter poi essere riutilizzate all’interno dei contenuti del sito.

.. _h7c2b7466704f1f106c504a672c3d3750:

La barra degli strumenti
------------------------

La barra degli strumenti consente di disporre delle funzionalità di \ |STYLE18|\  direttamente sulle pagine del sito (senza bisogno di accedere all’interfaccia di amministrazione). In questo modo è possibile navigare il sito come un normale visitatore, e operare modifiche a contenuti esistenti, spostamento di contenuti, ordinamenti, creazione di nuovi contenuti.

.. _h2853a65f2843553c4e2cb4b6f4b:

\ |IMG6|\ ----------

\ |STYLE19|\ 


..  Important:: 

    Le azioni che è possibile svolgere attraverso l’uso della barra degli strumenti \ |STYLE20|\  in quel momento: ad esempio se si sta visualizzando un contenuto di tipo “Avviso” e si clicca sull’icona con la matita (modifica), verrà modificato esattamente quel contenuto, la stessa cosa vale per la creazione di nuovi contenuti, la cancellazione, e così via.

Le funzionalità principali che è possibile operare dalla barra degli strumenti sono:

* \ |STYLE21|\ 

* \ |STYLE22|\ 

* \ |STYLE23|\ : come visto in precedenza, ogni contenuto del sito ha una collocazione in una struttura ad albero. Questa funzionalità consente di rendere uno stesso contenuto visibile in più sezioni del sito;

* \ |STYLE24|\  prima di cancellare un contenuto, il sistema chiede conferma. Inoltre, è possibile fare in modo che il contenuto venga messo nel cestino, in modo che sia possibile recuperarlo eventualmente;

* \ |STYLE25|\  da una collocazione a un’altra all’interno dell’albero dei contenuti;

* \ |STYLE26|\  posizionandosi su un contenuto, è possibile definire la modalità di ordinamento dei contenuti “figli” (per nome, data di creazione, priorità, …);

* \ |STYLE27|\  è possibile caricare dei files dal proprio pc (immagini, documenti pdf), che vengono convertiti in contenuti (seguendo una mappatura file/contenuto definita a livello di configurazione);

* \ |STYLE28|\  nel caso in cui il menù non mostra le modifiche apportate, è possibile forzare un refresh della visualizzazione del menù stesso;

* \ |STYLE29|\  per copiare un contenuto;

* \ |STYLE30|\  per accedere all’interfaccia di amministrazione e guardare “dietro le quinte”;

* \ |STYLE31|\  consente di tradurre un contenuto;

* \ |STYLE32|\  apre (o chiude) il box con informazioni sul contenuto che si sta visualizzando (data di creazione,  autore, tipologia di contenuto, …)

.. _h20112a6435232c2ee1a474074635b31:

Modifica di un contenuto esistente
----------------------------------

Per modificare un contenuto esistente, è sufficiente \ |STYLE33|\  attraverso i menù e i link del sito, esattamente come farebbe un visitatore. Una volta raggiunto il contenuto da modificare, \ |STYLE34|\  e si passa alla modalità di modifica del contenuto: viene mostrata l’\ |STYLE35|\ , \ |STYLE36|\  di quel particolare contenuto.

Ad esempio, modificando un oggetto di tipo “Avviso”, l’interfaccia sarà basata sugli attributi della classe “Avviso”.

\ |IMG7|\ 

\ |STYLE37|\  \ |STYLE38|\ 

.. _h2c316b717f547316a522c1143139e:

Creazione di un nuovo contenuto
-------------------------------

La creazione di un contenuto avviene nel seguente modo:

Si naviga il sito fino a raggiungere il contenitore all’interno del quale si vuole creare il contenuto, ad esempio un calendario:

\ |IMG8|\ 

Dalla tendina nella barra degli strumenti (1), è possibile filtrare le tipologie di contentuo (2) e  selezionare il tipo di contenuto da creare (3). Infine si preme sul pulsante Crea qui (4):

\ |IMG9|\ 

\ |STYLE39|\  \ |STYLE40|\ \ |STYLE41|\ 

Una volta effettuate queste operazioni, il sistema presenta una interfaccia identica a quella di modifica di un contenuto, con la differenza che i campi (attributi) saranno tutti vuoti.


.. admonition:: Attributi obbligatori

    Nelle interfacce di creazione e modifica dei contenuti, alcuni degli attributi sono marcati con un asterisco. Questo significa che è obbligatorio compilare quegli attributi.

.. _h2939163554334774451b95757d5c2a:

Il menù principale
==================

Il menù principale viene gestito modificando la home page del sito. Bisogna quindi navigare verso la Home page, e poi premere sull’icona “Modifica” della barra degli strumenti.

\ |IMG10|\ 

Si apre l’interfaccia di modifica della Home page, che è di tipo “Homepage”.  Spostandosi verso il basso, si incontra l’attributo che consente di gestire il menu principale. Da qui è possibile ordinare le voci esistenti (1), cancellare alcune delle voci esistenti (2,3), aggiungere contenuti che diventeranno voci di menù in modalità sfoglia (4) o ricerca (5).

\ |IMG11|\ 


..  Important:: 

    Nel menù vengono aggiunti di fatto dei link a contenuti già esistenti nel sito (e collocati nell’albero dei contenuti). Quindi il testo che compare nel menù è quello relativo ai nomi dei contenuti che sono stati aggiunti.


.. admonition:: Refresh dei menu

    Dopo aver apportato una modifica al menù, o ai contenuti che fanno parte del menù, potrebbe essere necessario effettuare un refresh dei menu per rendere effettive le modifiche. Questa operazione è possibile attraverso la funzione “refresh menù” presente nella barra degli strumenti. 

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

* Area tematica

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


.. |STYLE0| replace:: **sistema di gestione dei contenuti web**

.. |STYLE1| replace:: **amministrazioni pubbliche**

.. |STYLE2| replace:: **sito web conforme alle normative vigenti, accessibile e in linea con le direttive AgID**

.. |STYLE3| replace:: **strutture dati predefinite che rappresentazione diverse tipologie di contenuto**

.. |STYLE4| replace:: *La Classe “Circolare” con i suoi attributi e le sue relazioni.*

.. |STYLE5| replace:: **attributi**

.. |STYLE6| replace:: **Relazione oggetti**

.. |STYLE7| replace:: **mettono in relazione un oggetto con altri presenti nel sistema**

.. |STYLE8| replace:: *L’interfaccia di modifica di un oggetto Circolare*

.. |STYLE9| replace:: **Albo**

.. |STYLE10| replace:: **Comunicazione**

.. |STYLE11| replace:: **Contenitori di base**

.. |STYLE12| replace:: **Intranet**

.. |STYLE13| replace:: **Organizzazione**

.. |STYLE14| replace:: **Politica**

.. |STYLE15| replace:: **Territorio**

.. |STYLE16| replace:: **Open City**

.. |STYLE17| replace:: *Il Design di Open City è allineato a Design Italia*

.. |STYLE18| replace:: *content management*

.. |STYLE19| replace:: *La barra degli strumenti con le varie funzionalità*

.. |STYLE20| replace:: **sono contestuali al contenuto visualizzato**

.. |STYLE21| replace:: **Modifica di un contenuto esistente;**

.. |STYLE22| replace:: **Creazione di un contenuto;**

.. |STYLE23| replace:: **Aggiunta di una collocazione**

.. |STYLE24| replace:: **Cancellazione di un contenuto:**

.. |STYLE25| replace:: **Spostamento di un contenuto**

.. |STYLE26| replace:: **Ordinare i contenuti:**

.. |STYLE27| replace:: **Caricamento multiplo:**

.. |STYLE28| replace:: **Refresh menu:**

.. |STYLE29| replace:: **Copia:**

.. |STYLE30| replace:: **Interfaccia di amministrazione:**

.. |STYLE31| replace:: **Traduci:**

.. |STYLE32| replace:: **Informazioni sul contenuto:**

.. |STYLE33| replace:: **navigare verso quel contenuto**

.. |STYLE34| replace:: **si clicca sull’icona della matita**

.. |STYLE35| replace:: **interfaccia di modifica**

.. |STYLE36| replace:: **basata sugli attributi della classe di contenuto**

.. |STYLE37| replace:: *Interfaccia di modifica di un oggetto di tipo*

.. |STYLE38| replace:: **Avviso.**

.. |STYLE39| replace:: *Creazione di un nuovo oggetto di tipo*

.. |STYLE40| replace:: **Evento**

.. |STYLE41| replace:: *.*


.. |LINK1| raw:: html

    <a href="https://designers.italia.it/" target="_blank">Design Italia di AgID</a>


.. |IMG1| image:: static/Index_1.png
   :height: 428 px
   :width: 661 px

.. |IMG2| image:: static/Index_2.png
   :height: 569 px
   :width: 505 px

.. |IMG3| image:: static/Index_3.png
   :height: 326 px
   :width: 624 px

.. |IMG4| image:: static/Index_4.png
   :height: 48 px
   :width: 624 px

.. |IMG5| image:: static/Index_5.png
   :height: 49 px
   :width: 624 px

.. |IMG6| image:: static/Index_6.png
   :height: 153 px
   :width: 624 px

.. |IMG7| image:: static/Index_7.png
   :height: 916 px
   :width: 550 px

.. |IMG8| image:: static/Index_8.png
   :height: 193 px
   :width: 349 px

.. |IMG9| image:: static/Index_9.png
   :height: 134 px
   :width: 434 px

.. |IMG10| image:: static/Index_10.png
   :height: 261 px
   :width: 624 px

.. |IMG11| image:: static/Index_11.png
   :height: 306 px
   :width: 624 px
