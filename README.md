<div align="center">

# Marco Valle

**Sviluppatore back-end e data analyst · Bergamo, Italia**

Sviluppo applicazioni gestionali in **Python e Django**, attualmente in produzione,
e modelli di **deep learning** in PyTorch per la previsione a breve termine delle traiettorie aeree.

[![Portfolio](https://img.shields.io/badge/Portfolio-marcovallecs.github.io-111827?style=flat-square&logo=github&logoColor=white)](https://marcovallecs.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marco%20Valle-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcovallecs/)
[![CV IT](https://img.shields.io/badge/CV-ITALIANO-D93F0B?style=flat-square)](https://marcovallecs.github.io/assets/cv/Marco_Valle_CV_IT.pdf)
[![CV EN](https://img.shields.io/badge/CV-ENGLISH-4B8BBE?style=flat-square)](https://marcovallecs.github.io/assets/cv/Marco_Valle_CV_EN.pdf)
[![Email](https://img.shields.io/badge/Email-marco.valle2002@gmail.com-EA4335?style=flat-square)](mailto:marco.valle2002@gmail.com)

</div>

---

## Profilo

Laureato in **Informatica** all'Università di Milano-Bicocca nel 2025 con votazione **99/110**; la tesi ha riguardato i modelli Transformer per la previsione delle traiettorie aeree. Nel corso della laurea ho trascorso un semestre **Erasmus+** presso l'Università di Łódź, in Polonia.

Presso **Aquaforma S.r.l.** (Treviolo) gestisco l'infrastruttura IT e sviluppo il gestionale aziendale, oggi il sistema di gestione principale dell'azienda: anagrafiche, preventivi, ordini, magazzino, DDT e fatturazione elettronica verso lo SDI. Il sistema è in produzione su un VPS Linux con Docker Compose e dispone di oltre **600 test automatici**, eseguiti in CI ad ogni push.

In parallelo all'attività lavorativa dedico il tempo alla ricerca applicata: modelli di deep learning per la previsione delle traiettorie aeree, addestrati su dati **OpenSky ADS-B** reali, un firmware **ESP32** per la misura della chimica dell'acqua di una piscina e un'applicazione **Android** in Kotlin per il controllo dei relè.

| | |
|---|---|
| **Laurea** | 99/110 in Informatica — Università di Milano-Bicocca |
| **Record elaborati** | oltre 65 milioni di record ADS-B, fino a 180 giorni consecutivi di traffico reale |
| **Errore di previsione** | **991,6 m** su un orizzonte di 5–300 s: migliore su tutti gli orizzonti fra **10 modelli** a confronto |
| **Benchmark** | 5 modelli della letteratura reimplementati su dati e protocollo identici (ASCENT, Flow Matching, DDPM, Attention-LSTM, IMM) |
| **Modello** | 1,28 M parametri, 80 epoche in circa 25 minuti su una singola GPU |
| **Test automatici** | oltre 600, in esecuzione in CI ad ogni push |
| **Lingue** | Italiano madrelingua, inglese B2 |

## Progetti principali

| Progetto | Stack | Descrizione | Repository |
|---|---|---|---|
| **AeroTraj-Ultra** | PyTorch · OpenSky · NumPy | Modello **non autoregressivo** multi-orizzonte per la previsione della traiettoria aerea da 5 a 300 secondi, con un'unica passata in avanti e senza accumulo dell'errore. Ogni previsione è ancorata a un propagatore cinematico analitico sull'ellissoide WGS-84 e codificata in **Gray Code**. Include un **benchmark aperto**: dieci modelli della letteratura allenati e valutati sugli stessi dati con lo stesso protocollo. | [AeroTraj-Ultra](https://github.com/MarcoValleCS/AeroTraj-Ultra) |
| **Gestionale aziendale** | Django · PostgreSQL · Docker | Il sistema con cui Aquaforma opera quotidianamente: preventivi, ordini, magazzino, DDT e fatturazione. Genera l'XML **FatturaPA (FPR12)** e lo trasmette allo **SDI** via PEC; espone inoltre un server MCP in sola lettura per l'integrazione con gli assistenti AI. | [gestionale](https://github.com/MarcoValleCS/gestionale) |
| **FlightPREV** | PyTorch · pandas · NumPy | Modello Transformer addestrato su 65 milioni di record ADS-B per la previsione della traiettoria di un aereo da 10 a 120 secondi. Nato dalla tesi di laurea. | [flight](https://github.com/MarcoValleCS/flight) |
| **Portfolio** | HTML · CSS · JavaScript | Il sito personale: nessun framework e nessuna build, HTML, CSS e JavaScript scritti a mano. | [sito](https://marcovallecs.github.io/) · [repository](https://github.com/MarcoValleCS/MarcoValleCS.github.io) |
| **Domotica piscina** | ESP32 · C++ · Kotlin | Firmware per il controllo dei relè e la lettura delle sonde della chimica dell'acqua tramite ADC a 16 bit; applicazione Android via Bluetooth, integrata con Home Assistant. | Codice su richiesta |
| **Progetti minori** | C++ · Java | SuperCold (clone di SuperHot in C++ puro), Tris in modalità single player e le flashcard dei corsi di Bicocca. | [SuperCold](https://github.com/MarcoValleCS/SuperCold) · [Tris](https://github.com/MarcoValleCS/Tris-tic-tac-toe-) · [Flashcard](https://github.com/MarcoValleCS/Flashcard) |

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/pin?username=MarcoValleCS&repo=AeroTraj-Ultra&theme=gruvbox&hide_border=true&cache_seconds=3600" alt="Repository AeroTraj-Ultra" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/pin?username=MarcoValleCS&repo=gestionale&theme=gruvbox&hide_border=true&cache_seconds=3600" alt="Repository gestionale" width="49%" />

</div>

## Stack tecnologico

**Dal codice pubblico** — volume effettivo per linguaggio sui repository pubblici, calcolato da GitHub sui file effettivamente versionati:

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcoValleCS&layout=compact&langs_count=8&theme=gruvbox&hide_border=true&disable_animations=true&cache_seconds=3600" alt="Linguaggi più usati" />

</div>

**Composizione dello stack di lavoro** — quota di tempo di sviluppo per linguaggio, considerando l'attività in produzione, i progetti personali e i corsi universitari:

```text
Python       ████████████████████████████░░  85%   back-end, gestionale, ML, script
HTML / CSS   ███████████░░░░░░░░░░░░░░░░░░░  45%   template Django, sito personale
JavaScript   ██████████░░░░░░░░░░░░░░░░░░░░  40%   front-end, sito personale
C / C++      ████████░░░░░░░░░░░░░░░░░░░░░░  30%   firmware ESP32, progetti C++
SQL          ████████░░░░░░░░░░░░░░░░░░░░░░  30%   PostgreSQL, query su dati reali
Kotlin       ████░░░░░░░░░░░░░░░░░░░░░░░░░░  15%   app Android
Java         ███░░░░░░░░░░░░░░░░░░░░░░░░░░░  10%   progettazione all'università
```

## Tecnologie

**Back-end e web**
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)

**Dati e machine learning**
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3F4F6?style=flat-square&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![OpenSky](https://img.shields.io/badge/OpenSky-ADS-B%20data-0A66C2?style=flat-square)](https://opensky-network.org/)

**DevOps**
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square)](https://gunicorn.org/)
[![Caddy](https://img.shields.io/badge/Caddy-1F8C0C?style=flat-square)](https://caddyserver.com/)

**Embedded e mobile**
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![ESP32](https://img.shields.io/badge/ESP32-8A2BE2?style=flat-square)](https://www.espressif.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)](https://developer.android.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white)](https://developer.mozilla.org/docs/Web/JavaScript)

**Gestionale e integrazioni**
[![Odoo](https://img.shields.io/badge/Odoo-875A7B?style=flat-square&logo=odoo&logoColor=white)](https://www.odoo.com/)
[![XML](https://img.shields.io/badge/XML-005F6B?style=flat-square&logo=w3c&logoColor=white)](https://www.w3.org/XML/)
[![MCP](https://img.shields.io/badge/MCP%20Server-8A2BE2?style=flat-square)](https://modelcontextprotocol.io/)
FatturaPA (FPR12) · SDI · PEC · REST · PWA

## Metodo di lavoro

- **Problemi concreti.** Preferisco un progetto completo e in produzione a più progetti incompiuti.
- **Test automatizzati fin dall'inizio.** Il gestionale dispone di oltre 600 test in CI: ogni push viene verificato e ogni rilascio resta reversibile.
- **Dati reali e protocollo comune.** L'addestramento su traffico reale OpenSky (fino a 180 giorni consecutivi) e il confronto fra modelli su dati e protocollo identici rendono i risultati verificabili da terzi.
- **Documentazione contestuale.** Il codice di dominio viene spiegato meglio di una documentazione separata.

## Percorso professionale

**Formazione e volontariato**

| Periodo | |
|---|---|
| 2021 — 2025 | **Università di Milano-Bicocca** — Laurea in Informatica, 99/110. Tesi: modelli non autoregressivi per la previsione delle traiettorie aeree. |
| 2023 — 2024 | **Erasmus+** — Università di Łódź, Polonia: un semestre di corsi ed esami in inglese. |
| 2019 — oggi | **Educatore scout**, Bergamo — attività educative e di leadership con ragazzi dai 15 ai 19 anni. |

**Esperienza lavorativa**

| Periodo | |
|---|---|
| 2026 — oggi | **Aquaforma S.r.l.**, Treviolo — Socio e dipendente. Sviluppo del gestionale aziendale, gestione di Odoo Enterprise, dell'infrastruttura IT, della rete e del sito. |
| 2023 — 2025 | **Pavis S.r.l.**, Rovato — Installazione e manutenzione di piscine: analisi chimica delle acque, rapporti con clienti e fornitori. |
| 2023 | **Poppies S.r.l.**, Milano — Assistenza e consulenza IT: reti on-premise, postazioni di lavoro e hardware. |

## Attività su GitHub

<div align="center">

<img src="https://github-activity-graph.vercel.app/graph?username=MarcoValleCS&theme=gruvbox&hide_border=true&area=true&custom_title=Attivit%C3%A0%20su%20GitHub&days=180" alt="Attività GitHub" width="100%" />

</div>

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=MarcoValleCS&theme=gruvbox&cache_seconds=3600" alt="Statistiche GitHub" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=MarcoValleCS&theme=gruvbox&cache_seconds=3600" alt="Quando scrivo codice" />

</div>

## Contatti

Per opportunità professionali o di collaborazione sono disponibile al seguente recapito; rispondo a ogni messaggio.

[![Email](https://img.shields.io/badge/Email-marco.valle2002@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marco.valle2002@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-marcovallecs-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcovallecs/)
[![Portfolio](https://img.shields.io/badge/Portfolio-marcovallecs.github.io-111827?style=for-the-badge&logo=github&logoColor=white)](https://marcovallecs.github.io/)

---

<div align="center">

© 2026 Marco Valle

</div>
