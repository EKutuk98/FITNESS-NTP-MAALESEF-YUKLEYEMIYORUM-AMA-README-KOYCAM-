# FITNESS-NTP-MAALESEF-RESIM YUKLEYEMIYORUM GITHUB BİR ANDA ERROR VERDİ

# 🏋️ Fitness Takip Sistemi

Sporcu ve antrenman yönetimine odaklanan, kapsamlı ilerleme takibi ve gamification özellikleri içeren masaüstü fitness platformu. PyQt5 ile geliştirilmiş, SQLite veritabanı destekli, QPainter tabanlı grafiklerle donatılmıştır.

**🔐 Giriş Bilgileri:**
- Admin: `admin` / `admin123`
- Personel: `personel` / `personel123`

---





---

## 📋 Özellikler

---

### 🏠 Dashboard

- Toplam sporcu, antrenman, aktif program KPI kartları
- QPainter bar grafik (haftalık antrenman dağılımı)
- Pasta grafik (antrenman türü dağılımı)
- Son aktiviteler feed



---

### 🏃 Sporcular

- Sporcu ekleme, düzenleme, soft-delete
- Ad, yaş, kilo, boy, hedef, cinsiyet bilgileri
- Sporcu bazlı genel profil görünümü
- Anlık arama



---

### 💪 Antrenmanlar

- Antrenman kaydı oluşturma (tür, süre, kalori, tarih, not)
- Tamamlandı / Planlandı / İptal durumları
- Sporcu bazlı filtreleme
- Anlık arama


---

### 📋 Takipler

- Günlük kalori, su tüketimi, uyku süresi, kilo takibi
- Tarih bazlı kayıt ekleme ve düzenleme
- KPI kartları ile anlık özet



---

### 📅 Programlar

- Haftalık antrenman programı oluşturma
- Programa egzersiz ekleme (gün, egzersiz, set, tekrar)
- Program aktif/pasif toggle
- Sporcu bazlı program atama



---

### 📏 Vücut Ölçüm

- Bel, kalça, göğüs, kol, bacak ölçümü kayıtları
- Tarih bazlı karşılaştırma
- QPainter çizgi grafik ile değişim takibi


---

### 🎯 Hedefler

- Hedef tanımlama (tür, hedef değer, bitiş tarihi)
- İlerleme yüzdesi takibi
- Tamamlandı / Devam Ediyor / Başarısız durumları
- Hedef ayarlama diyaloğu



---

### 🔥 Streak (Seri Takip)

- Günlük antrenman serisini otomatik hesaplama
- En uzun seri rekoru
- Seri kırılma uyarısı



---

### 🥗 Beslenme

- Öğün kaydı (kahvaltı, öğle, akşam, ara öğün)
- Kalori ve makro besin (protein, karb, yağ) takibi
- Günlük hedef karşılaştırması
- QPainter makro dağılım grafiği


---

### 🥦 Besinler

- Besin veritabanı yönetimi
- Kalori ve makro bilgileri kayıt
- Besin ekleme, düzenleme, silme
- Anlık arama



---

### 📈 İlerleme

- Sporcu bazlı kilo değişim grafiği (QPainter Line Chart)
- Hacim (volüm) analizi sekmesi
- Tarih aralığı seçimi



---

### 📋 Haftalık Özet

- Seçilen haftanın antrenman, kalori, su, uyku özetleri
- KPI kartları ile haftalık karşılaştırma
- Excel özet raporu export



---

### 🏅 Rozetler

- Otomatik rozet kazanma sistemi (50 antrenman, ilk hedef vb.)
- Kazanılan / henüz kazanılmamış rozet listesi
- XP puanı gösterimi



---

### 🏆 Liderlik Tablosu

- Sporcuları toplam antrenman sayısına göre sıralama
- XP bazlı genel sıralama



---

### 🏋️ 1RM Hesaplama

- Bir tekrar maksimum ağırlık hesaplayıcı (Epley formülü)
- Egzersiz, kullanılan ağırlık ve tekrar sayısı girişi
- Sonuç anlık gösterim


---

### 🕸️ Radar Analiz

- Sporcu performans radari (QPainter Radar Chart)
- Güç, dayanıklılık, esneklik, hız, denge eksenleri
- İki sporcu karşılaştırma modu



