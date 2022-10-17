# 09 Alla ricerca dei dati del container

Avviare il seguente container:

```sh
docker run -it --name=alpinetest -e tmpvar=test alpine sh
```

Esportare il container in run in un archivio:

```sh
docker export -o alpine.tar alpinetest
```

Ora possiamo estrarre il contenuto del tarball ed osservarlo:

```sh
mkdir tmp
cd tmp
tar xvf ../alpine.tar
```

Osservo i file e le cartelle.

Da notare che in questo caso, a differenza dell'esercizio precedente, non sono presenti i metadati e le altre informazioni contenuti nelle immagini.
