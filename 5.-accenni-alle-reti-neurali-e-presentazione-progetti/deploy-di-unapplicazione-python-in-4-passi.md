---
description: >-
  Dopo tante celle di Colab è ora di vedere un vero script Python all'opera
  dall'inizio alla fine
---

# Deploy di un'applicazione Python in 4 passi

**🔢 Il dataset**

Vogliamo create una sentiment analysis basandoci sui tweet degli utenti delle più importanti compagnie aeree statunitensi, raccolte in questo corposo csv:\
[https://raw.githubusercontent.com/cd5050/CDS22-Torricelli/main/streamlit-first-app/us-airline-tweets.csv](https://raw.githubusercontent.com/cd5050/CDS22-Torricelli/main/streamlit-first-app/us-airline-tweets.csv)\


Questo dataset contiene i tweet relativi a febbraio 2015 classificati in tweet positivi, negativi e neutri. I tweet negativi sono classificati anche in base al motivo. Contiene inoltre le coordinate geografiche da cui sono stati postati i tweet.

**🎯 Gli obiettivi**

Vogliamo creare:

1. un grafico che mostri la distribuzione dei tweet per sentiment
2. una mappa di quando e dove gli utenti hanno tweetato
3. i tweet per compagnia aerea
4. una word cloud con le parole più usate nei tweet

\
**🐍 Il codice Python**

Ecco il codice per creare la nostra app:\
[https://github.com/cd5050/CDS22-Torricelli/blob/main/streamlit-first-app/app.py](https://github.com/cd5050/CDS22-Torricelli/blob/main/streamlit-first-app/app.py)\


Come potete vedere, una volta che si riescono a padroneggiare le basi di Python, è possibile realizzare analisi interessanti con poche righe di codice. Il nostro codice è ospitato su [Github](https://github.com/), che è un servizio di hosting per progetti software.\


**⚙️ ll deploy dell'app**

[Streamlit](https://streamlit.io/) è una libreria Python open source per la creazione di web app analitiche che trasforma gli script di dati in applicazioni condivisibili in pochi minuti. Utilizziamo Streamlit e siamo online 🚀:\


{% embed url="https://github.com/cd5050/CDS22-Torricelli/tree/main/streamlit-first-app" %}
