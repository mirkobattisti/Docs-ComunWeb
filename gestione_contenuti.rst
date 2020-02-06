
.. _h5a75316a23c415f4e435737646e782e:

Inizia a usare ComunWeb
***********************

.. _hf464843526245477320527c5120671:

Panoramica
==========

L'\ |STYLE3|\  di ComunWeb è pensata per \ |STYLE4|\  da parte degli utenti redattori. La maggior parte delle attività di gestione del sito web, infatti, può essere eseguita tramite un’interfaccia che si integra perfettamente nel front-end del sito web, rendendo così la gestione dei contenuti intuitiva, facile da imparare e da utilizzare.

Su ComunWeb ci sono due modalità che permettono di lavorare sui contenuti del sito: l’\ |STYLE5|\  e l’\ |STYLE6|\ .

* \ |STYLE7|\ 

La maggior parte del lavoro, su un sito ComunWeb - basato su piattaforma eZ Publish -, avviene tramite l’\ |STYLE8|\ . Gli elementi di questa interfaccia vengono visualizzati solo dagli utenti che appartengono a un gruppo con privilegi, per esempio, di \ |STYLE9|\  o \ |STYLE10|\ . Pertanto, gli ospiti del sito, anche se sono registrati, non possono accedere a questa interfaccia. 

Per istruzioni su come accedere all'interfaccia del redattore, fai riferimento alla sezione “Accedi al sistema”.

L'accesso e l'utilizzo delle funzioni di gestione dei contenuti nell'interfaccia del redattore è descritto nella sezione "Gestisci i contenuti".

* \ |STYLE11|\ 

Le attività amministrative più complesse, invece, come la \ |STYLE12|\  e la \ |STYLE13|\ , vengono eseguite tramite l'interfaccia di amministrazione. Generalmente solo gli utenti avanzati, come amministratori di siti e webmaster, devono utilizzare l'interfaccia di amministrazione. In ogni caso, tutte le attività di modifica che possono essere eseguite tramite l'interfaccia del redattore possono anche essere eseguite tramite l'interfaccia di amministrazione.

.. _h4415848433f221aec1a14347f613e:

Accedi al sistema
=================

Per accedere al sistema è necessario cliccare sul pulsante \ |STYLE14|\ 

Inserisci il tuo nome utente e password e quindi fai clic sul pulsante \ |STYLE15|\ .

Nel caso in cui le informazioni fornite (Username o Password) non siano valide (o non siano corrette), il sistema mostra un errore.

\ |STYLE16|\ 

Se l’accesso invece va a buon fine, comparirà in alto la \ |STYLE17|\  del redattore 

.. _h50f222f584470655b17a9783d1046:

Gestisci i contenuti: l’interfaccia del redattore
*************************************************

Questa sezione spiega come gestire i tuoi contenuti attraverso l’\ |STYLE18|\ . 

Per gestire i contenuti del sito web, è necessario aver effettuato l'accesso come utente con diritti di modifica (per impostazione predefinita, bisogna essere un membro dei gruppi Editor o Amministratori).

.. _h117f26752b3d1b796c432369501ce22:

Il sistema di gestione dei contenuti: come funziona?
====================================================

Tutti i siti web appartenenti alla suite OpenPA, che si basano sulla piattaforma eZ Publish, hanno un forte orientamento alla \ |STYLE19|\ . 

La strutturazione dei dati e, quindi, la gestione dei contenuti avviene attraverso le cosiddette classi di contenuto. 

I siti appartenenti alla suite OpenPA infatti possono supportare vari tipi di contenuto, come immagini, articoli, file multimediali, forum, moduli di feedback, ecc. 

Ogni particolare tipo di contenuto viene chiamato una \ |STYLE20|\ , mentre uno specifico contenuto è chiamato \ |STYLE21|\ .

.. _h46721d953744a52045c4d7212313d:

Classe di contenuto
-------------------

Che cos’è una classe di contenuto?

.. admonition:: Definizione

    Una \ |STYLE22|\  di contenuto è una \ |STYLE23|\ . 

