<!DOCTYPE html>
<html>
<body>

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
- [🏗️ Arsitektur Sistem](#️-arsitektur-sistem)
- [📱 Tampilan Interface](#-tampilan-interface)
- [📊 Perbandingan Kompetitor](#-perbandingan-kompetitor)
- [💎 Skema Lisensi](#-skema-lisensi)
- [🚀 Instalasi 1 Menit](#-instalasi-1-menit)
- [❓ FAQ](#-faq)
- [📞 Kontak & Order](#-kontak--order)

---

## ✨ Fitur Unggulan

### 🎮 Auto Order System — 7 Protokol Lengkap

<table>
  <thead>
    <tr>
      <th>Protokol</th>
      <th>Core</th>
      <th>Output Config</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>🌐 <strong>VMess</strong></td><td>Xray</td><td>WS, gRPC, XHTTP, Upgrade</td></tr>
    <tr><td>📡 <strong>VLess</strong></td><td>Xray</td><td>WS, gRPC, XHTTP, Upgrade</td></tr>
    <tr><td>⚔️ <strong>Trojan</strong></td><td>Xray</td><td>WS, gRPC, XHTTP, Upgrade</td></tr>
    <tr><td>🧦 <strong>Shadowsocks</strong></td><td>Xray</td><td>WS, gRPC, XHTTP, Upgrade</td></tr>
    <tr><td>🔑 <strong>SSH</strong></td><td>OpenSSH</td><td>SSH, UDP, OpenVPN, SlowDNS</td></tr>
    <tr><td>🔐 <strong>NoobzVPN</strong></td><td>Noobz</td><td>TCP STD, TCP SSL</td></tr>
    <tr><td>💲 <strong>ZiVPN</strong></td><td>UDP Custom</td><td>UDP ZiVPN</td></tr>
  </tbody>
</table>

<br>

<table>
  <tr>
    <td>⚡ <strong>Auto Create</strong></td>
    <td>Buat akun VPN ≤ 3 detik via API server</td>
  </tr>
  <tr>
    <td>🎁 <strong>Trial 15 Menit</strong></td>
    <td>Calon pelanggan bisa coba gratis</td>
  </tr>
  <tr>
    <td>🔄 <strong>1-Klik Renew</strong></td>
    <td>Perpanjang akun tanpa input ulang</td>
  </tr>
  <tr>
    <td>📊 <strong>Live Usage</strong></td>
    <td>Cek bandwidth & koneksi real-time</td>
  </tr>
  <tr>
    <td>🗑️ <strong>1-Klik Delete</strong></td>
    <td>Hapus akun langsung dari bot</td>
  </tr>
  <tr>
    <td>📈 <strong>Prorata Bandwidth</strong></td>
    <td>Kuota disesuaikan durasi sewa</td>
  </tr>
</table>

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

<table>
  <thead>
    <tr><th>Parameter</th><th>Contoh</th><th>Fungsi</th></tr>
  </thead>
  <tbody>
    <tr><td>🎁 Tipe Promo</td><td>deposit / purchase</td><td>Bonus saldo atau diskon</td></tr>
    <tr><td>👥 Role</td><td>member / reseller</td><td>Hanya untuk role tertentu</td></tr>
    <tr><td>📦 Produk</td><td>VMess SG / SSH ID</td><td>Hanya untuk produk tertentu</td></tr>
    <tr><td>💰 Min Transaksi</td><td>Rp 50.000</td><td>Minimal belanja</td></tr>
    <tr><td>💰 Max Transaksi</td><td>Rp 500.000</td><td>Maksimal diskon</td></tr>
    <tr><td>🔢 Max Usage</td><td>100x global</td><td>Batas pemakaian total</td></tr>
    <tr><td>👤 Max Per User</td><td>1x per user</td><td>Batas per user</td></tr>
    <tr><td>⏱️ Masa Aktif</td><td>7 / 30 / 365 hari</td><td>Promo terbatas waktu</td></tr>
  </tbody>
</table>

### 🛠️ Admin Panel Lengkap

<table>
  <thead>
    <tr><th>Menu</th><th>Fungsi</th></tr>
  </thead>
  <tbody>
    <tr><td>⚙️ Settings Live</td><td>Edit konfigurasi tanpa restart bot</td></tr>
    <tr><td>📡 Server Manager</td><td>CRUD server + harga dual-role (member/reseller)</td></tr>
    <tr><td>👥 User Manager</td><td>CRUD user, edit saldo/role/email, cari user</td></tr>
    <tr><td>🎁 Promo Manager</td><td>CRUD promo dengan 6 parameter targeting</td></tr>
    <tr><td>📢 Broadcast</td><td>Kirim ke @user, ID, all, admin, member, reseller</td></tr>
    <tr><td>💾 Auto Backup</td><td>Database dikirim ke admin tiap tengah malam</td></tr>
    <tr><td>🔔 Notifikasi</td><td>Topup & order notifikasi ke admin configurable</td></tr>
  </tbody>
</table>

---

## 💳 4 Payment Gateway

### Perbandingan Gateway

<table>
  <thead>
    <tr>
      <th>Gateway</th>
      <th>Metode</th>
      <th>Verifikasi</th>
      <th>Kecepatan</th>
      <th>Deposit</th>
      <th>Withdraw</th>
      <th>Cek Saldo</th>
      <th>Mutasi</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>OrderKuota (Asli)</strong></td><td>QRIS</td><td>Polling 60s</td><td>&lt; 1 menit</td><td>✅</td><td>✅</td><td>✅</td><td>✅</td></tr>
    <tr><td><strong>OrderKuota RafanStr</strong></td><td>QRIS</td><td>Webhook</td><td>&lt; 3 detik</td><td>✅</td><td>✅ (e-wallet)</td><td>✅</td><td>❌</td></tr>
    <tr><td><strong>Tripay</strong></td><td>QRIS/VA/Retail</td><td>Webhook HMAC</td><td>&lt; 3 detik</td><td>✅</td><td>❌</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Tokopay</strong></td><td>QRIS</td><td>Webhook MD5</td><td>&lt; 3 detik</td><td>✅</td><td>❌</td><td>❌</td><td>❌</td></tr>
  </tbody>
</table>

### Detail Masing-masing Gateway

<details>
<summary><b>📱 OrderKuota (Asli) — Full Featured</b></summary>

| Keunggulan | Kekurangan |
|------------|------------|
| Bisa pakai akun OrderKuota sendiri | Verifikasi via polling (60 detik) |
| Full fitur: Deposit, Withdraw, Cek Saldo, Mutasi | Perlu konfigurasi auth_username, auth_token, data_qris |
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

<table>
  <thead>
    <tr>
      <th>Aspek</th>
      <th>🥇 <strong>MT-BOT</strong></th>
      <th>🥈 Bot X</th>
      <th>🥉 Bot Y</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><strong>7 Protokol</strong></td><td>✅</td><td>❌ (3)</td><td>✅ (5)</td></tr>
    <tr><td><strong>4 Payment GW</strong></td><td>✅</td><td>❌ (1)</td><td>❌ (2)</td></tr>
    <tr><td><strong>OrderKuota Asli</strong></td><td>✅ Full</td><td>❌</td><td>❌ Only QRIS</td></tr>
    <tr><td><strong>OrderKuota RFS</strong></td><td>✅ Webhook</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Reseller Auto</strong></td><td>✅ + Downgrade</td><td>❌</td><td>✅ Manual</td></tr>
    <tr><td><strong>Promo Targeting</strong></td><td>✅ 6 Parameter</td><td>❌ Basic</td><td>❌ Basic</td></tr>
    <tr><td><strong>Settings Live</strong></td><td>✅ No Restart</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Prorata BW</strong></td><td>✅ Otomatis</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Dual Pricing</strong></td><td>✅ Member/Reseller</td><td>❌</td><td>✅</td></tr>
    <tr><td><strong>DB Auto Backup</strong></td><td>✅ Harian</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Broadcast</strong></td><td>✅ 5 Target</td><td>✅</td><td>❌</td></tr>
    <tr><td><strong>Daily Trial</strong></td><td>✅ Reset 00:00</td><td>❌</td><td>❌</td></tr>
    <tr><td><strong>Deploy</strong></td><td>🚀 1 Perintah</td><td>Ribet</td><td>Ribet</td></tr>
    <tr><td><strong>Custom Request</strong></td><td>✅ Welcome</td><td>❌</td><td>❌</td></tr>
  </tbody>
</table>

### 💎 Keunggulan Bisnis

<table>
  <tr>
    <td>✅ FULL AUTO PILOT</td>
    <td>Bot berjalan 24/7 tanpa henti</td>
  </tr>
  <tr>
    <td>✅ ORDER ≤ 3 DETIK</td>
    <td>Pelanggan puas, repeat order tinggi</td>
  </tr>
  <tr>
    <td>✅ 4 PAYMENT GW</td>
    <td>Jangkau semua metode pembayaran</td>
  </tr>
  <tr>
    <td>✅ RESELLER SYSTEM</td>
    <td>Scale bisnis tanpa batas</td>
  </tr>
  <tr>
    <td>✅ PROMO FLEXIBLE</td>
    <td>Strategi marketing unlimited</td>
  </tr>
  <tr>
    <td>✅ SINGLE BINARY</td>
    <td>Tidak perlu install dependencies Python</td>
  </tr>
  <tr>
    <td>✅ INSTALL 1 MENIT</td>
    <td>Jalankan 1 perintah, bot langsung siap</td>
  </tr>
</table>

---

## 🏗️ Arsitektur Sistem

<pre>
┌─────────────────────────────────────────────────────────────────────┐
│                          TELEGRAM BOT (Aiogram)                      │
│  ┌─────────┐ ┌──────────┐ ┌──────────┐ ┌────────────────────────┐  │
│  │  ORDER  │ │  TOPUP   │ │  ADMIN   │ │     NOTIFIKASI         │  │
│  │ SERVICE │ │ PAYMENT  │ │  PANEL   │ │     CALLBACK           │  │
│  └────┬────┘ └────┬─────┘ └────┬─────┘ └───────────┬────────────┘  │
│       │            │            │                   │               │
│       │    ┌───────┴───────┐    │    ┌──────────────┴───────────┐  │
│       │    │ AUTO VERIFY  │    │    │     WEBHOOK SERVER        │  │
│       │    │ ┌──────────┐ │    │    │  /callback/tripay         │  │
│       │    │ │ Tripay   │ │    │    │  /callback/tokopay        │  │
│       │    │ │ Tokopay  │ │    │    │  /callback/orkutrfs       │  │
│       │    │ │ Orkut    │ │    │    │                       │  │
│       │    │ └──────────┘ │    │    └───────────────────────────┘  │
│       │    └───────┬───────┘    │                                   │
└───────┼────────────┼────────────┼───────────────────────────────────┘
        │            │            │
┌───────▼────┐  ┌─────▼─────┐  ┌──▼────────┐
│   VPN      │  │ PAYMENT   │  │  SQLite   │
│   SERVERS  │  │   APIs    │  │    DB     │
│            │  │           │  │           │
│ • VMess    │  │ • Tripay  │  │ • users   │
│ • VLess    │  │ • Tokopay │  │ • produk  │
│ • Trojan   │  │ • Orkut   │  │ • harga   │
│ • Shadowsocks│ │ • OrkutRFS│  │ • transaksi│
│ • SSH      │  │           │  │ • promo   │
│ • NoobzVPN │  │           │  │ • pending │
│ • ZiVPN    │  │           │  │   _deposits│
└────────────┘  └───────────┘  └───────────┘
</pre>

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
💰 Pilih metode pembayaran:

┌─────────────────┐ ┌─────────────────┐
│ 💳 OrderKuota   │ │ 💳 Qris RafanStr│
├─────────────────┼─────────────────┤
│ 💳 Tripay       │ │ 💳 Tokopay      │
└─────────────────┴─────────────────┘

🔙 Kembali
</pre>

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
│   ├─ 7 Protokol VPN                                            │
│   ├─ 4 Payment Gateway                                         │
│   ├─ Reseller System + Auto Downgrade                          │
│   ├─ Promo Code System (6 parameter targeting)                 │
│   ├─ Admin Panel Lengkap                                       │
│   ├─ Auto Backup Database                                      │
│   ├─ Daily Trial Reset (otomatis tiap 00:00)                   │
│   ├─ Live Settings Edit (tanpa restart)                        │
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

<table>
  <tr>
    <td colspan="2"><strong>Minimal:</strong></td>
  </tr>
  <tr>
    <td>OS</td>
    <td>Debian 10+ / Ubuntu 20.04+</td>
  </tr>
  <tr>
    <td>RAM</td>
    <td>1 GB</td>
  </tr>
  <tr>
    <td>CPU</td>
    <td>1 Core</td>
  </tr>
  <tr>
    <td>Storage</td>
    <td>10 GB free</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Required:</strong></td>
  </tr>
  <tr>
    <td>Bot Token</td>
    <td>dari @BotFather (GRATIS)</td>
  </tr>
  <tr>
    <td>Payment Gateway</td>
    <td>OrderKuota / OrderKuota RFS / Tripay / Tokopay (GRATIS daftar)</td>
  </tr>
  <tr>
    <td>VPN Server</td>
    <td>Server VPN yang support API (punya sendiri)</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Optional:</strong></td>
  </tr>
  <tr>
    <td>Domain + SSL</td>
    <td>untuk webhook callback (disarankan)</td>
  </tr>
</table>

### ⚡ Perintah Instalasi

> **Hubungi saya untuk mendapatkan link installer:** [@mehonk_cs](https://t.me/mehonk_cs)

```bash
# Setelah mendapatkan link installer, jalankan:
apt update && apt install wget curl jq -y && \
wget --no-check-certificate [LINK_INSTALLER] && \
chmod +x setup-bot && \
./setup-bot
```

📝 Proses Instalasi Interaktif

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
│  • Auto Downgrade     → target transaksi reseller/bulan    │
│  • HTTPS + SSL        → domain untuk webhook               │
└─────────────────────────────────────────────────────────────┘
</pre>

✅ Verifikasi Instalasi

```bash
# Cek status bot
systemctl status mt_bot

# Lihat log real-time
journalctl -u mt_bot.service -f

# Test ke bot di Telegram
# Kirim /start ke @nama_bot_anda
```

---

❓ FAQ

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

<table>
  <tr><th>Kebutuhan</th><th>Rekomendasi</th></tr>
  <tr><td>Ingin withdraw otomatis</td><td>OrderKuota Asli</td></tr>
  <tr><td>Ingin verifikasi cepat (&lt; 3 detik)</td><td>OrderKuota RFS atau Tripay</td></tr>
  <tr><td>Butuh banyak metode pembayaran (VA, Retail)</td><td>Tripay</td></tr>
  <tr><td>Simple dan gratis</td><td>Tokopay</td></tr>
  <tr><td>All-in-one</td><td>Setup semua 4 gateway!</td></tr>
</table>

</details>

---

🆕 Roadmap & Request Fitur

In Progress / Planned

<table>
  <tr>
    <td>📊</td>
    <td>Panel Web monitoring (opsional)</td>
  </tr>
  <tr>
    <td>🌐</td>
    <td>Multi-language support (EN/ID)</td>
  </tr>
  <tr>
    <td>📎</td>
    <td>Export transaksi ke CSV/Excel</td>
  </tr>
  <tr>
    <td>💳</td>
    <td>Integrasi payment gateway lain (Xendit, Midtrans)</td>
  </tr>
  <tr>
    <td>🔔</td>
    <td>Notifikasi via Discord/WhatsApp</td>
  </tr>
</table>

Request Fitur

Punya ide fitur yang belum ada? Sampaikan! Saya sangat terbuka dengan custom request untuk meningkatkan value bot ini.

---

📞 Kontak & Order

<div align="center">

🤝 Siap Automasi Bisnis VPN Anda?

<table>
  <tr>
    <td align="center">
      <a href="https://t.me/mehonk_cs">
        <img src="https://img.shields.io/badge/Telegram-@mehonk_cs-blue?style=for-the-badge&logo=telegram" width="300">
      </a>
    </td>
  </tr>
</table>

<pre>
1. Kirim IP VPS Anda ke @mehonk_cs
2. Saya buatkan lisensi (3 hari trial FREE)
3. Saya berikan link installer + API KEY
4. Jalankan 1 perintah install
5. Bot siap digunakan!
</pre>

---

"Sewa lisensi, install 1 menit, bisnis auto pilot!"

🚀 MT-BOT — Simple, Powerful, Affordable

---

<sub>© 2024-2025 MT-BOT — Premium Telegram Bot Solution for VPN Business</sub>


<sub>All rights reserved.</sub>

</div>
</body>
</html>
