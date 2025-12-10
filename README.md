# ITASEAS Website

Sito istituzionale per ITASEAS (Italian Association of South East Asian Studies).

## Sviluppo Locale

Questo progetto utilizza Jekyll con le dipendenze installate localmente in `vendor/bundle` per evitare problemi di permessi di sistema.

### Come avviare il server

1. Apri il terminale nella cartella del progetto.
2. Esegui il comando:
   ```bash
   bundle exec jekyll serve
   ```
3. Il sito sarà disponibile su: [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

### Come fermare il server

- Premi `Ctrl + C` nel terminale dove il server è in esecuzione.

### Installazione (una tantum)

Se scarichi il progetto su un nuovo computer:
```bash
bundle install --path vendor/bundle
```
