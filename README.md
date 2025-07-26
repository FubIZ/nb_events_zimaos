# NB Events ZimaOS

Aplicație simplă pentru încărcare fișiere și gestionare evenimente, compatibilă cu ZimaOS și CasaOS.

## Structura proiectului

- `Dockerfile` - imagine PHP cu Apache pentru server web
- `docker-compose.yml` - configurare serviciu Docker pentru rulare container
- `app.yaml` - fișier de configurare pentru integrare în App Store CasaOS/ZimaOS
- `index.php` - punctul de intrare al aplicației
- `config.php` - fișier pentru configurări
- `pages/` - pagini web suplimentare
- `files/` - folder pentru fișiere încărcate și persistente

## Instalare și rulare locală

1. Clonează acest repo:

   ```bash
   git clone https://github.com/FubIZ/nb_events_zimaos.git
   cd nb_events_zimaos
