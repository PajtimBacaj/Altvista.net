# Altvista.net
Altvista is startup company in Tirana, Albania dedicated to developing innovative hardware and software technologies. Main focus is to create an ecosystem for Smart Home from scratch, more stability performance with less hardware resources. Projekti është i ndërtuar për të qenë fleksibël, i shpejtë dhe i lehtë për t’u zgjeruar në të ardhmen.

# Altvista Smart Home

Altvista Smart Home është një sistem i zhvilluar për menaxhimin dhe kontrollin e pajisjeve smart në një ambient shtëpie ose zyre.

Sistemi është i ndërtuar në Go dhe është projektuar për të punuar si një server i lehtë, i shpejtë dhe i zgjerueshëm.

---

## 🏠 Çfarë bën sistemi

Altvista Smart Home ofron:

- Kontroll të pajisjeve smart (ndez/fik)
- Menaxhim të kamerave IP (RTSP / ONVIF / XM protocol)
- Monitorim të rrjetit lokal (LAN discovery)
- Automatizime bazike (rules / triggers)
- Ruajtje dhe menaxhim të konfigurimeve të pajisjeve
- Integrim me module të jashtme (USB LoRa, sensorë, etj.)

---

## ⚙️ Arkitektura

Sistemi është ndërtuar si një server qendror:

- Backend në **Go**
- API për komunikim me UI / aplikacione
- Module për pajisje (plugins / drivers)
- Support për ekzekutim në Linux server ose PC

---

## 📡 Funksione kryesore

### 🔌 Device Control
Kontroll i pajisjeve smart përmes rrjetit lokal ose protokolleve specifike.

### 📷 Camera Management
- Shikim live RTSP
- Snapshot
- Kontroll i kamerave XM / ONVIF
- Rekordim dhe ruajtje video

### 🌐 Network Discovery
Zbulon pajisjet në LAN automatikisht.

### ⚡ Automation (në zhvillim)
- Rules bazike (IF / THEN)
- Event-driven actions

---

## 🖥️ Build & Run

### Build për Linux / AMD64
