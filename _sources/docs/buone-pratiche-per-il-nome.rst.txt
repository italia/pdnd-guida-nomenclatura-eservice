Buone pratiche per il nome dell’e-service
=========================================

NB: Il numero limite di caratteri consentiti per il nome è di **60**

Struttura del nome
------------------

**Si propone una struttura fissa del nome, per facilitarne la lettura e
comprensione.** 

+------------------------+---------+--------------------+----------+
| fortemente consigliati           | quando applicabili            |
+------------------------+---------+--------------------+----------+
|         AZIONE         | OGGETTO | PROGETTO/BASE DATO | (CODICE) |
+------------------------+---------+--------------------+----------+

#. **AZIONE/I** che l’e-service abilita al fruitore: descrive cosa fa, a cosa serve l’e-service. 
   
   Es. ricerca, verifica. ➔Vedi `Glossario delle azioni consigliate per la nomenclatura degli e-service`_

#. **OGGETTO**, ossia il dato in oggetto

   Es. Codice Fiscale, ISEE

#. **PROGETTO/BASE DATO** separato dall’oggetto con un trattino. 

   Es. ANPR oppure WaaS

#. **CODICE** identificativo, inserito come ultimo elemento, tra parentesi. 
   
   Es. (C001)

*E-service completi, che compiono numerose azioni, possono essere nominati con il semplice oggetto.*

*Es. “amministrazione trasparente”, “eventi”.*

Suggeriamo di inserire codici solo quando significativi e riconoscibili
per i fruitori, evitandoli ove non strettamente necessari. Il codice
deve far riferimento a una norma o documentazione consultabile.

.. image:: /media/Fig_01_struttura_nome.webp

Altre buone pratiche: cosa fare e cosa non fare
-----------------------------------------------

-  Inserire **spazi** tra una parola e l’altra, senza utilizzare
   trattini: il catalogo è visitato da persone umane

-  utilizzare le **maiuscole** solo dove necessario

.. image:: /media/Fig_04_esempio_nome.webp

-  quando non strettamente necessari **evitare** **abbreviazioni,
   acronimi, inglesismi** e **termini tecnici** o utilizzati dall’ente
   erogatore ma difficilmente comprensibili in generale: gli e-service
   dovrebbero essere di facile lettura

.. image:: /media/Fig_05_esempio_nome.webp

-  **non** inserire termini quali “**API**”, “**servizio**”,
   “**e-service**”, “**interoperabilità**”: risultano ridondanti e
   sottraggono spazio al contenuto

.. image:: /media/Fig_02_esempio_nome.webp

-  **non** riportare il **nome del fornitore o dell’ente erogatore**, o
   codici identificativi dell’ente. Il nome dell’erogatore è già
   presente nella scheda dell’e-service

-  **non** riportare il **nome del fruitore** o gli attributi necessari
   alla fruizione: le informazioni sono contenute nella scheda
   dell’e-service e potrebbero essere

.. image:: /media/Fig_03_esempio_nome.webp

-  **non** utilizzare termini quali “**new**”, “**nuovo**”, “**clone**”
   o riferimenti alla versione: le informazioni sulla versione sono già
   contenute all’interno della scheda e-service

.. image:: /media/Fig_06_esempio_nome.webp

-  **non** devono essere presenti termini quali “**SOAP**”, “**REST**” in quanto 
   l’architettura con cui è costruita l’API si trova già nella scheda di dettaglio dell'e-service

Glossario delle azioni **consigliate** per la nomenclatura degli e-service
--------------------------------------------------------------------------

+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Azione                                                      | Significato dell'azione                                                                                                                                                                                                                                               | Esempi di e-service                                                                                                                                            |
+=============================================================+=======================================================================================================================================================================================================================================================================+================================================================================================================================================================+
| RICERCA/CONSULTAZIONE                                       | La ricerca (o consultazione) è:                                                                                                                                                                                                                                       |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       | * l'e-service ricerca tutti i soggetti che abitano in una certa via e hanno una certa età                                                                      |
|                                                             | * ricerca di elementi in funzione di alcuni parametri. Tale operazione ritorna una lista che può essere vuota o avere uno o più elementi                                                                                                                              |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       | * dato uno o più codici fiscali, l'e-service recupera i relativi ISEE                                                                                          |
|                                                             | * recupero di dati relativi a uno o più soggetti d'interesse. La non esistenza di tali oggetti comporta una risposta con messaggio di errore                                                                                                                          |                                                                                                                                                                |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| VERIFICA                                                    | Gli e-service di verifica consentono di verificare l’aderenza di informazioni di cui si è in possesso con la realtà dell’oggetto di interesse a cui si ritiene appartengano.  Questi e-service possono, ad esempio, supportare la veridicità di dati autodichiarati.  |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       | * dato il codice fiscale e il valore ISEE (per esempio, auto dichiarato) di un soggetto, l’e-service restituisce Vero se l’ISEE è corretto, Falso altrimenti   |
|                                                             |                                                                                                                                                                                                                                                                       |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       | * dato un documento, l’e-service valida le informazioni contenute e restituisce le eventuali informazioni non corrette                                         |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| INVIO                                                       | Azione tipica degli e-service a erogazione inversa, ovvero che ricevono dati dal fruitore.                                                                                                                                                                            |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       |  * e-service che permette l’invio dei dati da sensoristica IoT                                                                                                 |
|                                                             |                                                                                                                                                                                                                                                                       |                                                                                                                                                                |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Altre azioni specifiche: ISCRIZIONE, RETTIFICA, CAMBIO, ... | Quando l’e-service è utilizzato per un’azione specifica, come una rettifica o un’iscrizione, è buona pratica specificarla nel nome                                                                                                                                    |  * e-service per la rettifica di dati anagrafici                                                                                                               |
|                                                             |                                                                                                                                                                                                                                                                       |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       |  * e-service di iscrizione alla scuola primaria                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       |                                                                                                                                                                |
|                                                             |                                                                                                                                                                                                                                                                       |  * e-service per il cambio di residenza                                                                                                                        |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+


Glossario delle azioni **da evitare** per la nomenclatura degli e-service
-------------------------------------------------------------------------

+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| AZIONE          | COMMENTO                                                                                                                                                                              |
+=================+=======================================================================================================================================================================================+
| FORNITURA       | Spesso utilizzato impropriamente al posto di consultazione.                                                                                                                           |
+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| INTERROGAZIONE  | Utilizzato come sinonimo talvolta di consultazione, talvolta di ricerca.                                                                                                              |
+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| VALIDAZIONE     | Sinonimo di verifica.                                                                                                                                                                 |
+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| RECUPERO        | Sinonimo di consultazione.                                                                                                                                                            |
+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ACQUISIZIONE    | Sinonimo di consultazione o ricerca.                                                                                                                                                  |
+-----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
