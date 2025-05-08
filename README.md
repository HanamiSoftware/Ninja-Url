# NinjaUrl

[Ninja Url Logo](https://drive.google.com/file/d/14MIFY94IsLiJ-bDkAaVYyzlfd3D4IDMH/view?usp=sharing)

**NinjaUrl** è un'applicazione avanzata per l'abbreviazione di URL, progettata per offrire velocità, sicurezza e personalizzazione. Il progetto è **open source**, ma include anche funzionalità avanzate disponibili in una versione premium.

## 🚀 Caratteristiche Principali

- **Abbreviazione di URL personalizzabile** con alias dedicati
- **Analisi e statistiche avanzate** per il monitoraggio dei link
- **Protezione con password** per link privati
- **Scadenza temporale dei link**
- **Estensioni per Chrome e Firefox** *(in sviluppo)*
- **API REST per l'integrazione con altre applicazioni**
- **Supporto per QR Code** generati automaticamente
- **Interfaccia moderna e user-friendly**
- **Sistema di Single Sign-On (SSO) con NinjaConnect** *(in sviluppo)*
- **Webhook per notifiche e automazioni** *(in sviluppo)*

## 🔥 Roadmap

- [x] MVP con funzionalità di base
- [ ] Estensioni per Chrome e Firefox
- [ ] Integrazione con AI per analisi predittive
- [ ] Funzionalità avanzate per utenti premium
- [ ] Supporto multi-utente con Single Sign-On (SSO)
- [ ] Dashboard avanzata con analisi dettagliate
- [ ] Implementazione di un modello di business scalabile

## 📦 Installazione

### Requisiti
- PHP 8.1+
- MySQL 8+
- Composer
- Node.js & npm

### Istruzioni

```bash
git clone https://github.com/tuo-username/NinjaUrl.git
cd NinjaUrl
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

Per eseguire il build delle risorse frontend:
```bash
npm run build
```

## 🛠️ Configurazione

### Variabili d'Ambiente
Modifica il file `.env` per configurare le seguenti variabili:

```env
APP_URL=https://ninjaurl.tuo-dominio.com
DB_DATABASE=ninjaurl_db
DB_USERNAME=root
DB_PASSWORD=yourpassword
```

## 📜 Licenza

NinjaUrl è rilasciato sotto licenza **MIT**, consentendo il libero utilizzo, la modifica e la distribuzione del codice. Tuttavia, alcune funzionalità avanzate potrebbero essere disponibili solo nella versione premium.

## 🤝 Contribuire

Contribuire a NinjaUrl è facile! Sentiti libero di **fare un fork** del repository, aprire una **pull request** o segnalare problemi tramite **GitHub Issues**.

1. Fai un fork del progetto
2. Crea un branch con la tua funzionalità: `git checkout -b feature/mia-funzionalita`
3. Committa le tue modifiche: `git commit -m 'Aggiunta nuova funzionalità'`
4. Pusha il branch: `git push origin feature/mia-funzionalita`
5. Apri una pull request

Per rispettare gli standard del progetto, segui le linee guida di codifica e utilizza la formattazione PSR-12 per PHP.

## 📧 Contatti

Hai domande o suggerimenti? Contattami su [LinkedIn](https://www.linkedin.com/in/francescobiagini/) o apri una issue su GitHub.

📌 **Sito Web Ufficiale:** [https://ninjaurl.hanamisoftware.com](https://ninjaurl.hanamisoftware.com)
📌 **Hanami Software Innovative Solutions:** [https://hanamisoftware.com](https://hanamisoftware.com)

---
**NinjaUrl** - Un progetto di [Hanami Software Innovative Solutions](https://hanamisoftware.com)

