
.. _h1f44664a402436677c1c1e2e3c7629:

Manuale OpenCity
****************

OpenCity è un \ |STYLE0|\  (basato sulla piattaforma Open Source eZ Publish) orientato alla strutturazione dei dati. Permette alle \ |STYLE1|\  di presentarsi con un \ |STYLE2|\ . I redattori (funzionari, dirigenti, amministrazioni, associazioni) possono inserire e organizzare facilmente i contenuti, che saranno visualizzati anche con calendari, mappe e grafici.

.. _h2878256a793dd584a14e7776663c4a:

Classi di contenuto
===================

La gestione dei contenuti avviene attraverso le cosiddette “classi di contenuto”. Si tratta di \ |STYLE3|\ .

Ad esempio, se un editor deve inserire una circolare sul sito web, in fase di creazione del contenuto utilizzerà la classe di contenuto “Circolare”.

\ |STYLE4|\ 

Ogni classe di contenuto è costituita da \ |STYLE5|\  (ad esempio “Titolo”, “Testo”, “Data di inizio validità”, “Ufficio proponente”) che vanno compilati in fase di creazione e/o modifica dei contenuti: le interfacce di creazione e modifica di un contenuto sono infatti basate sugli attributi specifici di ogni classe di contenuto.

Alcuni attributi sono di tipo “\ |STYLE6|\ ”, perché \ |STYLE7|\ . 

\ |IMG1|\ 

\ |STYLE8|\ 

Nel caso della circolare, ad esempio, uno degli attributi si chiama “Ufficio proponente”. In fase di compilazione di quel campo non si scriverà il nome dell’ufficio proponente, ma si cercherà tra gli oggetti di tipo “Ufficio” già censiti all’interno del sistema, per selezionare quello che rappresenta l’ufficio responsabile per quella circolare.

Uno dei vantaggi di questo approccio è che le informazioni vengono salvate e mantenute in un unico punto. Si pensi ad esempio al numero di telefono di un ufficio: esso è salvato nell’oggetto che rappresenta quell’ufficio. Quando viene pubblicato un avviso e si vuole indicare una modalità per richiedere maggiori informazioni, anziché scrivere un numero di telefono direttamente nell’avviso, viene inserito un link verso l’ufficio, che detiene l’informazione.

Se il numero dell’ufficio cambia, non è necessario eseguire un tedioso “trova e sostituisci” all’interno dei contenuti del sito, ma basta aggiornare i contenuti dell’oggetto ufficio.


.. admonition:: Un sistema per la mappatura della realtà

    Le classi di contenuto servono per avere una mappatura quasi uno a uno tra contenuti del sistema web e la realtà. Questo presenta numerosi vantaggio, come ad esempio la facilità di organizzare ricerche mirate (solo su determinate tipologie di contenuto) o l’esportazione dei contenuti in formato open data. 

In totale nel sistema sono presenti circa 200 classi di contenuto.

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

.. |IMG1| image:: static/Index_1.png
   :height: 569 px
   :width: 505 px
