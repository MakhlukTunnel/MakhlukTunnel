<div align="center">

# 🤖 MT-BOT — Premium Telegram Bot Solution

### Auto Order VPN • 4 Payment Gateway • Reseller System • 7 Protocols

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![Aiogram](https://img.shields.io/badge/Aiogram-3.x-green.svg)](https://aiogram.dev)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen.svg)]()
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()

**Kelola Bisnis VPN Anda 24/7 Secara Otomatis dengan Bot Telegram Canggih**

</div>

---

## 📋 Daftar Isi

- [✨ Fitur Unggulan](#-fitur-unggulan)
- [💳 4 Payment Gateway](#-4-payment-gateway)
- [🎯 Mengapa MT-BOT?](#-mengapa-mt-bot)
- [📱 Tampilan Interface](#-tampilan-interface)
- [📊 Perbandingan Kompetitor](#-perbandingan-kompetitor)
- [💎 Skema Lisensi](#-skema-lisensi)
- [🚀 Instalasi 1 Menit](#-instalasi-1-menit)
- [❓ FAQ](#-faq)
- [📞 Kontak & Order](#-kontak--order)

---

## ✨ Fitur Unggulan

### 🎮 Auto Order System — 7 Protokol Lengkap

| Protokol | Core | Output Config |
|----------|------|---------------|
| 🌐 **VMess** | Xray | WS, gRPC, XHTTP, Upgrade |
| 📡 **VLess** | Xray | WS, gRPC, XHTTP, Upgrade |
| ⚔️ **Trojan** | Xray | WS, gRPC, XHTTP, Upgrade |
| 🧦 **Shadowsocks** | Xray | WS, gRPC, XHTTP, Upgrade |
| 🔑 **SSH** | OpenSSH | SSH, UDP, OpenVPN, SlowDNS |
| 🔐 **NoobzVPN** | Noobz | TCP STD, TCP SSL |
| 💲 **ZiVPN** | UDP Custom | UDP ZiVPN |

**Fitur Order:**
- ⚡ **Auto Create** — Buat akun VPN ≤ 3 detik via API server
- 🎁 **Trial Configurable** — Durasi trial bisa diatur (menit/jam/hari)
- 🔄 **1-Klik Renew** — Perpanjang tanpa input ulang
- 📊 **Live Usage** — Cek bandwidth & koneksi real-time
- 🗑️ **1-Klik Delete** — Hapus akun langsung dari bot
- 📈 **Prorata Bandwidth** — Kuota disesuaikan durasi sewa
- 💰 **Refund Otomatis** — Refund sisa hari saat hapus akun

### 👥 Manajemen 3 Level Role

<pre>
┌─────────────────────────────────────────────────────────────┐
│                          ADMIN                               │
│  CRUD server • CRUD user • CRUD promo • Broadcast • Settings│
├─────────────────────────────────────────────────────────────┤
│                         RESELLER                             │
│  Harga khusus • Statistik transaksi • Auto-downgrade        │
├─────────────────────────────────────────────────────────────┤
│                          MEMBER                              │
│  Order VPN • Topup saldo • Cek transaksi sendiri            │
└─────────────────────────────────────────────────────────────┘

⚡ AUTO DOWNGRADE: Reseller yang tidak mencapai target transaksi 
   bulanan akan otomatis diturunkan ke Member + notifikasi.
</pre>

### 🎫 Promo Code System — 6 Parameter Targeting

| Parameter | Contoh | Fungsi |
|-----------|--------|--------|
| 🎁 **Tipe Promo** | deposit / purchase | Bonus saldo atau diskon |
| 👥 **Role** | member / reseller | Hanya untuk role tertentu |
| 📦 **Produk** | VMess SG / SSH ID | Hanya untuk produk tertentu |
| 💰 **Min Transaksi** | Rp 50.000 | Minimal belanja |
| 💰 **Max Transaksi** | Rp 500.000 | Maksimal diskon |
| 🔢 **Max Usage** | 100x global | Batas pemakaian total |
| 👤 **Max Per User** | 1x per user | Batas per user |
| ⏱️ **Masa Aktif** | 7 / 30 / 365 hari | Promo terbatas waktu |

### 🛠️ Admin Panel Lengkap

| Menu | Fungsi |
|------|--------|
| ⚙️ **Settings Live** | Edit konfigurasi tanpa restart bot (7 kategori) |
| 📡 **Server Manager** | CRUD server + Reset Stock + harga dual-role |
| 👥 **User Manager** | CRUD user, edit saldo/role/email, cari user |
| 🎁 **Promo Manager** | CRUD promo dengan 6 parameter targeting |
| 📢 **Broadcast** | Kirim ke @user, ID, all, admin, member, reseller |
| 💾 **Auto Backup** | Database dikirim ke admin tiap tengah malam |
| 🔔 **Notifikasi** | Topup & order notifikasi ke admin configurable |

### 🆕 Fitur Baru (Update Terbaru)

| Fitur | Keterangan |
|-------|-------------|
| 💰 **Minimal Deposit** | Bisa diatur via Settings (default Rp 1.000) |
| ⏱️ **Durasi Trial** | Bisa diatur (menit/jam/hari) via Settings |
| 🔄 **Reset Stock Server** | Reset counter akun tanpa hapus transaksi |
| 🔒 **Masking User** | Privasi user di notifikasi (contoh: jo******) |
| 💰 **Refund Otomatis** | Refund sisa hari saat hapus akun (ikut harga server saat ini) |

---

## 💳 4 Payment Gateway

### Perbandingan Gateway

| Gateway | Metode | Verifikasi | Kecepatan | Deposit | Withdraw | Cek Saldo | Mutasi |
|---------|--------|-----------|-----------|---------|----------|-----------|--------|
| **OrderKuota (Asli)** | QRIS | Polling 60s | < 1 menit | ✅ | ✅ | ✅ | ✅ |
| **OrderKuota RafanStr** | QRIS | Webhook | < 3 detik | ✅ | ✅ (e-wallet) | ✅ | ❌ |
| **Tripay** | QRIS/VA/Retail | Webhook HMAC | < 3 detik | ✅ | ❌ | ❌ | ❌ |
| **Tokopay** | QRIS | Webhook MD5 | < 3 detik | ✅ | ❌ | ❌ | ❌ |

### Detail Masing-masing Gateway

<details>
<summary><b>📱 OrderKuota (Asli) — Full Featured</b></summary>

| Keunggulan | Kekurangan |
|------------|------------|
| Bisa pakai akun OrderKuota sendiri | Verifikasi via polling (60 detik) |
| Full fitur: Deposit, Withdraw, Cek Saldo, Mutasi | Perlu konfigurasi lengkap |
| QRIS generate sendiri | |

</details>

<details>
<summary><b>⚡ OrderKuota RafanStr — Cepat & Simple</b></summary>

| Keunggulan | Kekurangan |
|------------|------------|
| Verifikasi webhook (< 3 detik) | Pakai akun RafanStr (tidak bisa pakai sendiri) |
| Withdraw ke DANA/OVO/GOPAY/SHOPEEPAY | Tidak ada fitur cek mutasi |
| API key dari @payqrme_bot | |

</details>

<details>
<summary><b>🏦 Tripay — Professional</b></summary>

| Keunggulan | Kekurangan |
|------------|------------|
| Support QRIS, Virtual Account, Retail | Tidak ada fitur withdraw via bot |
| Security HMAC-SHA256 | Perlu merchant account Tripay |
| Webhook real-time | |

</details>

<details>
<summary><b>💳 Tokopay — Simple QRIS</b></summary>

| Keunggulan | Kekurangan |
|------------|------------|
| Setup simple | Fitur terbatas (hanya deposit) |
| Webhook MD5 | Tidak ada withdraw |
| QRIS only | |

</details>

---

## 🎯 Mengapa MT-BOT?

### 🔥 Keunggulan Dibanding Bot Lain

| Aspek | 🥇 **MT-BOT** | 🥈 Bot X | 🥉 Bot Y |
|-------|------------|---------|---------|
| **7 Protokol** | ✅ | ❌ (3) | ✅ (5) |
| **4 Payment GW** | ✅ | ❌ (1) | ❌ (2) |
| **OrderKuota Asli** | ✅ Full | ❌ | ❌ Only QRIS |
| **OrderKuota RFS** | ✅ Webhook | ❌ | ❌ |
| **Reseller Auto** | ✅ + Downgrade | ❌ | ✅ Manual |
| **Promo Targeting** | ✅ 6 Parameter | ❌ Basic | ❌ Basic |
| **Settings Live** | ✅ 7 Kategori | ❌ | ❌ |
| **Prorata BW** | ✅ Otomatis | ❌ | ❌ |
| **Reset Stock** | ✅ | ❌ | ❌ |
| **Minimal Deposit** | ✅ Configurable | ❌ | ❌ |
| **Trial Duration** | ✅ Configurable | ❌ | ❌ |
| **Refund Otomatis** | ✅ | ❌ | ❌ |
| **Dual Pricing** | ✅ Member/Reseller | ❌ | ✅ |
| **DB Auto Backup** | ✅ Harian | ❌ | ❌ |
| **Broadcast** | ✅ 5 Target | ✅ | ❌ |
| **Daily Trial** | ✅ Reset 00:00 | ❌ | ❌ |
| **Deploy** | 🚀 1 Perintah | Ribet | Ribet |

### 💎 Keunggulan Bisnis

| ✅ | Keunggulan |
|----|-------------|
| 🚀 | **FULL AUTO PILOT** — Bot berjalan 24/7 tanpa henti |
| ⚡ | **ORDER ≤ 3 DETIK** — Pelanggan puas, repeat order tinggi |
| 💳 | **4 PAYMENT GW** — Jangkau semua metode pembayaran |
| 📈 | **RESELLER SYSTEM** — Scale bisnis tanpa batas |
| 🎁 | **PROMO FLEXIBLE** — Strategi marketing unlimited |
| 📦 | **SINGLE BINARY** — Tidak perlu install dependencies Python |
| 🔧 | **LIVE SETTINGS** — Edit konfigurasi tanpa restart |
| 🎯 | **MIN DEPOSIT** — Atur minimal topup sesuai keinginan |
| ⏱️ | **TRIAL DURATION** — Atur durasi trial (menit/jam/hari) |
| 💰 | **REFUND OTOMATIS** — Refund sisa hari saat hapus akun |

---

## 📱 Tampilan Interface

### 🏠 Dashboard Member

<pre>
👤 Username: @customer
📧 Email: customer@mt.id
💰 Saldo: Rp 150.000
🛡️ Role: member
🎁 Trial Tersedia: 5x

👥 Total Users: 1,234

🌐 Statistik Global:
» Hari Ini: 45 trx | Minggu Ini: 312 trx | Bulan Ini: 1,234 trx

📚 Statistik Anda:
» Hari Ini: 3 trx | Minggu Ini: 12 trx | Bulan Ini: 45 trx

⚙️ Status Sistem:
» RAM: 45.2% | CPU: 12.5% | OS: Ubuntu 22.04

📞 CS Admin: @mehonk_cs
─────────────────────────────
🤖 Bot Uptime: 14:32:45
</pre>

### 🛒 Order VMess — Full Config Output

<pre>
┌────────────────────────┐
· ⟨ Xray/VMess Account ⟩
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
» Path : ( /vmess | /xhttp )

» 🌀WS : 
vmess://ew0KICAidiI6ICIyIiwNCiAgInBzIjogIlNHLVZNZXNzIiwNCiAgImFkZCI6ICJzZzEuZXhhbXBsZS5jb20iLA0KICAicG9ydCI6IDQ0MywNCiAgImlkIjogImFiYy1kZWYtZ2hpLWprbCIsDQogICJhaWQiOiAwLA0KICAibmV0IjogIndzIiwNCiAgInR5cGUiOiAibm9uZSIsDQogICJob3N0IjogInNnMS5leGFtcGxlLmNvbSIsDQogICJwYXRoIjogIi92bWVzcyIsDQogICJ0bHMiOiAidGxzIg0KfQ

» 📋Link Account : View Account
─────────────────────────
» 🗓️Expired On : 2026-06-09
» 🤖@mehonk_cs
─────────────────────────
</pre>

### 💳 Pilihan Payment Gateway

<pre>
💰 Pilih metode pembayaran (Minimal Rp 1.000):

┌─────────────────┐ ┌─────────────────┐
│ 💳 OrderKuota   │ │ 💳 Qris RafanStr│
├─────────────────┼─────────────────┤
│ 💳 Tripay       │ │ 💳 Tokopay      │
└─────────────────┴─────────────────┘

🔙 Kembali
</pre>

### ⚙️ Menu Settings (Live Config)

<pre>
⚙️ Pengaturan Sistem
Pilih kategori yang ingin dikonfigurasi:

┌─────────────────┐ ┌─────────────────┐
│ ⚙️ License      │ │ ⚙️ Tokopay      │
├─────────────────┼─────────────────┤
│ ⚙️ Tripay       │ │ ⚙️ Orkut RafanStr│
├─────────────────┼─────────────────┤
│ ⚙️ OrderKuota   │ │ ⚙️ Endpoints    │
├─────────────────┼─────────────────┤
│ ⚙️ Konfigurasi  │ │                 │
│   tambahan      │ │                 │
└─────────────────┴─────────────────┘

🔙 Kembali
</pre>

---

## 📊 Perbandingan Kompetitor

| Fitur | 🥇 **MT-BOT** | 🥈 Bot X | 🥉 Bot Y |
|-------|------------|---------|---------|
| **7 Protokol** | ✅ | ❌ (3) | ✅ (5) |
| **4 Payment GW** | ✅ | ❌ (1) | ❌ (2) |
| **OrderKuota Asli** | ✅ Full | ❌ | ❌ Only QRIS |
| **OrderKuota RFS** | ✅ Webhook | ❌ | ❌ |
| **Reseller Auto** | ✅ + Downgrade | ❌ | ✅ Manual |
| **Promo Targeting** | ✅ 6 Parameter | ❌ Basic | ❌ Basic |
| **Settings Live** | ✅ 7 Kategori | ❌ | ❌ |
| **Prorata BW** | ✅ Otomatis | ❌ | ❌ |
| **Reset Stock** | ✅ | ❌ | ❌ |
| **Minimal Deposit** | ✅ Configurable | ❌ | ❌ |
| **Trial Duration** | ✅ Configurable | ❌ | ❌ |
| **Refund Otomatis** | ✅ | ❌ | ❌ |
| **Dual Pricing** | ✅ Member/Reseller | ❌ | ✅ |
| **DB Auto Backup** | ✅ Harian | ❌ | ❌ |
| **Broadcast** | ✅ 5 Target | ✅ | ❌ |
| **Daily Trial** | ✅ Reset 00:00 | ❌ | ❌ |
| **Deploy** | 🚀 1 Perintah | Ribet | Ribet |
| **Custom Request** | ✅ Welcome | ❌ | ❌ |

---

## 💎 Skema Lisensi

### 🎯 Simple & Transparan

> **Semua fitur FULL. Semua orang dapat perlakuan yang sama.**
> **Lisensi berdasarkan IP Server — Bisa pindah VPS kapan saja!**

<pre>
┌─────────────────────────────────────────────────────────────────┐
│                     🚀 LISENSI MT-BOT                           │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   💰 BIAYA SEWA: Rp 50.000/bulan                               │
│                                                                 │
│   ✅ SEMUA FITUR TERMASUK:                                      │
│   ├─ 7 Protokol VPN (VMess, VLess, Trojan, Shadowsocks,        │
│   │                 SSH, NoobzVPN, ZiVPN)                      │
│   ├─ 4 Payment Gateway (OrderKuota, OrderKuota RFS,            │
│   │                 Tripay, Tokopay)                           │
│   ├─ Reseller System + Auto Downgrade                          │
│   ├─ Promo Code System (6 parameter targeting)                 │
│   ├─ Admin Panel Lengkap (Server, User, Promo, Broadcast)      │
│   ├─ Auto Backup Database (tiap tengah malam)                  │
│   ├─ Daily Trial Reset (otomatis tiap 00:00)                   │
│   ├─ Live Settings Edit (7 kategori, tanpa restart)            │
│   ├─ Minimal Deposit Configurable                              │
│   ├─ Trial Duration Configurable                               │
│   ├─ Reset Stock Server                                        │
│   ├─ Refund Otomatis (ikut harga server saat ini)              │
│   ├─ Single Binary (install 1 perintah)                        │
│   └─ Free Update (selama masa sewa)                            │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   🤝 TANGGUNG JAWAB SAYA (DEV):                                │
│   ├─ Maintenance License API                                   │
│   ├─ Bug Fix & Security Patch                                  │
│   └─ Update fitur (sesuai roadmap)                             │
│                                                                 │
│   🛠️ TANGGUNG JAWAB ANDA (USER):                               │
│   ├─ Setup server & environment (1 perintah)                   │
│   ├─ Konfigurasi bot & payment gateway                         │
│   ├─ Manajemen server VPN sendiri                              │
│   └─ Maintenance server & database                             │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   🎁 BONUS:                                                     │
│   ├─ Trial 3 hari (full fitur)                                 │
│   ├─ Dokumentasi setup lengkap                                 │
│   ├─ Free konsultasi awal                                      │
│   └─ Request fitur baru — sangat terbuka! 🆕                   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
</pre>

---

## 🚀 Instalasi 1 Menit

### 📋 Persyaratan Server

| Komponen | Minimal |
|----------|---------|
| **OS** | Debian 10+ / Ubuntu 20.04+ |
| **RAM** | 1 GB |
| **CPU** | 1 Core |
| **Storage** | 10 GB free |

**Required:**
- Bot Token dari @BotFather (GRATIS)
- Akun payment gateway (GRATIS daftar, pilih salah satu atau semua):
  - OrderKuota
  - OrderKuota RFS (via @payqrme_bot)
  - Tripay
  - Tokopay
- Server VPN yang support API (punya sendiri)

**Optional:**
- Domain + SSL untuk webhook callback (disarankan)

### ⚡ Perintah Instalasi

> **Hubungi saya untuk mendapatkan link installer:** [@mehonk_cs](https://t.me/mehonk_cs)

<pre>
# Setelah mendapatkan link installer, jalankan:
apt update && apt install wget curl jq -y && \
wget --no-check-certificate [LINK_INSTALLER] && \
chmod +x setup-bot && \
./setup-bot
</pre>

### 📝 Proses Instalasi Interaktif

Installer akan memandu Anda mengisi:

<pre>
┌─────────────────────────────────────────────────────────────┐
│  STEP 1: KONFIGURASI UTAMA (WAJIB)                          │
├─────────────────────────────────────────────────────────────┤
│  • Bot Token          → dari @BotFather                     │
│  • CS Admin           → username admin (tanpa @)            │
│  • License Key        → diberikan saat aktivasi             │
│  • Admin User ID      → ID Telegram Anda                    │
│  • Daily Trial        → jumlah trial per user/hari          │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  STEP 2: PAYMENT GATEWAY (PILIH SALAH SATU ATAU SEMUA)     │
├─────────────────────────────────────────────────────────────┤
│  • OrderKuota Asli    → pakai akun sendiri                 │
│  • OrderKuota RFS     → API key dari @payqrme_bot          │
│  • Tripay             → merchant code + key                │
│  • Tokopay            → merchant + secret                  │
└─────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────┐
│  STEP 3: FITUR TAMBAHAN (OPSIONAL)                          │
├─────────────────────────────────────────────────────────────┤
│  • Minimal Deposit   → nominal minimal topup               │
│  • Trial Duration    → durasi trial (30m / 1h / 7)         │
│  • Auto Downgrade    → target transaksi reseller/bulan     │
│  • HTTPS + SSL       → domain untuk webhook                │
└─────────────────────────────────────────────────────────────┘
</pre>

### ✅ Verifikasi Instalasi

<pre>
# Cek status bot
systemctl status mt_bot

# Lihat log real-time
journalctl -u mt_bot.service -f

# Test ke bot di Telegram
# Kirim /start ke @nama_bot_anda
</pre>

### 🔧 Settings Live (Setelah Instalasi)

Setelah bot berjalan, Anda bisa mengubah konfigurasi tanpa restart melalui menu **Settings** di bot:

| Kategori | Yang Bisa Diubah |
|----------|------------------|
| License | API URL, API Key, Secret Key |
| Tokopay | Merchant, Secret |
| Tripay | API Key, Private Key, Merchant Code |
| Orkut RafanStr | API Key, Callback URL |
| OrderKuota | Auth Username, Token, App Version, dll |
| Endpoints | Aktif/nonaktifkan gateway |
| Konfigurasi | CS Admin, Min Deposit, Daily Trial, Time Trial, Notifikasi, Auto Downgrade |

---

## ❓ FAQ

<details>
<summary><b>🤔 Kenapa sewa lisensi bukan beli putus?</b></summary>

Model sewa memastikan Anda selalu dapat update terbaru & security patch. Biaya lebih ringan (Rp 50.000/bulan) dibanding beli putus (Rp 2-3 juta), dan Anda bisa cancel kapan saja.

</details>

<details>
<summary><b>🔒 Apakah data saya aman? Binary kan closed source?</b></summary>

Sangat aman! Database ada di server Anda sendiri. Binary hanya mengunci source code agar tidak bisa di-copy, tapi tidak mengakses data Anda. Saya tidak punya akses ke server atau database Anda sama sekali.

</details>

<details>
<summary><b>🔄 Bagaimana jika saya ganti VPS?</b></summary>

Berikan IP VPS baru ke saya, saya update di database license. Bisa request pindah IP maksimal 2x per bulan. License key tetap sama, tidak perlu ubah config.json.

</details>

<details>
<summary><b>⚡ Apakah bot bisa handle banyak order?</b></summary>

Ya! Bot sudah dioptimasi dengan HTTP/2 multiplexing, connection pooling, async I/O, dan SQLite WAL mode. Ratusan order per hari bisa dihandle tanpa masalah.

</details>

<details>
<summary><b>🆕 Bisakah request fitur baru?</b></summary>

Sangat bisa! Saya sangat terbuka dengan feedback dan request fitur. Selama masih dalam scope bot auto-order VPN dan feasible, akan saya pertimbangkan.

</details>

<details>
<summary><b>📱 Apakah ada trial?</b></summary>

Ya! Trial 3 hari full fitur — testing semua fitur sebelum commit sewa.

</details>

<details>
<summary><b>💳 Payment gateway mana yang harus saya pilih?</b></summary>

| Kebutuhan | Rekomendasi |
|-----------|-------------|
| Ingin withdraw otomatis | OrderKuota Asli |
| Ingin verifikasi cepat (< 3 detik) | OrderKuota RFS atau Tripay |
| Butuh banyak metode pembayaran (VA, Retail) | Tripay |
| Simple dan gratis | Tokopay |
| All-in-one | Setup semua 4 gateway! |

</details>

<details>
<summary><b>⏱️ Berapa durasi trial default?</b></summary>

Default 30 menit, bisa diubah via Settings ke menit (`30m`), jam (`1h`), atau hari (`7`).

</details>

<details>
<summary><b>💰 Berapa minimal deposit?</b></summary>

Default Rp 1.000, bisa diubah via Settings ke nominal berapa pun yang Anda inginkan.

</details>

<details>
<summary><b>💰 Bagaimana sistem refund?</b></summary>

Saat menghapus akun sebelum expired, refund dihitung berdasarkan:
- Harga harian server **SAAT INI** (bukan harga pas beli)
- Sisa hari yang tidak terpakai
- Admin tidak mendapat refund (karena harga = 0)

</details>

---

## 🆕 Roadmap & Request Fitur

### In Progress / Planned

- [ ] Panel Web monitoring (opsional)
- [ ] Multi-language support (EN/ID)
- [ ] Export transaksi ke CSV/Excel
- [ ] Integrasi payment gateway lain (Xendit, Midtrans)
- [ ] Notifikasi via Discord/WhatsApp

### Request Fitur

> **Punya ide fitur yang belum ada? Sampaikan!** Saya sangat terbuka dengan custom request untuk meningkatkan value bot ini.

---

## 📞 Kontak & Order

<div align="center">

### 🤝 **Siap Automasi Bisnis VPN Anda?**

| Kontak | Link |
|--------|------|
| **Telegram** | [@mehonk_cs](https://t.me/mehonk_cs) |

<pre>
1. Kirim IP VPS Anda ke @mehonk_cs
2. Saya buatkan lisensi (3 hari trial FREE)
3. Saya berikan link installer + API KEY
4. Jalankan 1 perintah install
5. Bot siap digunakan!
</pre>

---

**"Sewa lisensi, install 1 menit, bisnis auto pilot!"**

🚀 **MT-BOT — Simple, Powerful, Affordable**

---

<sub>© 2026 MT-BOT — Premium Telegram Bot Solution for VPN Business</sub>
<br>
<sub>All rights reserved.</sub>

</div>
