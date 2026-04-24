Accessory Store
Projekta apraksts
E-komercijas mājaslapa, kas izveidota ar WordPress + WooCommerce uz DigitalOcean servera, izmantojot Cloudflare CDN un SSL sertifikātu.
Galvenās funkcijas:
Produktu katalogs (5+ produkti)
Grozs un pasūtījuma noformēšana
Pasūtījumu e-pasti caur SMTP
PDF rēķini pasūtījumiem
Cloudflare CDN + HTTPS
Hostings uz DigitalOcean
Atkārtota izvietošana uz jauna servera
(DigitalOcean / Ubuntu 22.04)
Izveidot jaunu DigitalOcean droplet ar Ubuntu 22.04
Atvērt portus 80 un 443
Uzstādīt Apache + PHP + MySQL
Uzstādīt WordPress (tādu pašu versiju kā produkcijā)
Klonēt šo GitHub repozitoriju
Iekopēt wp-content WordPress direktorijā (/var/www/html/)
Aktivizēt tēmu un nepieciešamos spraudņus WordPress admin panelī
Uzstādīt WooCommerce un konfigurēt veikala iestatījumus
Konfigurēt pirkuma plūsmu (grozs → checkout → order created)
Uzstādīt SMTP e-pastu sūtīšanu (WP Mail SMTP)
Konfigurēt Gmail SMTP vai citu SMTP servisu
Uzstādīt PDF rēķinu spraudni (PDF Invoices & Packing Slips for WooCommerce)
Pievienot domēnu caur Cloudflare
Konfigurēt DNS ierakstus (A ieraksts uz DigitalOcean serveri)
Nomainīt nameservers uz Cloudflare
Uzstādīt SSL sertifikātu ar Let’s Encrypt + Certbot
Cloudflare SSL režīms: Full (strict)
Pārbaudīt HTTPS darbību un novērst mixed content kļūdas
