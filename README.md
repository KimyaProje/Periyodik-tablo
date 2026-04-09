# ⚛ İnteraktif Periyodik Tablo — Kurulum Rehberi

## Dosyalar
- `index.html` → Ana periyodik tablo (tüm 118 element)
- `element.html` → Her element için detay sayfası (3D animasyon + grafikler)
- `elements_data.js` → 118 elementin veri dosyası
- `qr-generator.html` → QR kod üretici + yazdırma sayfası

---

## GitHub Pages'e Yükleme (Ücretsiz, ~10 dakika)

### 1. GitHub hesabı aç
- https://github.com adresine git → "Sign up" → hesap oluştur

### 2. Yeni repo oluştur
- Sağ üstte "+" → "New repository"
- Repository name: `periodictable`
- Public seç
- "Create repository" tıkla

### 3. Dosyaları yükle
- "uploading an existing file" linkine tıkla
- 4 dosyayı (index.html, element.html, elements_data.js, qr-generator.html) sürükle bırak
- "Commit changes" tıkla

### 4. GitHub Pages'i aç
- Repo sayfasında "Settings" → sol menüde "Pages"
- Source: "Deploy from a branch"
- Branch: "main" seç → "Save"
- 2-3 dakika bekle

### 5. Site URL'in
`https://KULLANICI_ADIN.github.io/periodictable/`

---

## QR Kodları Üretme

1. `qr-generator.html` sayfasını aç
2. URL kutusuna kendi GitHub Pages adresini yaz
3. "QR Üret" butonu → 118 QR otomatik oluşur
4. "Yazdır" → A4'e sığar, kes ve modele yapıştır

---

## Netlify Alternatifi (Daha kolay)
1. https://netlify.com → "Deploy manually"
2. 4 dosyayı sürükle bırak
3. Anında canlı URL alırsın
