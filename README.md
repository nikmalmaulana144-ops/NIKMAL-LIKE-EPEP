<div align="center">

<img src="https://cdn.phototourl.com/member/2026-10-07-da0318ae-9d20-47d8-82b4-0bc72973e9b0.png" width="120" height="120" style="border-radius: 50%;" alt="malz codex"/>

# MALZ CODEX

### Free Fire Like API — Premium Edition

*Cepat · Aman · Unlimited*

<br>

[![Telegram](https://img.shields.io/badge/Telegram-@malzwithyou-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/malzwithyou)
[![TikTok](https://img.shields.io/badge/TikTok-@malzwithyou-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@malzwithyou)
[![YouTube](https://img.shields.io/badge/YouTube-@Nikmal__hsb-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Nikmal_hsb)
[![GitHub](https://img.shields.io/badge/GitHub-@ini__nikmal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ini_nikmal)

<br>

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.0-000000?style=flat-square&logo=flask&logoColor=white)
![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=flat-square)

</div>

---

<div align="center">

## ✦ Tentang

**MALZ CODEX Like API** adalah layanan pengiriman like Free Fire berkecepatan tinggi dengan dashboard web modern, sistem auto-like harian, database pemain real-time, dan master admin panel lengkap.

Dibangun pakai **Python 3.11 + Flask + aiohttp** — dirancang untuk performa maksimal, keamanan, dan kemudahan deploy.

</div>

---

## ✦ Fitur

<table>
<tr>
<td width="50%" valign="top">

### 🚀 Core
- ✅ Kirim like ke UID Free Fire (semua server)
- ✅ Multi-server support: BD / IND / BR / US / SAC / NA
- ✅ Parallel like engine (200 concurrent)
- ✅ Auto JWT refresh setiap 7 jam
- ✅ Auto-like harian via scheduler (04:10 pagi)
- ✅ Info fetch harian ke database (04:30 pagi)

</td>
<td width="50%" valign="top">

### 🎨 Dashboard
- ✅ Web UI user — kirim like manual
- ✅ Master admin panel — full control
- ✅ Real-time player info + riwayat harian
- ✅ Kuota harian user (1 UID/hari)
- ✅ Master key unlimited
- ✅ Blocklist UID
- ✅ Dark mode premium UI
- ✅ Fully responsive (mobile + desktop)

</td>
</tr>
</table>

---

## ✦ Endpoint API

### 🌐 User Endpoint

```http
GET  /malz&like?uid={uid}&key={key}
GET  /malz&like?uid={uid}&key={key}&server_name={server}
GET  /like?uid={uid}&server_name={server}&key={key}