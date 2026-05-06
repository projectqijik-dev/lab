# ⚗️ Tarih Laboratuvarı — lab.kirkyama.uk

**İnteraktif haritalar, tarihsel simülasyonlar ve strateji oyunlarıyla tarihe dokunun.**

Özel Batman Boğaziçi Koleji MTAL — 9. Sınıf Tarih Dersi  
Geliştirici: Murat Mutlu

---

## 📦 İçerik

| Kategori | Modül Sayısı |
|---|---|
| 🗺️ İnteraktif Haritalar | 17 |
| 🎮 Simülasyon & Strateji | 10 |
| 🛠️ Analitik Araçlar | 8 |
| **Toplam** | **35** |

---

## 🗂️ Dosya Yapısı

```
lab-site/
├── index.html              ← Ana sayfa (galeri + filtreleme)
├── modul.html              ← Modül çalıştırıcı (tüm modüller buradan açılır)
├── 404.html                ← GitHub Pages hata sayfası
├── css/
│   └── style.css           ← Tüm stiller
└── js/
    ├── main.js             ← Ana sayfa motoru (canvas, sayaç, grid, filtre)
    ├── motor.js            ← Modül çalıştırıcı (URL → HARITA_MOTORU[id])
    └── sinif9haritalar.js  ← Tüm modül fonksiyonları (window.HARITA_MOTORU)
```

---

## 🚀 GitHub Pages ile Yayınlama

1. Bu repoyu GitHub'a yükle
2. **Settings → Pages → Branch: main → / (root)** seç → **Save**
3. Birkaç dakika bekle
4. Siteniz: `https://KULLANICI_ADI.github.io/REPO_ADI/`

### Özel Domain (lab.kirkyama.uk) Bağlama

1. GitHub Pages ayarlarında **Custom domain** alanına `lab.kirkyama.uk` yaz
2. Domain sağlayıcında DNS ayarları:
   ```
   CNAME  lab  →  KULLANICI_ADI.github.io
   ```
3. **Enforce HTTPS** kutusunu işaretle

---

## 🛠️ Teknoloji Yığını

- **Saf HTML/CSS/JavaScript** — framework yok
- **Leaflet.js 1.9.4** — interaktif haritalar
- **Font Awesome 6.5** — ikonlar
- **Google Fonts** — Cinzel, Crimson Pro
- **Canvas API** — hero animasyonu

---

## 📝 Lisans

Tüm hakları saklıdır. Eğitim amaçlı kullanım için izin alınız.  
© 2025–2026 Murat Mutlu — Özel Batman Boğaziçi Koleji MTAL
