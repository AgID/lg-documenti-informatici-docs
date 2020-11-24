.. _`§1`:
§\ :ref:`3 <§3>`

Introduzione
===================================================

Il presente documento fornisce indicazioni iniziali sui formati dei file con cui vengono rappresentati i documenti informatici oggetto delle presenti linee guida. I termini indicati in azzurro, alla prima occorrenza all’interno di questo testo, sono definiti nel Glossario delle presenti Linee guida.

I formati descritti sono stati scelti tra quelli che possono maggiormente garantire il principio dell’interoperabilità tra i sistemi di gestione documentale e conservazione e in base alla normativa vigente riguardante specifiche tipologie di documenti. Va tuttavia segnalato che non tutti i formati di file nel presente documento sono leggibili da qualsivoglia elaboratore, a seconda della configurazione degli applicativi installati. Questo perché, nel caso di finalità specifiche e settoriali (come avviene ad esempio per i file multimediali), alcuni formati di file sono utilizzabili solo dopo l’installazione di software applicativi specifici per l’attuazione delle suddette finalità.

È bene precisare che, rispettando il principio di interoperabilità e cercando di mitigare il rischio di “obsolescenza tecnologica”, i formati consigliati tra quelli elencati elencati –inclusi quelli per finalità specifiche, cfr. 
§\ :ref:`1.2.3 <§1.2.3>`– sono quanto più possibile “aperti”, liberamente utilizzabili e non coperti da brevetto. Sono inoltre reperibili online diversi software applicativi open-source in grado di leggere tali file. Tra i formati elencati

Tra i formati elencati nel presente Allegato, vi sono anche quelli non consigliati per finalità di interoperabilità, archiviazione o conservazione; essi sono presenti nell’elenco perché formati già ampiamente diffusi nella pubblica amministrazione e quindi non ignorabili per quanto riguarda il loro trattamento e il riversamento da questi formati verso formati più interoperabili.

Il presente Allegato, per la natura stessa dell’argomento trattato, viene periodicamente aggiornato sulla base dell’evoluzione tecnologica e dell’obsolescenza dei formati e può essere pubblicato online sotto forma di Avvisi, ovvero di un registro dei formati sul sito istituzionale dell’Agenzia per l’Italia Digitale, raggiungibile all’indirizzo https://registry.AGID.gov.it .

a. il nome del file del documento predisposto per la firma;

b. l’impronta dell’evidenza informatica ottenuta calcolando l’\ :ref:`hash <hash>`
   del file di cui al punto a, calcolata dal SP conformemente a quanto
   indicato al §\ :ref:`6 <§6>`;

c. l’identificativo della funzione di *hash* crittografico utilizzato al
   punto b;

d. il codice fiscale del soggetto che deve apporre la firma.

La **risposta di autenticazione** per la firma con SPID contiene
obbligatoriamente i seguenti metadati:

e. il nome del file del documento firmato con SPID;

f. l’impronta dell’evidenza informatica ottenuta calcolando l’\ :ref:`hash <hash>`
   del file di cui al punto e, calcolata dall’IdP conformemente a quanto
   indicato al §\ :ref:`6 <§6>`;

g. l’identificativo della funzione di *hash* crittografico utilizzato al
   punto f.

L’identificativo unico della sessione di autenticazione (*session ID*),
sempre presente in ogni richiesta e risposta di autenticazione, associa
in modo univoco il documento informatico scambiato tra SP, IdP e vice
versa, ad un’unica autenticazione di firma con SPID.

La durata delle sessioni di autenticazione descritte nell’ambito del
processo di sottoscrizione di cui alle presenti linee guida è estesa
adeguatamente per permettere lo svolgimento dell’intera procedura di
sottoscrizione.

Le richieste e risposte di autenticazione per la firma SPID seguono la
sintassi descritta nei seguenti paragrafi.

.. toctree::
  :maxdepth: 3

  05/05.1_saml.rst
  05/05.2_secure-dataio.rst
