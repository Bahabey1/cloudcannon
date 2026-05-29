# Efekaya Emlak – Netlify Deploy

## 🚀 Netlify'a Yükleme (2 Adım)
1. https://app.netlify.com/drop adresine gidin
2. Bu **dist** klasörünün tamamını sayfaya sürükleyip bırakın

## 📁 Dosyalar
- `index.html`  → Tüm site (HTML + CSS + JS)
- `hero.mp4`    → Hero video
- `netlify.toml`→ Netlify ayarları (otomatik)

## 📦 Yayın Hazırlığı
- `dist/` klasörü hazır: `dist/index.html`, `dist/hero.mp4`, `dist/netlify.toml`

## � Yerel ve Alternatif Platform Çalıştırma
Bu proje artık Node.js ile çalışan bir sunucuya sahiptir. Böylece admin panelinden yaptığın değişiklikler `data/listings.json` dosyasına kaydedilebilir.

1. Terminalde proje köküne gelin:
```bash
cd "c:\Users\Bahattin\Desktop\Yeni klasör"
```
2. Paketleri yükleyin:
```bash
npm install
```
3. Sunucuyu başlatın:
```bash
npm start
```
4. Siteyi açın:
- `http://localhost:8000/`
- Admin paneli için: `http://localhost:8000/admin/`

### Alternatif platform önerisi
Bu projeyi Netlify yerine şu platformlara deploy edebilirsin:
- Render
- Railway
- Fly.io
- Heroku

Bu platformlar Node.js uygulamasını destekler ve `data/listings.json` dosyasına yazma işlemi çalışır.

## �📞 İletişim Bilgileri
- Tel: +90 532 401 03 11
- E-posta: gokmenogluemlak@hotmail.com
- Konum: https://share.google/7MXRarLQmEf2TcTkF

## 🔧 Özelleştirme
Tüm içerik `index.html` içindedir.
- Renkler: CSS `:root` bloğu
- İlanlar/linkler: `efekayaemlak.sahibinden.com`
- Telefon: `0532 401 03 11`

## 🛠️ Lokal Mock Admin Paneli
- Yerel test için admin giriş sayfası: `admin/login.html`
- Giriş bilgileri:
  - E-posta: `yigitjayra42@gmail.com`
  - Şifre: `bahabey01254`
- Başarılı giriş sonrası panel: `admin/mock-admin.html`
- Not: Bu mock panel sadece tarayıcıda çalışır. Değişiklikler sunucuya yazılmaz, ancak `JSON İndir` ile çıktıyı alabilirsiniz.