Una \ |STYLE24|\  può essere pensata come un \ |STYLE25|\ . Ad esempio, la classe di contenuto dell'Avviso contiene attributi come titolo, data di pubblicazione, breve descrizione, testo dell’avviso, ecc. Sebbene non tutti questi attributi siano obbligatori, fanno tutti parte della classe di contenuto dell'avviso, quindi tutti gli oggetti di contenuto basati su questa classe possono contenere dati per tutti gli attributi definiti dalla classe di contenuto.


.. admonition:: Un sistema per la mappatura della realtà

    Le classi di contenuto servono per avere una mappatura quasi uno a uno tra contenuti del sistema web e la realtà. Questo presenta numerosi vantaggi, come ad esempio la facilità di organizzare ricerche mirate (solo su determinate tipologie di contenuto) o l’esportazione dei contenuti in formato Open Data. 

.. _h1d4c543776b648667653d412d7421:

Oggetto di contenuto
--------------------

Gli \ |STYLE26|\  possono essere sia \ |STYLE27|\  sia \ |STYLE28|\  che contengono altri oggetti situati al di sotto di essi nell’albero dei contenuti. Ad esempio, uno o più oggetti di tipo \ |STYLE29|\  (\ |STYLE30|\ ) possono essere memorizzati sotto un oggetto di tipo \ |STYLE31|\  (\ |STYLE32|\ ). Quando viene visualizzato l'oggetto \ |STYLE33|\ , questo visualizza automaticamente un elenco di riepilogo degli oggetti di tipo Avviso memorizzati al di sotto di esso.

.. _h28216c314279776926c20056637b7:

Attributi
---------

Ogni classe di contenuto è composta da una serie di voci o campi da compilare (\ |STYLE34|\ ) che rappresenta le principali caratteristiche che quel tipo di contenuto ha.

Gli  \ |STYLE35|\  - che variano da una classe all’altra - (ad esempio “Titolo”, “Testo”, “Data di inizio validità”, “Ufficio proponente”) vanno compilati in fase di creazione e/o modifica dei contenuti: \ |STYLE36|\ .

.. _h10604b402c4d5175152c3fd415e671a:

Tipologie di attributi
----------------------

Alcuni attributi possono essere di tipo “\ |STYLE37|\ ”, perché \ |STYLE38|\ . 

.. _h7c2b7466704f1f106c504a672c3d3750:

La barra degli strumenti
------------------------

Quando si effettua l'accesso con un account utente appartenente al gruppo Editor o Amministratore, la barra degli strumenti del sito web (mostrata sotto) viene visualizzata in ogni pagina del sito.

La barra degli strumenti consente di disporre delle funzionalità di \ |STYLE39|\  direttamente sulle pagine del sito (senza bisogno di accedere all’interfaccia di amministrazione). In questo modo è possibile navigare il sito come un normale visitatore, operare modifiche a contenuti esistenti, spostare contenuti, dargli un ordine oppure creare nuovi contenuti.


.. admonition:: Importante

    Le azioni che è possibile svolgere attraverso l’uso della barra degli strumenti \ |STYLE40|\  in quel momento: ad esempio se si sta visualizzando un contenuto di tipo “Ufficio” e si clicca sull’icona con la matita (modifica), verrà modificato esattamente quel contenuto, la stessa cosa vale per la creazione di nuovi contenuti, la cancellazione, e così via.

I pulsanti disponibili dalla barra degli strumenti del sito Web variano a seconda del gruppo di appartenenza dell’editor. Questo significa che l’operatività di un utente è limitata dalle policy di accesso assegnate al suo gruppo di appartenenza.


.. admonition:: L’albero dei contenuti

    Nel sistema ComunWeb, i contenuti sono organizzati in una struttura ad albero. Ogni contenuto ha una sua collocazione nell’albero dei contenuti. Questo va tenuto in considerazione quando viene creato un nuovo contenuto, perché esso va creato nella posizione corretta all’interno di un albero. Fanno eccezioni le immagini, che idealmente vengono create in un unico contenitore (Media/Images) per poter poi essere riutilizzate all’interno dei contenuti del sito.

