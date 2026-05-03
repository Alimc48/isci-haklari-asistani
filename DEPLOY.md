# 🚀 GitHub'a Yayınlama Rehberi (Adım Adım)

Bu rehber, projeni **5-10 dakika içinde** dünyaya açmana yardım edecek. Programcı olmana gerek yok.

## Sonuç ne olacak?

- `https://senin-kullanici-adin.github.io/isci-haklari-asistani/` gibi bir link
- Tamamen ücretsiz
- Sınırsız ziyaretçi
- Mobil uyumlu
- Sen istediğin zaman güncelleyebilirsin

---

## ADIM 1: GitHub Hesabı Aç (eğer yoksa)

1. **github.com** adresine git
2. Sağ üstte **"Sign up"** tıkla
3. Email, şifre, kullanıcı adı seç
4. Email'ini onayla

> 💡 **Kullanıcı adı önemli** — link'in bir parçası olacak. Kısa ve hatırlanır seç. Örn: `mehmet-yilmaz`

---

## ADIM 2: Yeni Repo Oluştur

1. Sağ üstte **"+"** ikonuna tıkla → **"New repository"** seç
2. Şu bilgileri gir:
   - **Repository name**: `isci-haklari-asistani`
   - **Description**: `Türkiye'deki çalışanlar için ücretsiz hak analizi aracı`
   - **Public** seçili olsun (Free GitHub Pages için zorunlu)
   - ✅ **"Add a README file"** kutusunu işaretle
   - ✅ **"Choose a license"** → **MIT License** seç
3. **"Create repository"** tıkla

---

## ADIM 3: Dosyaları Yükle

1. Yeni açılan repo sayfasında **"Add file"** → **"Upload files"** tıkla
2. Bilgisayardan şu dosyaları sürükle-bırak:
   - `Isci_Haklari_Asistani.html` ← **DİKKAT: Adını `index.html` olarak değiştir!**
   - `README.md` (eğer henüz yoksa)
   - `LICENSE`
3. Sayfanın altında **"Commit changes"** tıkla

> 💡 **Neden `index.html`?** GitHub Pages otomatik olarak `index.html` dosyasını anasayfa yapar.

### `Isci_Haklari_Asistani.html` → `index.html` nasıl yaparım?

**Yöntem A (Bilgisayarda):** Dosyaya sağ tık → "Yeniden adlandır" → `index.html`

**Yöntem B (GitHub'da yükledikten sonra):** 
1. Yüklenen `Isci_Haklari_Asistani.html` dosyasına tıkla
2. Sağ üstte kalem ikonuna tıkla
3. Dosya adını üstten `index.html` yap
4. "Commit changes"

---

## ADIM 4: GitHub Pages'i Aç

1. Repo sayfasında üstte **"Settings"** sekmesine tıkla
2. Sol menüde aşağıda **"Pages"** seç
3. **"Source"** kısmında:
   - **Branch**: `main` seç
   - **Folder**: `/ (root)` seç
4. **"Save"** tıkla

5-10 dakika içinde sayfan hazır olur. Sayfanın üstünde yeşil bir kutuda link görünecek:

```
✅ Your site is live at https://senin-kullanici-adin.github.io/isci-haklari-asistani/
```

---

## ADIM 5: Test Et

1. Verilen linke tıkla
2. Sitenin açıldığını kontrol et
3. Telefonunda da aç (link'i WhatsApp'tan kendine gönder)

🎉 **Bitti!** Artık dünyaya açıksın.

---

## 🎨 Bonus: Daha İyi Görünüm

### Sosyal medya paylaşım resmi (OG Image)

Birisi linkin WhatsApp'tan paylaşırsa, bir kart görsel görünür. Kendi görselini yapabilirsin:

1. **Canva** veya **Figma**'da 1200×630 boyutunda görsel hazırla
2. Şu içerik öner:
   - Başlık: "İşçi Hakları Asistanı"
   - Alt başlık: "Haklarını bil, hakkını ara"
   - Logo veya ⚖️ emojisi
3. `og-image.png` adıyla kaydet
4. GitHub repo'na yükle
5. `index.html` içinde şu satırları kendi link'inle güncelle:

```html
<meta property="og:image" content="https://kullanici-adin.github.io/isci-haklari-asistani/og-image.png">
```

### Custom Domain (kendi alan adın)

Eğer `iscihaklariasistani.com` gibi kendi domainin varsa:

1. Domain sağlayıcında DNS ayarlarına git
2. Şu CNAME kaydını ekle:
   ```
   www → kullanici-adin.github.io
   ```
3. GitHub'da Settings → Pages → "Custom domain" kısmına `www.iscihaklariasistani.com` yaz
4. ✅ "Enforce HTTPS" işaretle

> 💡 Alan adı 1 yıllık ortalama 50-100 ₺. Namecheap, GoDaddy, Turhost iyi sağlayıcılar.

---

## 🔄 Güncelleme Yapma

Sonradan dosyayı güncellemek istersen:

1. Repo sayfasında `index.html` dosyasına tıkla
2. Sağ üstte kalem ikonuna tıkla
3. Değişiklik yap
4. "Commit changes" tıkla
5. 1-2 dakika sonra siten otomatik güncellenir

Veya yeni dosya yüklemek için "Add file" → "Upload files" yine çalışır.

---

## 📊 Ziyaretçi Sayısı Görme

GitHub Pages varsayılan olarak istatistik sunmaz. Ücretsiz seçenekler:

- **Plausible Analytics** (gizliliğe saygılı, ücretsiz başlangıç)
- **Google Analytics** (en yaygın, ücretsiz ama kullanıcı izleme)
- **Umami** (açık kaynak)

Hiçbiri zorunlu değil. Eğer eklemek istersen, sağladıkları script'i `index.html`'in `</body>` etiketinden hemen önce yapıştır.

---

## ❓ Sık Sorulan Sorular

**S: Site açılmadı, ne yapmalıyım?**  
C: 10 dakika bekle. Hâlâ açılmıyorsa: Settings → Pages'e git, branch'in `main` ve folder'ın `/ (root)` olduğunu kontrol et. Dosya adı kesinlikle `index.html` mi?

**S: API key güvenli mi?**  
C: Sen API key'ini repo'ya KOYMUYORSUN. Her kullanıcı kendi tarayıcısında kendi key'ini saklıyor. Sen sadece HTML'i yayınlıyorsun.

**S: Trafik çok artarsa para vermem gerekir mi?**  
C: Hayır. GitHub Pages ücretsiz hesapta **ayda 100 GB** trafik veriyor. Senin uygulaman ~200 KB. Yani **ayda 500.000 ziyaretçi** ücretsiz.

**S: GitHub Pages alternatif var mı?**  
C: Evet, hepsi de ücretsiz:
- **Cloudflare Pages** — en hızlı CDN
- **Netlify** — en kolay
- **Vercel** — modern, geliştirici dostu

Hepsi aynı mantıkta çalışır.

---

## 🎯 Yayın Sonrası Yapılacaklar

Sıralı bir kontrol listesi:

- [ ] Site link'i bir tarayıcıda açılıyor
- [ ] Telefonda açılıyor (WhatsApp'tan kendine yolla)
- [ ] AI key olmadan tüm offline özellikler çalışıyor
- [ ] AI key ile patron simülatörü çalışıyor
- [ ] Hesaplamalar mantıklı sayılar veriyor
- [ ] README.md güzel görünüyor (GitHub repo sayfasında)
- [ ] LICENSE dosyası var
- [ ] Custom domain ayarladın (opsiyonel)
- [ ] OG image yaptın (opsiyonel)
- [ ] Bir tweet attın 🎉

---

**Yardım gerekirse:** GitHub'da repo'nun "Discussions" sekmesini aç, oradan soru sor.

İyi yayınlar! 🚀