---

### 🔬 Gelişmiş Analiz

- Aylık karşılaştırmalı antrenman ve kalori grafikleri
- En yoğun günler analizi
- Bölgesel kas grubu dağılımı



---

### 📄 Şablonlar

- Hazır antrenman şablonları (Push/Pull/Legs vb.)
- Şablon bazlı program oluşturma
- Şablon aktif/pasif toggle



---

### ⚙️ Sistem Ayarları

- Uygulama adı, varsayılan kalori hedefi, su hedefi
- Hatırlatıcı saati ayarı
- DB yedekleme
- Tema ve genel tercihler



---

### 📊 Excel / Rapor

- Excel özet raporu export (sporcular, antrenmanlar, beslenme)
- CSV dışa aktarma
- Sistem geneli rapor



---

## ❓ Final Soruları

### Sistemde hangi kullanıcılar veya nesneler vardır?

**Kullanıcı Türleri:**
- **Admin** — Tam yetkili; kullanıcı yönetimi, sistem ayarları, tüm modüller
- **Personel** — Antrenör; sporcu, antrenman, program, beslenme takip işlemleri

**Ana Nesneler / Varlıklar:**
- **Sporcu** — sporcu_id, ad, yaş, kilo, boy, hedef, cinsiyet, durum
- **Antrenman** — antrenman_id, sporcu, tür, süre, kalori, tarih, not, durum
- **Takip** — tarih, sporcu, kilo, kalori, su, uyku
- **Program** — program_id, ad, sporcu, haftalık antrenman planı
- **Vücut Ölçüm** — tarih, sporcu, bel, kalça, göğüs, kol, bacak
- **Hedef** — hedef_id, sporcu, tür, hedef değer, mevcut değer, bitiş tarihi, durum
- **Beslenme** — kayit_id, sporcu, öğün, besin, kalori, protein, karb, yağ, tarih
- **Besin** — besin_id, ad, kalori, protein, karb, yağ
- **Rozet** — rozet_id, ad, açıklama, ikon, XP, kriter türü, eşik değeri
- **Streak** — sporcu bazlı günlük seri sayacı
- **1RM Kaydı** — sporcu, egzersiz, ağırlık, tekrar, hesaplanan 1RM
- **Şablon** — şablon_id, ad, açıklama, egzersiz listesi, durum
- **Kullanıcı** — kullanici_id, ad, kullanıcı adı, SHA256 parola, rol
- **Sistem Ayarları** — anahtar-değer çifti tablosu

---

### Kullanıcı sistemde hangi işlemleri gerçekleştirebilir?

**Admin:**
- Kullanıcı ekleyebilir, düzenleyebilir, pasife alabilir
- Sistem ayarlarını güncelleyebilir
- DB yedeği alabilir
- Excel ve CSV raporu export edebilir
- Aşağıdaki tüm personel işlemlerini yapabilir

**Personel (Antrenör):**
- Sporcu ekleyebilir, düzenleyebilir, pasife alabilir, arayabilir
- Antrenman kaydı oluşturabilir, güncelleyebilir, silebilir
- Günlük takip (kilo, kalori, su, uyku) kaydedebilir
- Haftalık program oluşturabilir ve sporculara atayabilir
- Vücut ölçümü ekleyebilir ve ilerleme grafiğini görüntüleyebilir
- Hedef tanımlayabilir ve ilerleme güncelleyebilir
- Beslenme kaydı ve besin veritabanını yönetebilir
- Rozet ve liderlik tablosunu görüntüleyebilir
- 1RM hesaplaması yapabilir
- Radar ve gelişmiş analiz grafiklerini görüntüleyebilir
- Antrenman şablonu oluşturabilir ve kullanabilir
- Haftalık özet ve Excel raporunu görüntüleyebilir / export edebilir

---

## 🖥️ Teknolojiler

| Teknoloji | Kullanım Alanı |
|-----------|----------------|
| Python 3.9+ | Ana programlama dili |
| PyQt5 | GUI Framework |
| SQLite3 | Veritabanı yönetimi (`@contextmanager`) |
| QPainter | Tüm grafikler (Bar, Pie, Line, Radar) |
| hashlib (SHA256) | Şifre güvenliği |
| openpyxl / csv | Rapor export |
