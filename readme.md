# Configurazione

## URL BASE DEL SITO

Aprire il file **config.toml** e modificare la linea *baseURL* inserendo l'indirizzo creato da githubpages.

**ATTENZIONE**

Attualmente l'url di base è questo

baseURL = "https://antoniopipitone.github.io/af2-website/public/"

l'url finale dovrebbe essere qualcosa tipo

baseURL = "https://github.com/Air-Factories-2-0/af2-website/public/"

a questo punto compilare utilizzando il comando *hugo*

## Redirect alla cartella public

Inserire lo stesso url inserito su *baseURL* anche nel file **index.html** nel metatag presente nell'header.