# Accessory Store

## Projekta apraksts

E-komercijas mājaslapa, kas izveidota ar WordPress + WooCommerce uz DigitalOcean servera, izmantojot Cloudflare CDN un SSL sertifikātu.

---

## Galvenās funkcijas

* Produktu katalogs (5+ produkti)
* Grozs un pasūtījuma noformēšana
* Pasūtījumu e-pasti caur SMTP
* PDF rēķini pasūtījumiem
* Cloudflare CDN + HTTPS
* Hostings uz DigitalOcean

---

## Atkārtota izvietošana uz jauna servera

### (DigitalOcean / Ubuntu 22.04)

1. Izveidot jaunu DigitalOcean droplet ar Ubuntu 22.04
2. Atvērt portus 80 un 443
3. Uzstādīt Apache + PHP + MySQL
4. Uzstādīt WordPress (tādu pašu versiju kā produkcijā)
5. Klonēt šo GitHub repozitoriju
6. Iekopēt wp-content WordPress direktorijā (/var/www/html/)
7. Aktivizēt tēmu un nepieciešamos spraudņus WordPress admin panelī
8. Uzstādīt WooCommerce un konfigurēt veikala iestatījumus
9. Konfigurēt pirkuma plūsmu (grozs → checkout → order created)
10. Uzstādīt SMTP e-pastu sūtīšanu (WP Mail SMTP)
11. Konfigurēt Gmail SMTP vai citu SMTP servisu
12. Uzstādīt PDF rēķinu spraudni (PDF Invoices & Packing Slips for WooCommerce)
13. Pievienot domēnu caur Cloudflare
14. Konfigurēt DNS ierakstus (A ieraksts uz DigitalOcean serveri)
15. Nomainīt nameservers uz Cloudflare
16. Uzstādīt SSL sertifikātu ar Let’s Encrypt + Certbot
17. Cloudflare SSL režīms: Full (strict)
18. Pārbaudīt HTTPS darbību un novērst mixed content kļūdas

---
