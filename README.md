# Advanced-Telegram-Hit-Bot-with-Proxy-URL-Rotation-Async-Fast-

# 🚀 Advanced Telegram Hit Bot

Bu proje, yüksek hızda async HTTP istekleri yapabilen, proxy ve URL rotasyonu destekleyen gelişmiş bir **Telegram kontrollü hit botudur**. Tamamen Python ile yazılmıştır ve tamamen özelleştirilebilir.

---

## 🧠 Özellikler

- ⚡ **Async/Aiohttp destekli hızlı istek sistemi**
- 🔁 Proxy ve URL rotasyonu
- 🧹 Proxy auto-ban sistemi (başarısızlık sayısı bazlı)
- 🧮 Gerçek zamanlı istatistikler (/stats komutu)
- 🧾 Log kaydı ve Telegram'dan log dosyası gönderimi
- 💬 Telegram bot komutlarıyla tüm kontrol
- ✅ Başlat / ⛔ Durdur / 📊 İstatistik / 📁 Log çekme
- 📨 Opsiyonel e-posta ve Discord bildirim sistemi
- 🔒 Sadece belirlenen kullanıcıdan komut kabul eder (Güvenli)

---

## 🛠️ Kurulum

1. Gerekli modülleri kur:
```bash
pip install aiohttp python-telegram-bot

2. proxy.txt → Proxy listeni buraya koy
urls.txt → Hedef URL’leri buraya ekle


3. config alanındaki:



TELEGRAM_TOKEN (bot token)

CHAT_ID (kendi Telegram ID)


ayarlarını doldur.


---

🚦 Komutlar

/start → Botu başlat

/stop → Botu durdur

/stats → Hit istatistiklerini göster

/getlog → Log dosyasını gönder

/addurl, /delurl, /clearurls, /urls

/addproxy, /delproxy, /clearproxies, /proxies


