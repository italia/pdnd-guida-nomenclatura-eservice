# Strumenti AI per nomenclatura

In questa directory sono contenuti alcuni strumenti che permettono di essere supportati da una AI per la nomenclatura.

In particolare, sono disponibili una _**skill**_ e una serie di _**prompt**_ suggeriti.

## _Skill_

Le *skill* o competenze, sono istruzioni riutilizzabili che insegnano a un modello AI di tipo LLM come svolgere compiti specifici, automatizzando processi. Ciascuna _skill_ dichiara anche al modello quali siano le condizioni in cui è utile applicarla. In questo caso, le _skill_ proposte sono per le attività legate alla nomenclatura delle API di PDND.

### _Skill_ proposte

* [skill-revisione-nomenclatura-API.md](./skill-revisione-nomenclatura-API.md) : utilizzabile per ottenere proposte di nomenclatura e descrizione di un'API, a partire dalla sua documentazione (OpenAPI, PDF, ...) e dalle eventuali proposte già a disposizione.
  <br>Prompt suggeriti:
  *  \[caricare prima i documenti OpenAPI e PDF\] _Dati i documenti che ti ho caricato e queste proposte di nome "{nome}" e descrizione "{descrizione}", verifica la conformità di nome e descrizione rispetto alle buone pratiche e fammi delle proposte_
  * _Dati i documenti che ti ho caricato fammi delle proposte per nome e descrizione_

### Come installare le skill

* [ChatGPT](https://help.openai.com/en/articles/20001066-skills-in-chatgpt)
* [Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)