La barra degli strumenti permette di eseguire le seguenti operazioni sui contenuti:

* \ |STYLE41|\ 

* \ |STYLE42|\ 

* \ |STYLE43|\ 

* \ |STYLE44|\ 

* \ |STYLE45|\ 

* \ |STYLE46|\ 

* \ |STYLE47|\ 

* \ |STYLE48|\ 

* \ |STYLE49|\ 

* \ |STYLE50|\  (data di creazione,  autore, tipologia di contenuto, …)

.. _h2c1d74277104e41780968148427e:




 


.. bottom of content


.. |STYLE0| replace:: **sistema di gestione dei contenuti web**

.. |STYLE1| replace:: *open source*

.. |STYLE2| replace:: **eZ Publish**

.. |STYLE3| replace:: **interfaccia**

.. |STYLE4| replace:: **semplificare la creazione e la gestione dei contenuti del sito web**

.. |STYLE5| replace:: **interfaccia del redattore (front-end)**

.. |STYLE6| replace:: **interfaccia di amministrazione (back-end)**

.. |STYLE7| replace:: **L'interfaccia del redattore**

.. |STYLE8| replace:: **interfaccia del redattore**

.. |STYLE9| replace:: **Editor**

.. |STYLE10| replace:: **Amministratore**

.. |STYLE11| replace:: **L'interfaccia di amministrazione**

.. |STYLE12| replace:: **gestione degli utenti**

.. |STYLE13| replace:: **progettazione del sito**

.. |STYLE14| replace:: **Accedi**

.. |STYLE15| replace:: **Login**

.. |STYLE16| replace:: *Messaggio di accesso non riuscito*

.. |STYLE17| replace:: **barra degli strumenti**

.. |STYLE18| replace:: **interfaccia del redattore**

.. |STYLE19| replace:: **strutturazione dei dati**

.. |STYLE20| replace:: **classe di contenuto**

.. |STYLE21| replace:: **oggetto di contenuto**

.. |STYLE22| replace:: **classe**

.. |STYLE23| replace:: **struttura dati predefinita che rappresenta una specifica tipologia di contenuto**

.. |STYLE24| replace:: **classe di contenuto**

.. |STYLE25| replace:: **modello per un particolare tipo di contenuto che esprime gli attributi di quell'oggetto**

.. |STYLE26| replace:: **oggetti di contenuto**

.. |STYLE27| replace:: **singoli oggetti**

.. |STYLE28| replace:: **contenitori**

.. |STYLE29| replace:: **Avviso**

.. |STYLE30| replace:: *contenuti*

.. |STYLE31| replace:: **Pagina del sito**

.. |STYLE32| replace:: *contenitore*

.. |STYLE33| replace:: **Pagina del sito**

.. |STYLE34| replace:: **attributi**

.. |STYLE35| replace:: **attributi**

.. |STYLE36| replace:: **le interfacce di creazione e modifica di un contenuto sono infatti basate sugli attributi specifici di ogni classe di contenuto**

.. |STYLE37| replace:: **Relazione oggetti**

.. |STYLE38| replace:: **mettono in relazione un oggetto con altri presenti nel sistema**

.. |STYLE39| replace:: *content management*

.. |STYLE40| replace:: **sono contestuali al contenuto visualizzato**

.. |STYLE41| replace:: **Creare un nuovo contenuto**

.. |STYLE42| replace:: **Modificare un contenuto esistente**

.. |STYLE43| replace:: **Spostare un contenuto**

.. |STYLE44| replace:: **Eliminare un contenuto**

.. |STYLE45| replace:: **Visualizzare un contenuto in più posti**

.. |STYLE46| replace:: **Ordinare un elenco di contenuti**

.. |STYLE47| replace:: **Copiare un contenuto**

.. |STYLE48| replace:: **Accedere all’interfaccia di amministrazione**

.. |STYLE49| replace:: **Tradurre un contenuto**

.. |STYLE50| replace:: **Visualizzare delle informazioni sul contenuto**
