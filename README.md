# Un esempio client/server – AngularJS 1.x / Spring 4

👉 Corso correlato:
[Un esempio client/server - AngularJS 1.x / Spring 4](https://stahe.github.io/it-spring-angular1.x-juillet-2014/)

---

## 📌 Panoramica

Questo documento offre un'introduzione congiunta a due importanti framework attraverso l'implementazione di un'applicazione **client/server**:

* **AngularJS 1.x** per il lato client (frontend)
* **Spring 4** per il lato server (backend)

Per semplicità, i termini **Angular** e **Spring** saranno utilizzati nel resto del presente documento.

L'obiettivo è fornire un'illustrazione concreta delle interazioni tra un client web e un server Java utilizzando tecnologie ampiamente utilizzate nello sviluppo di applicazioni web moderne.

---

## 🎯 Obiettivi

* Comprendere l'architettura client/server
* Implementare AngularJS 1.x per lo sviluppo frontend
* Utilizzare Spring 4 per esporre i servizi backend
* Illustrare gli scambi HTTP tra client e server
* Gestire un database tramite JPA

---

## ⚙️ Prerequisiti

La comprensione di questo documento richiede le seguenti conoscenze:

* Livello intermedio in **Java EE**
* Competenza in **JPA (Java Persistence API)**
* Conoscenza di una versione precedente di **Spring**
* Utilizzo di **Maven** per la gestione dei progetti
* Comprensione della comunicazione **HTTP**
* Nozioni di base su:
  * **HTML**
  * **JavaScript**

Ulteriori concetti vengono introdotti gradualmente nel corso del caso di studio.

---

## ⚠️ Nota importante

Questo documento:

* **non è un corso completo**
* è intenzionalmente **incompleto**
* mira principalmente a un **approccio pratico attraverso esempi**

---

## 📚 Risorse consigliate

Per approfondire i concetti trattati:

### AngularJS

* *Pro AngularJS* – Adam Freeman (Apress)
* Documentazione ufficiale: [https://docs.angularjs.org/guide](https://docs.angularjs.org/guide)

### Spring

* *Spring Data* – O’Reilly
* *Pro Spring 3* – Apress (concetti applicabili a Spring 4)
* Documentazione ufficiale di Spring:
  [https://docs.spring.io/spring/docs/current/spring-framework-reference/](https://docs.spring.io/spring/docs/current/spring-framework-reference/)

### Risorse aggiuntive

* [https://stackoverflow.com/](https://stackoverflow.com/) (utile per il debug e gli esempi pratici)

---

## 🧩 Approccio didattico

Questo documento si basa su:

* un **caso di studio reale**
* **esempi pratici**
* un percorso orientato alla **risoluzione dei problemi**

---

## 🚀 Conclusione

Questa risorsa funge da base per:

* comprendere l'integrazione tra AngularJS e Spring
* sperimentare con l'architettura web moderna
* prepararsi a uno sviluppo più avanzato

Serge Tahé, luglio 2014