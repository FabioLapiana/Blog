# README - Il mio blog con Django

Questo progetto è un blog progettato utilizzando Django, un framework web Python potente e flessibile. Il blog ha diverse capacità, tra cui:

- Creazione di modelli dati, visualizzazioni e URL: Il progetto include modelli dati per rappresentare le entità chiave del blog, come gli articoli e i commenti. Le visualizzazioni sono implementate per rendere accessibili le diverse pagine del blog, e gli URL sono gestiti in modo canonico per garantire una buona esperienza utente.

- Sito di amministrazione: Abbiamo integrato un'area di amministrazione in modo da poter gestire facilmente gli articoli, i commenti e altre risorse del blog.

- URL SEO-friendly per gli articoli: Abbiamo implementato URL amichevoli per i motori di ricerca (SEO-friendly) per i post del blog, in modo che siano facilmente individuabili e indicizzabili dai motori di ricerca.

- Paginazione degli articoli: Abbiamo incluso un sistema di paginazione per gli articoli in modo che gli utenti possano navigare tra le diverse pagine di articoli senza dover scorrere una pagina lunghissima.

- Condivisione di post tramite email: I lettori del blog possono condividere i post con i propri amici tramite email grazie all'utilizzo di form appositamente sviluppati.

- Sistema di commenti: È stato implementato un sistema di commenti usando i moduli di Django, in modo che i lettori possano esprimere le proprie opinioni e feedback su ciascun articolo.

- Tagging degli articoli: Abbiamo utilizzato l'estensione di Django chiamata django-taggit per consentire l'aggiunta di tag agli articoli, consentendo ai lettori di identificare facilmente gli articoli correlati attraverso i tag condivisi.

- Articoli consigliati: Basandoci sui tag condivisi, abbiamo implementato una funzionalità che suggerisce articoli simili ai lettori per una migliore esperienza di scoperta dei contenuti.

- Template tags personalizzati: Abbiamo creato tag personalizzati per i template che visualizzano gli ultimi articoli e quelli più commentati.
- 

Requisiti di sistema:

Python 3.11
Django 4.1.7
Installazione e avvio:

Assicurarsi di avere Python 3.11 installato sul proprio sistema.
Clonare questo repository sul proprio computer.
Aprire il terminale nella directory principale del progetto.
Installare le dipendenze eseguendo il comando pip install -r requirements.txt.
Eseguire le migrazioni del database con il comando python manage.py migrate.
Avviare il server di sviluppo con il comando python manage.py runserver.
Visitare http://localhost:8000/blog nel browser per accedere al blog.

Nota finale:

Questo progetto è stato sviluppato per scopi didattici e può essere personalizzato ulteriormente per adattarsi alle proprie esigenze. Il codice è rilasciato con una licenza aperta e liberamente accessibile sul nostro repository GitHub (inserire il link al repository qui). Speriamo che questo progetto possa essere utile come esempio e risorsa per chiunque sia interessato a esplorare Django e la creazione di blog dinamici e interattivi.
