📄 README.md
markdown
Kopyala
Düzenle
# GNB Transfer - Web Sitesi Projesi

**GNB Transfer**, Türkiye genelinde turizm ve havalimanı transfer hizmetleri sunan profesyonel bir firmadır.  
Bu proje, firmanın dijital varlığını modern, çok dilli ve tam yönetilebilir bir yapıyla temsil eder.

## 🌍 Proje Özellikleri

- ✅ Çok dilli destek: Türkçe, İngilizce, Arapça, Rusça
- ✅ İstanbul ve çevresi için transfer ve tur hizmetleri
- ✅ Dinamik rota ve fiyat yönetimi
- ✅ Kullanıcı yorum sistemi
- ✅ Blog ve galeri alanı
- ✅ Tam mobil uyumlu tasarım
- ✅ Stripe ödeme altyapısına hazır
- ✅ Admin panel ile içerik ve rezervasyon yönetimi

---

## 🧱 Proje Yapısı

📦 GNB_Transfer
├── frontend/ # Web sitesinin kullanıcı arayüzü
├── backend/ # Node.js tabanlı API sistemi
├── admin-panel/ # Yönetim paneli (React)
├── assets/ # Görsel ve video dosyaları
├── db/ # Veritabanı yedeği (SQL)
├── .env.example # Ortam değişkeni örnek dosyası
└── README.md # Proje tanıtım dosyası

yaml
Kopyala
Düzenle

---

## 🛠 Kurulum ve Başlatma

### 1. Ortam Değişkenlerini Ayarla

`.env.example` dosyasını `.env` olarak kopyalayın ve içerikleri kendi değerlerinizle doldurun.

```bash
cp .env.example .env
2. Backend Kurulumu
bash
Kopyala
Düzenle
cd backend
npm install
npm start
3. Admin Panel Kurulumu
bash
Kopyala
Düzenle
cd admin-panel
npm install
npm start
4. Frontend Kurulumu
bash
Kopyala
Düzenle
cd frontend
npm install
npm start
🔐 Güvenlik
API istekleri JWT ile korunmaktadır.

Admin paneline sadece giriş yapmış kullanıcılar erişebilir.

Ayrıca API Key katmanı ile dış erişim kontrollü sağlanır.

📩 İletişim
Bu proje GNB Transfer adına özel olarak hazırlanmıştır.
Her türlü teknik destek ve güncelleme için proje yöneticiniz ile iletişime geçebilirsiniz.

🧑‍💻 Geliştirici Notu
Bu proje, modern web teknolojileri kullanılarak en iyi kullanıcı deneyimini sağlamak amacıyla hazırlanmıştır.
Yorumlarınız ve katkılarınız bizim için değerlidir.
