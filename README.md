.env-bak ubah jadi .env

Struktur folder
- _Laradock
- sociomile
-- api-sm
-- app-sm
-- crawl
-- crawl-controller
-- notif
-- webhook
-- webhook-a4

Build
`docker compose up -d nginx worker mariadb redis mongo php`

Run
`docker compose start nginx worker mariadb redis mongo php`
