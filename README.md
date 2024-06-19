# YoDawg Caddy

Yo Dawg, I heard you liked caddy, but you don't want to ever have to write a
single line of production Caddyfile; don't worry, we've got you covered.
When you launch the YoDawg caddy with YoDawger, other YoDawg services will
register their hostnames with YoDawg Caddy via the HTTP YoDawg interface

## Getting Started

1. Have YoDawger set up
2. Clone YoDawg Caddy into /yodawg/Caddy.service
3. Link Caddy to the HTTP service: `ln -s /yodawg/Caddy.service /yodawg/HTTP.service`
4. `/yodawg/yodawger caddy up`
5. Launch other services
6. Enjoy
4
