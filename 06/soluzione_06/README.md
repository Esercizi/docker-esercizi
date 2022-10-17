# Soluzione 06

Il secondo container non viene eseguito perchè il nome deve essere univoco.
Basta cambiare uno dei due nomi:

```sh
docker run -it --name=test1 alpine:latest date
docker run -it --name=test2 alpine:latest date
```
