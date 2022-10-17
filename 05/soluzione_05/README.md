# Soluzione 05

L'immagine di partenza scratch è una istruzione nulla per il Dockerfile. Non viene aggiunto nulla quindi occupa 0B.
Il file a.txt è un file di testo semplice. Il suo peso equivale al numero di caratteri presenti, moltiplicato per il peso della loro rappresentazione.
Il carattere "a" è un carattere ASCII standard ed occupa 1B.
Lo spazio totale occupato da questa immagine sarà 0+1=1B.

Verifichiamolo:

```bash
docker build -t 05 .
docker images
```
