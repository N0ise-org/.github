# N0ise

# Feature

Tutti i repost degli utenti sono puntatori ad un link univoco

I repost hanno un titolo definito dall'autore del repost

L'upvote/downvote porta un aumento di score della risorsa e un aumento di "karma" per l'utente che ha repostato


---

Social per "trovare link"

I motori di ricerca non ti mostrano le cose interessanti

Troviamo un modo di mostrare agli utenti link e articoli interessanti sulla base di ciò che gli utenti condividono



Bacheca

Account privato?

## Problemi
- Perchè la gente dovrebbe scaricare?
	- Per trovare info di qualità 
	- per trovare info che su google sono sommerse da merda

- Perchè la gente dovrebbe pubblciare?
	- Knowledge sharing
	- Se ho un bel profilo fa curriculum
	- Possibilità di finire in homepage degli altri

- Evitare doppioni

- Come fare recomendation?
	- Tag?
	- Followers
	- Topic della history

- Reading list?
	- Non ti ripropongo articoli già letti
	- Read later


## Come stracazzo portiamo il pane a casa?

- Pagare per salire di rank
	- No, diventiamo come goolge
- Feature limitate?
	- Limiti le ricerche? è un po da stronzi però non è cosi male

- ADS di default, se non la vuoi paghi

- Farti pagare per opinione
	- Pago subscription/ ogni recensione
		- Evitiamo i Bot
		- Evitiamo shitstorm

Premium
- Verificato
- Ricerche avanzate
	- Filtri strani  es. no wikipedia
- Rimuovi ads
- Vedere cosa leggono le persone che segui (Privacy????????????)



serverless

---
## Funzionalità 
- Condividere link
	- Unici
		- Pro
			- Pulizia 
		- Contro
			- Difficoltà
				- Come compariamo i link? Tagliamo i parametri? Ci sono casi in cui questo cambia destinazione? (su amazon ad es)

- Seguire altri utenti
	- Mostrare cio che postano sulla tua home


- Homepage
	- Tutti i post con recomendation



- Mio profilo
	- Tutti i miei link
	- Recensioni e/o commenti
		- Repost del link con commento

- Link
	- Topic
		- Manuali
			- Anche custom
		 - Automatici
			 - Si vedra
	- Vedere chi ha retwittato
	- Commenti
	- Eventuale propic


## Archittettura

Frontend
	- React 
	- typescript

- DB
	- No sql
		- Mongo
			- Redis

- back
	- Go? 
		- + semplice
	- py ?

	- Node?

- Load balancer
	- ????

Docker
