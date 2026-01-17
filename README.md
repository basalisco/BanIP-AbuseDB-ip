<p align="center">

  <!-- Workflow status -->
  <img src="https://img.shields.io/github/actions/workflow/status/basalisco/BanIP-AbuseDB-ip/update.yml?branch=main" alt="Build Status">

  <!-- Last update -->
  <img src="https://img.shields.io/github/last-commit/basalisco/BanIP-AbuseDB-ip" alt="Last Update">

  <!-- Repo size -->
  <img src="https://img.shields.io/github/repo-size/basalisco/BanIP-AbuseDB-ip" alt="Repo Size">

  <!-- License -->
  <img src="https://img.shields.io/github/license/basalisco/BanIP-AbuseDB-ip" alt="License">

  <!-- Stars -->
  <img src="https://img.shields.io/github/stars/basalisco/BanIP-AbuseDB-ip" alt="Stars">

  <!-- Auto update enabled -->
  <img src="https://img.shields.io/badge/Auto_Update-Enabled-brightgreen" alt="Auto Update">

  <!-- CIDR preserved -->
  <img src="https://img.shields.io/badge/CIDR-Preserved-success" alt="CIDR Preserved">

  <!-- banIP compatible -->
  <img src="https://img.shields.io/badge/banIP-Compatible-blue" alt="banIP Compatible">

  <!-- Cleaning automated -->
  <img src="https://img.shields.io/badge/Cleaning-Automated-orange" alt="Cleaning Automated">

</p>

---

# 🚀 BanIP AbuseDB IP Lists

Repository contenente liste IP basate su segnalazioni di attività malevola, ottimizzate e completamente compatibili con **banIP** su OpenWrt.

Le liste vengono aggiornate automaticamente ogni ora tramite GitHub Actions, mantenendo:

- formattazione corretta  
- CIDR preservate  
- zero duplicati  
- nessun commento superfluo  
- output leggero e pulito  

Perfetto per chi vuole una protezione affidabile e costante contro IP ostili.

---

# 📌 Origine delle liste

Questo repository **non utilizza API key personali** e **non interroga direttamente AbuseIPDB**.

Le liste provengono dal repository pubblico:

https://github.com/borestad/blocklist-abuseipdb

che pubblica dati basati su segnalazioni AbuseIPDB.  
Questo progetto si limita a:

- scaricare tali liste pubbliche  
- pulirle e normalizzarle  
- preservare le CIDR  
- rimuovere duplicati  
- renderle compatibili con banIP  

Questo repository **non è affiliato con AbuseIPDB** e **non redistribuisce dati ottenuti tramite API private**.

---

# ✨ Features

- 🔄 Aggiornamento automatico ogni ora  
- 🧹 Pulizia e normalizzazione delle liste  
- 🧩 Compatibilità totale con banIP  
- 📦 CIDR preservate  
- ⚡ Zero duplicati  
- 🛡 Liste pronte all’uso  
- 📊 Repository leggero e ottimizzato  

---

# 🛠 Workflow

Il workflow GitHub Actions:

1. scarica le liste pubbliche  
2. esegue lo script di pulizia  
3. aggiorna i file solo se ci sono modifiche reali  
4. committa automaticamente  

Il tutto **ogni ora**, senza intervento manuale.

---

# 🔧 Come usare le liste con banIP

In OpenWrt:

1. Vai su **Services → banIP**  
2. Aggiungi un nuovo feed personalizzato  
3. Inserisci l’URL RAW della lista, ad esempio:

