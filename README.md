# ⚖️ İşçi Hakları Asistanı

> **Türkiye'deki çalışanlar için ücretsiz, açık kaynaklı hak analizi ve kanıt yönetim aracı.**

Çalışma koşullarını anlat — hak ihlallerini tespit et, kıdem ve ihbar tazminatını 2026 tarifesiyle hesapla, dilekçeni hazırla, kanıtlarını topla.

[**🔗 Canlı Demo**](https://kullanici-adi.github.io/isci-haklari-asistani/) · [**📱 Telefonda Aç**](https://kullanici-adi.github.io/isci-haklari-asistani/) · [**🐛 Sorun Bildir**](https://github.com/kullanici-adi/isci-haklari-asistani/issues)

---

## 📸 Ekran Görüntüleri

> Buraya 3-4 ekran görüntüsü ekleyin (yer tutucu)

| Hak Analizi | Senaryo Karşılaştırma | Kanıt Klasörü |
|---|---|---|
| ![Analiz](docs/screenshot-analiz.png) | ![Senaryo](docs/screenshot-senaryo.png) | ![Kanıt](docs/screenshot-kanit.png) |

---

## 🎯 Bu Proje Kim İçin?

Türkiye'de **kafası karışık, hakkını bilmeyen, avukata gücü yetmeyen** her çalışan için. Sektör fark etmez:

- Fabrikada haftada 60 saat çalışıp fazla mesai ücreti alamayan işçi
- Mağazada haksız yere işten çıkarılan tezgahtar
- Restoranda maaşı geç ödenen garson
- Ofiste mobbing yaşayan çalışan
- İstifa edip kıdem tazminatı alabileceğini bilmeyen kişi

---

## ✨ Özellikler

### 🆓 Offline Mod (API key gerekmez)
Tarayıcıda çalışır, internet bile şart değil. Hiçbir veri sunucuya gitmez.

- **⚖️ Hak Analizi** — 10+ farklı ihlal türünü tespit eden rule-based motor
- **💰 Hesaplayıcı** — 2026 kıdem tavanı (64.948,77 ₺/yıl) uygulanmış doğru formüller
- **📈 Senaryo Karşılaştırma** — "Bugün vs 6 ay sonra ayrılırsam" tablosu
- **📁 Kanıt Klasörü** — Mesai kayıtları, tanık bilgileri, fotoğraflar, olay günlüğü; tek tıkla avukata teslim edilebilir paket olarak indirilir
- **📊 Hak Takip Panom** — İşe başlangıç tarihinden itibaren canlı kıdem/ihbar/izin takibi
- **⏰ Zamanaşımı Alarmı** — Hangi alacağında kaç gün kaldı (5 yıl, 10 yıl, 1 ay)
- **🎭 Patron Simülatörü (Offline)** — Senaryo ağacı tabanlı, 7 konu × 4 patron tipi, 48 farklı diyalog node'u, puanlı geri bildirim
- **📝 Dilekçe Taslağı** — Otomatik hazırlanmış, kanun maddesi referanslı

### 🤖 AI Mod (ücretsiz Google API key ile)
Yukarıdakilerin hepsi + ekstra:

- **🎭 Patron Simülatörü (AI)** — Gerçek diyalog, serbest yazışma
- **📄 Belge Analizi** — Sözleşme/bordro fotoğrafı yükle, AI çelişkileri ve sorunları söylesin
- **💬 AI Sohbet** — Analiz sonrası serbest soru-cevap

---

## 🚀 Hızlı Başlangıç

### Yöntem 1: Sadece kullan
1. [**📥 Tek dosyayı indir**](https://github.com/kullanici-adi/isci-haklari-asistani/raw/main/Isci_Haklari_Asistani.html)
2. Çift tıkla, tarayıcıda açılsın
3. Bitti — internete bağlı olmasan bile çalışır

### Yöntem 2: Online kullan
[**isci-haklari-asistani.com**](https://kullanici-adi.github.io/isci-haklari-asistani/) (GitHub Pages üzerinden)

### Yöntem 3: Kendi sitende host et
Bu projeyi fork'layıp GitHub Pages'i etkinleştirmen yeterli. 5 dakikada kendi domainin altında çalışır. Bkz: [Yayınlama Rehberi](#-kendi-sitende-yayınlama)

---

## 📖 Yasal Dayanaklar

Tüm hesaplamalar Türk İş Hukuku'na dayanır ve 2026 tarifesi uygulanır:

| Konu | Kaynak |
|---|---|
| Kıdem tazminatı | 1475 sayılı İş Kanunu m.14 (tavan: **64.948,77 ₺/yıl**, 2026/H1) |
| İhbar tazminatı | 4857 sayılı İş Kanunu m.17 |
| Fazla mesai | 4857/m.41 (haftalık 45 saat üstü, %50 zamlı) |
| Yıllık izin | 4857/m.53 (1-5y: 14g, 5-15y: 20g, 15+y: 26g) |
| Asgari ücret (brüt) | 33.030 ₺ (2026) |
| Damga vergisi | ‰7,59 |
| Zamanaşımı | TBK m.146 (5 yıl), 7036 sayılı kanun (kıdem 5 yıl, 25.10.2017 sonrası fesihler için) |

> ⚠️ **Hukuki danışmanlık değildir.** Bu uygulama bilgilendirme amaçlıdır. Önemli kararlar için bir avukat veya İŞKUR'a danışın.

---

## 🛠️ Teknoloji

- **Saf HTML/CSS/JavaScript** — hiçbir framework yok, hiçbir bağımlılık yok
- **Tek dosya** — 184 KB, çift tıkla açılır
- **localStorage** — tüm veriler tarayıcıda, hiçbir sunucuya gitmez
- **Google Gemini API** (opsiyonel) — sadece AI özellikleri için
- **Mobil uyumlu** — telefonda, tablette, masaüstünde aynı

---

## 🌍 Kendi Sitende Yayınlama

GitHub Pages ile **5 dakikada ücretsiz** kendi sitenizi açabilirsiniz:

1. **GitHub'a giriş yap** — github.com'da hesap aç (varsa atla)
2. **Bu projeyi fork'la** — sağ üstte "Fork" butonuna tıkla
3. **Settings → Pages** sekmesine git
4. **Source** olarak `main` branch'i seç, **Save** tıkla
5. 1-2 dakika bekle — GitHub sana `https://kullanici-adin.github.io/isci-haklari-asistani/` linkini verecek

Detaylı rehber: [docs/DEPLOY.md](docs/DEPLOY.md)

---

## 💡 AI Modu Nasıl Aktif Edilir?

1. https://aistudio.google.com/app/apikey adresine git
2. Google hesabınla giriş yap
3. "Create API Key" tıkla, oluşan anahtarı kopyala
4. Uygulamada üst sağdaki rozete tıkla → AI moduna geç → anahtarı yapıştır

**Maliyet: 0 ₺.** Google'ın ücretsiz tier'ı günde 1.500 isteğe kadar ücretsizdir, kart bilgisi istemez.

---

## 🤝 Katkı

Pull request'ler memnuniyetle kabul edilir. Büyük değişiklikler için lütfen önce bir issue açın.

Özellikle yardım edebilecekleriniz:
- **🏛️ Hukuki gözden geçirme** — Avukatsanız, hesaplamaları ve dilekçe taslağını inceleyin
- **🌐 Çeviri** — Arapça, Kürtçe, İngilizce versiyonlar (Türkiye'deki yabancı işçiler için)
- **📝 Senaryo ağacı genişletme** — Patron Simülatöründe yeni konular ekleme
- **🎨 Tasarım** — Ekran görüntüleri, OG image, tanıtım materyalleri
- **🐛 Hata bildirimi** — Issue açın, ekran görüntüsüyle

---



---

## 🙏 Teşekkürler

Bu proje, Türkiye'de hakkını bilmediği için kaybeden milyonlarca işçi için yapıldı.

Hesap formüllerinde hata bulan, hukuki nüansları paylaşan, kanun değişikliklerini bildiren herkese teşekkürler.

---

## 📞 İletişim

- **Email**: alimceler123@gmail.com

---

**Made with ❤️ for Turkish workers.**
