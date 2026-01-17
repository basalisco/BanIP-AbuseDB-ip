# 🌍 BanIP AbuseDB IP Lists  
Repository multilingua: Italiano | English

## 📑 Index / Indice
- [🇮🇹 Italiano](#-italiano)
- [🇬🇧 English](#-english)

---

# 🇮🇹 Italiano

<p align="center">

  <img src="https://img.shields.io/github/actions/workflow/status/basalisco/BanIP-AbuseDB-ip/update.yml?branch=main" alt="Build Status">
  <img src="https://img.shields.io/github/last-commit/basalisco/BanIP-AbuseDB-ip" alt="Last Update">
  <img src="https://img.shields.io/github/repo-size/basalisco/BanIP-AbuseDB-ip" alt="Repo Size">
  <img src="https://img.shields.io/github/license/basalisco/BanIP-AbuseDB-ip" alt="License">
  <img src="https://img.shields.io/github/stars/basalisco/BanIP-AbuseDB-ip" alt="Stars">
  <img src="https://img.shields.io/badge/Auto_Update-Enabled-brightgreen" alt="Auto Update">
  <img src="https://img.shields.io/badge/CIDR-Preserved-success" alt="CIDR Preserved">
  <img src="https://img.shields.io/badge/banIP-Compatible-blue" alt="banIP Compatible">
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

---

## 📌 Origine delle liste

Questo repository non utilizza API key personali e non interroga direttamente AbuseIPDB.

Le liste provengono dal repository pubblico:

https://github.com/borestad/blocklist-abuseipdb

Questo progetto si limita a:

- scaricare tali liste pubbliche  
- pulirle e normalizzarle  
- preservare le CIDR  
- rimuovere duplicati  
- renderle compatibili con banIP  

---

## 🔧 Utilizzo con banIP

In OpenWrt:

1. Vai su **Services → banIP**  
2. Aggiungi un nuovo feed personalizzato  
3. Inserisci l’URL RAW della lista, ad esempio:

https://raw.githubusercontent.com/basalisco/BanIP-AbuseDB-ip/main/abuseipdb_1d.txt

4. Imposta il feed come **INBOUND**  
5. Salva e riavvia banIP  

---

## 📁 Liste disponibili

- abuseipdb_1d.txt — ultime 24 ore  
- abuseipdb_3d.txt — ultime 72 ore  
- abuseipdb_7d.txt — ultima settimana  
- abuseipdb_14d.txt — ultime due settimane  
- abuseipdb_30d.txt — ultimo mese  

---

# 🇬🇧 English

<p align="center">

  <img src="https://img.shields.io/github/actions/workflow/status/basalisco/BanIP-AbuseDB-ip/update.yml?branch=main" alt="Build Status">
  <img src="https://img.shields.io/github/last-commit/basalisco/BanIP-AbuseDB-ip" alt="Last Update">
  <img src="https://img.shields.io/github/repo-size/basalisco/BanIP-AbuseDB-ip" alt="Repo Size">
  <img src="https://img.shields.io/github/license/basalisco/BanIP-AbuseDB-ip" alt="License">
  <img src="https://img.shields.io/github/stars/basalisco/BanIP-AbuseDB-ip" alt="Stars">
  <img src="https://img.shields.io/badge/Auto_Update-Enabled-brightgreen" alt="Auto Update">
  <img src="https://img.shields.io/badge/CIDR-Preserved-success" alt="CIDR Preserved">
  <img src="https://img.shields.io/badge/banIP-Compatible-blue" alt="banIP Compatible">
  <img src="https://img.shields.io/badge/Cleaning-Automated-orange" alt="Cleaning Automated">

</p>

---

# 🚀 BanIP AbuseDB IP Lists

This repository contains IP blocklists based on malicious activity reports, optimized and fully compatible with **banIP** on OpenWrt.

The lists are automatically updated every hour through GitHub Actions, ensuring:

- correct formatting  
- preserved CIDRs  
- zero duplicates  
- no unnecessary comments  
- lightweight and clean output  

---

## 📌 Source of the Lists

This repository does not use personal AbuseIPDB API keys and does not query AbuseIPDB directly.

The lists originate from the public repository:

https://github.com/borestad/blocklist-abuseipdb

This project simply:

- downloads those public lists  
- cleans and normalizes them  
- preserves CIDRs  
- removes duplicates  
- makes them compatible with banIP  

---

## 🔧 How to Use with banIP

On OpenWrt:

1. Go to **Services → banIP**  
2. Add a new custom feed  
3. Insert the RAW URL of the list, for example:

https://raw.githubusercontent.com/basalisco/BanIP-AbuseDB-ip/main/abuseipdb_1d.txt

4. Set the feed as **INBOUND**  
5. Save and restart banIP  

---

## 📁 Available Lists

- abuseipdb_1d.txt — last 24 hours  
- abuseipdb_3d.txt — last 72 hours  
- abuseipdb_7d.txt — last week  
- abuseipdb_14d.txt — last two weeks  
- abuseipdb_30d.txt — last month  

---

## 📜 License

Distributed under the MIT License.
