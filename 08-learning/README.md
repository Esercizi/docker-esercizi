# 08 Alla ricerca dei layer delle imamgini

Scegliere una immagine a piacimento (consiglio: iniziare da una immagine piccola).
Salvare l'immagine in locale in un file tarball e poi analizzarne il contenuto.

Es.: Scelgo Alpine Linux.

```sh
docker pull alpine
docker save -o alpine.tar alpine
mkdir tmp
cd tmp
```

A questo punto estraggo l'archivio:

```sh
tar xvf ../alpine.tar
```

Osservo i file e le cartelle.
Posso procedere iterativamente ad estrarre i vari archivi presenti nel layer.
