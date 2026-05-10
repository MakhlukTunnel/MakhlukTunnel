# 🤖 MT Bot — Auto Order VPN Premium Solution

> **Kelola Bisnis VPN Anda 24/7 Secara Otomatis dengan Bot Telegram Canggih**

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![Aiogram](https://img.shields.io/badge/Aiogram-3.x-green.svg)](https://aiogram.dev)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Build-PyInstaller%20Binary-orange.svg)]()

---

## 📋 **Daftar Isi**
- [✨ Fitur Unggulan](#-fitur-unggulan)
- [🎯 Mengapa MT Bot?](#-mengapa-mt-bot)
- [🏗️ Arsitektur Sistem](#-arsitektur-sistem)
- [📱 Tampilan & Interface](#-tampilan--interface)
- [💳 Payment Gateway](#-payment-gateway)
- [📊 Perbandingan](#-perbandingan-kompetitor)
- [💎 Skema Lisensi — Rp 50.000/Bulan](#-skema-lisensi--rp-50000bulan)
- [🚀 Cara Memulai](#-cara-memulai)

---

## ✨ **Fitur Unggulan**

### 🎮 **Auto Order System — 7 Protokol Lengkap**

| Protokol | Tipe | Config Output |
|----------|------|---------------|
| 🌐 **VMess** | Xray Core | WS, gRPC, XHTTP, Upgrade |
| 📡 **VLess** | Xray Core | WS, gRPC, XHTTP, Upgrade |
| ⚔️ **Trojan** | Xray Core | WS, gRPC, XHTTP, Upgrade |
| 🧦 **Shadowsocks** | Xray Core | WS, gRPC, XHTTP, Upgrade |
| 🔑 **SSH** | OpenSSH | SSH, UDP, OpenVPN, SlowDNS |
| 🔐 **NoobzVPN** | Noobz | TCP STD, TCP SSL |
| 💲 **ZiVPN** | UDP Custom | UDP ZiVPN |

| Fitur Order | Deskripsi |
|-------------|-----------|
| ⚡ **Auto Create** | Buat akun VPN ≤ 3 detik via API server |
| 🎁 **Trial 15 Menit** | Calon pelanggan bisa coba gratis |
| 🔄 **1-Klik Renew** | Perpanjang akun tanpa input ulang |
| 📊 **Live Usage** | Cek bandwidth & koneksi real-time |
| 🗑️ **1-Klik Delete** | Hapus akun langsung dari bot |
| 📋 **Detail Akun** | Lihat full config + link account |
| 📈 **Prorata Bandwidth** | Kuota disesuaikan durasi sewa |

### 👥 **Manajemen Pelanggan 3 Level**

```

┌──────────┐
│  ADMIN   │ → Full access: CRUD server, user, promo, broadcast
├──────────┤
│ RESELLER │ → Harga khusus, statistik transaksi, target downgrade
├──────────┤
│  MEMBER  │ → Order VPN, topup saldo, cek transaksi sendiri
└──────────┘

⚡ AUTO DOWNGRADE: Reseller yg tidak memenuhi target transaksi 
bulanan akan otomatis diturunkan ke Member + notifikasi.

```

### 💳 **3 Payment Gateway Auto-Verify**

```

┌──────────────────────────────────────────────────┐
│  TRIPAY        TOKOPAY        ORDERKUOTA (QRIS)  │
│  Webhook ✔️    Webhook ✔️     Polling 60s ✔️     │
│  Real-time     Real-time      < 1 menit          │
└──────────────────────────────────────────────────┘

```

### 🎫 **Promo Code System — Marketing Powerhouse**

| Jenis Promo | Contoh | Target |
|-------------|--------|--------|
| 💰 **Deposit Bonus** | Topup 100k + Bonus 10k | Role, min/max amount |
| 🛒 **Diskon Pembelian** | Diskon 10% semua server | Role, produk spesifik |
| 📦 **Per Produk** | Diskon khusus VMess SG | Server tertentu |
| 👥 **Per Role** | Bonus hanya Reseller | Member/Reseller |
| ⏱️ **Masa Aktif** | Promo 7 hari / 30 hari | Start & end date |
| 🔢 **Kuota Promo** | 100x klaim / 1x per user | Global & per-user limit |

### 🏦 **OrderKuota Integration — Full Featured**

| Fitur | Fungsi |
|-------|--------|
| 💰 **Cek Saldo** | Lihat saldo utama & QRIS OrderKuota |
| 📤 **Withdraw** | Tarik saldo langsung dari bot |
| 📊 **Cek Mutasi** | Riwayat transaksi QRIS lengkap |
| 🔄 **QRIS Deposit** | Generate QR code instant |
| ⏱️ **Auto Expire** | Hapus deposit pending > 5 menit |

### 🛠️ **Admin Panel Komplit**

| Menu | Fungsi |
|------|--------|
| ⚙️ **Settings Live** | Edit license, gateway, endpoints tanpa restart |
| 📡 **Server Manager** | Tambah/edit/hapus server + harga dual-role |
| 👥 **User Manager** | CRUD user, edit saldo/role/email |
| 🎁 **Promo Manager** | CRUD promo code + targeting detail |
| 📢 **Broadcast** | Kirim pesan ke @user, ID, all, admin, member, reseller |
| 💾 **Auto Backup** | Database dikirim ke admin tiap tengah malam |
| 🔔 **Notifikasi** | Topup & order notifikasi ke admin configurable |

---

## 🎯 **Mengapa MT Bot?**

### 🔥 **Keunggulan Dibanding Bot Lain**

| Aspek | 🥇 MT Bot | 🥈 Bot Lain |
|-------|-----------|-------------|
| **Protokol** | ✅ 7 Protokol | ❌ 2-3 |
| **Payment Gateway** | ✅ 3 Auto-Verify | ❌ 1 Manual |
| **Reseller System** | ✅ Auto Manage + Downgrade | ❌ / Manual |
| **Promo Targeting** | ✅ Role, Produk, Kuota | ❌ / Basic |
| **OrderKuota Fitur** | ✅ Saldo, WD, Mutasi | ❌ QRIS only |
| **Security** | ✅ HMAC + Token + Anti-Timing | ❌ Basic |
| **Multi-Server** | ✅ Unlimited | ❌ Limited |
| **Live Config Edit** | ✅ Settings tanpa restart | ❌ Restart required |
| **Prorata BW** | ✅ Otomatis | ❌ Flat |

### 💎 **Keunggulan Bisnis**

```

✅ FULL AUTO PILOT — Bot berjalan 24/7 tanpa henti
✅ ORDER ≤ 3 DETIK — Pelanggan puas, repeat order tinggi
✅ 3 PAYMENT GW — Jangkau semua metode pembayaran
✅ RESELLER SYSTEM — Scale bisnis tanpa batas
✅ PROMO FLEXIBLE — Strategi marketing unlimited
✅ SINGLE BINARY — Tidak perlu install dependencies

```

---

## 🏗️ **Arsitektur Sistem**

```

┌─────────────────────────────────────────────────────────────┐
│                     TELEGRAM BOT (Aiogram)                   │
│  ┌─────────┐ ┌──────────┐ ┌──────────┐ ┌────────────────┐  │
│  │  ORDER  │ │  TOPUP   │ │  ADMIN   │ │  NOTIFIKASI    │  │
│  │ SERVICE │ │ PAYMENT  │ │  PANEL   │ │  CALLBACK      │  │
│  └────┬────┘ └────┬─────┘ └────┬─────┘ └───────┬────────┘  │
│       │            │            │               │            │
│       │    ┌───────┴───────┐    │    ┌──────────┴────────┐  │
│       │    │  AUTO VERIFY  │    │    │  WEBHOOK SERVER   │  │
│       │    │  ┌──────────┐ │    │    │  /callback/tripay │  │
│       │    │  │ Tripay   │ │    │    │  /callback/tokopay│  │
│       │    │  │ Tokopay  │ │    │    │  /notif-service   │  │
│       │    │  │ Orkut    │ │    │    └───────────────────┘  │
│       │    │  └──────────┘ │    │                           │
│       │    └───────┬───────┘    │                           │
└───────┼────────────┼────────────┼───────────────────────────┘
│            │            │
┌────▼────┐  ┌───▼────┐  ┌───▼─────┐
│  VPN    │  │ PAYMENT│  │  SQLite │
│ SERVERS │  │   API  │  │   DB    │
└─────────┘  └────────┘  └─────────┘

```

---

## 📱 **Tampilan & Interface**

### 🏠 **Dashboard Member**
```

👤 Username: @customer
📧 Email: customer@mt.id
💰 Saldo: Rp 150.000
🛡️ Role: member

📚 Statistik Anda:
» Hari Ini: 3 trx | Minggu Ini: 12 trx | Bulan Ini: 45 trx

⚙️ Status Sistem:
» RAM: 45.2% | CPU: 12.5% | OS: Ubuntu 22.04

📞 CS Admin: @mehonk_cs
─────────────────────────────
🤖 Bot Uptime: 14:32:45

```

### 🛒 **Order VMess — Full Config Output**
```

┌────────────────────────┐

· ⟨ Xray/VMess Account ⟩*
  └────────────────────────┘
  » Remarks : customer123
  » Provider : DigitalOcean, LLC
  » Location : Singapore
  » Domain : sg1.example.com
  » User Quota : 166 GB
  » Limit IP : 2 IP
  » Port TLS : 443
  » Port NTLS : 80
  » User ID : abc-def-ghi-jkl
  » AlterId : 0
  » Path : ( ws-path | xhttp-path )
  ...
  » 📋Link Account : View
  » 🗓️Expired On : 2026-06-09
  » 🤖@makhluktunnel

```

### 💳 **QRIS Deposit — OrderKuota**
```

📝 Detail Pembayaran:
💰 Nominal: Rp 50.000
🎁 Bonus Promo: Rp 5.000
⚠️ Transfer sesuai nominal di QRIS
⏱️ Berlaku: 5 menit

[QR CODE IMAGE]

```

---

## 💳 **Payment Gateway**

### 🔄 **Auto Verification Mechanism**

| Gateway | Metode | Verifikasi | Response |
|---------|--------|-----------|----------|
| **Tripay** | QRIS, VA, Retail | Webhook HMAC-SHA256 | < 3 detik |
| **Tokopay** | QRIS | Webhook MD5 | < 3 detik |
| **OrderKuota** | QRIS | Polling 60 detik | < 1 menit |

---

## 🛡️ **Keamanan Berlapis**

```

🔐 TRANSPORT LAYER
├─ HTTPS/TLS untuk semua API calls
├─ HTTP/2 untuk performa maksimal
└─ Certificate validation ketat

🔑 AUTHENTICATION
├─ HMAC-SHA256 (Tripay)
├─ MD5 Signature (Tokopay)
├─ Bearer Token (Service Callback)
└─ hmac.compare_digest() — anti-timing attack

🛡️ APPLICATION LAYER
├─ Input validation semua endpoint
├─ SQL injection prevention
├─ Rate limiting per-user (max pending deposits)
├─ Multi-layer deduplication (in-memory + database)
└─ SQLite lock retry (3x auto-retry)

```

---

## 📊 **Perbandingan Kompetitor**

| Fitur | 🥇 **MT Bot** | 🥈 Bot X | 🥉 Bot Y |
|-------|------------|---------|---------|
| **7 Protokol** | ✅ | ❌ (3) | ✅ (5) |
| **3 Payment GW** | ✅ | ❌ (1) | ❌ (2) |
| **Reseller Auto** | ✅ Full | ❌ | ✅ Manual |
| **Promo Targeting** | ✅ 6 Parameter | ❌ Basic | ❌ Basic |
| **Orkut Full** | ✅ Saldo/WD/Mutasi | ❌ | ❌ Only QRIS |
| **Settings Live** | ✅ No Restart | ❌ | ❌ |
| **Prorata BW** | ✅ Otomatis | ❌ | ❌ |
| **Dual Pricing** | ✅ | ❌ | ✅ |
| **DB Auto Backup** | ✅ Harian | ❌ | ❌ |
| **Broadcast** | ✅ Multi-target | ✅ | ❌ |
| **Deploy** | 🚀 1 Binary | Ribet | Ribet |
| **Custom Request** | ✅ Welcome | ❌ | ❌ |

---

## 💎 **Skema Lisensi — Rp 50.000/Bulan**

### 🎯 **Simple & Transparan**

> **Semua fitur full. Semua orang dapat perlakuan yang sama.**

```

┌──────────────────────────────────────────────────────────┐
│               🚀 LISENSI MT BOT                         │
├──────────────────────────────────────────────────────────┤
│                                                          │
│   💰 BIAYA SEWA: Rp 50.000/bulan                        │
│                                                          │
│   ✅ SEMUA FITUR TERMASUK:                               │
│   ├─ 7 Protokol VPN                                     │
│   ├─ 3 Payment Gateway                                  │
│   ├─ Reseller System + Auto Downgrade                   │
│   ├─ Promo Code System (6 parameter)                    │
│   ├─ OrderKuota Full (Saldo, WD, Mutasi, Deposit)       │
│   ├─ Admin Panel Lengkap                                │
│   ├─ Auto Backup Database                               │
│   ├─ Single Binary (No Install)                         │
│   └─ Free Update                                         │
│                                                          │
├──────────────────────────────────────────────────────────┤
│                                                          │
│   🤝 TANGGUNG JAWAB SAYA (DEV):                         │
│   ├─ Maintenance License API                            │
│   ├─ Bug Fix & Security Patch                           │
│   └─ Update fitur (sesuai roadmap)                      │
│                                                          │
│   🛠️ TANGGUNG JAWAB ANDA (USER):                         │
│   ├─ Setup server & environment                         │
│   ├─ Konfigurasi bot & payment gateway                   │
│   ├─ Manajemen server VPN sendiri                       │
│   └─ Maintenance server & database                      │
│                                                          │
├──────────────────────────────────────────────────────────┤
│                                                          │
│   🎁 BONUS:                                              │
│   ├─ Trial 3 hari (full fitur)                          │
│   ├─ Dokumentasi setup lengkap                          │
│   ├─ Free konsultasi awal                               │
│   └─ Request fitur baru — sangat terbuka! 🆕            │
│                                                          │
└──────────────────────────────────────────────────────────┘

```

---

## 🚀 **Cara Memulai**

### **4 Langkah Sederhana**

```

┌─────────────────────────────────────────┐
│  STEP 1 — HUBUNGI SAYA                  │
│  📞 Telegram: @mehonk_cs                │
│  • Tanyakan info & ketersediaan         │
│  • Pilih durasi sewa (1/3/6/12 bulan)   │
└──────────────┬──────────────────────────┘
↓
┌──────────────┴──────────────────────────┐
│  STEP 2 — DAPATKAN BINARY               │
│  • Saya kirim binary via private link   │
│  • License key untuk aktivasi           │
│  • Dokumentasi setup PDF                │
└──────────────┬──────────────────────────┘
↓
┌──────────────┴──────────────────────────┐
│  STEP 3 — SETUP DI SERVER ANDA          │
│  • Upload binary ke VPS                 │
│  • Edit config.json (payment, dll)      │
│  • Jalankan ./mt_bot                    │
└──────────────┬──────────────────────────┘
↓
┌──────────────┴──────────────────────────┐
│  STEP 4 — GO LIVE! 🚀                  │
│  • Bot online 24/7                      │
│  • Setting server & harga via bot       │
│  • Mulai terima order!                  │
└─────────────────────────────────────────┘

```

### **Persyaratan Server**

```yaml
Minimal:
  OS: Ubuntu 20.04 / 22.04 (recommended)
  RAM: 1 GB
  CPU: 1 Core
  Storage: 10 GB free

Required:
  - Bot Token dari @BotFather (GRATIS)
  - Akun Tripay/Tokopay/OrderKuota (GRATIS daftar)
  - Server VPN yang support API (punya sendiri)

Optional:
  - Domain + SSL untuk webhook callback
```

---

❓ FAQ 

<details>
<summary><b>🤔 Kenapa sewa lisensi bukan beli putus?</b></summary>

Model sewa memastikan Anda selalu dapat update terbaru & security patch. Saya juga termotivasi untuk terus maintain dan improve bot. Biaya lebih ringan dibanding beli putus, dan Anda bisa cancel kapan saja.

</details>

<details>
<summary><b>🔒 Apakah data saya aman? Binary kan closed source?</b></summary>

Sangat aman! Database ada di server Anda sendiri. Binary hanya mengunci source code agar tidak bisa di-copy, tapi tidak mengakses data Anda. Saya tidak punya akses ke server atau database Anda sama sekali.

</details>

<details>
<summary><b>🔄 Bagaimana jika saya ganti VPS?</b></summary>

Tinggal upload binary ke VPS baru, update config (domain/IP baru), dan bot langsung jalan. License berdasarkan key, bukan IP/domain.

</details>

<details>
<summary><b>⚡ Apakah bot bisa handle banyak order?</b></summary>

Ya! Bot sudah dioptimasi dengan HTTP/2 multiplexing, connection pooling, async I/O, dan SQLite WAL mode. Ratusan order per hari bisa dihandle tanpa masalah.

</details>

<details>
<summary><b>🆕 Bisakah request fitur baru?</b></summary>

Sangat bisa! Saya sangat terbuka dengan feedback dan request fitur. Selama masih dalam scope bot auto-order VPN dan feasible, akan saya pertimbangkan untuk ditambahkan di update berikutnya.

</details>

<details>
<summary><b>📱 Apakah ada trial?</b></summary>

Ya! Saya sediakan trial 3 hari full fitur supaya Anda bisa testing semua fitur sebelum commit sewa.

</details>

<details>
<summary><b>🆘 Bagaimana support teknisnya?</b></summary>

Saya bantu via Telegram chat untuk setup awal, troubleshooting, bug fixing (1-3 hari), dan pertanyaan seputar fitur bot. Untuk maintenance server/OS/VPN server, itu tanggung jawab Anda sendiri.

</details>

---

🆕 Roadmap & Request Fitur

In Progress / Planned

· Panel Web monitoring (opsional)
· Multi-language support (EN/ID)
· Export transaksi ke CSV/Excel
· Integrasi payment gateway lain (request)
· Notifikasi via Discord/WhatsApp (opsional)

Punya ide fitur yang belum ada? Sampaikan!

Saya sangat terbuka dengan custom request untuk meningkatkan value bot ini. Fitur yang feasible akan masuk backlog dan dikerjakan di update selanjutnya.

---

<div align="center">

🤝 Siap Automasi Bisnis VPN Anda?

📞 Hubungi Saya: @mehonk_cs

"Sewa lisensi, upload binary, bisnis auto pilot!"

🚀 MT Bot — Simple, Powerful, Affordable

</div>

---

© 2026 MT — Premium Telegram Bot Solution. All rights reserved.
