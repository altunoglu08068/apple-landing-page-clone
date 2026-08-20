# 🍏 Apple Store Homepage Clone

Apple Store modern giriş sayfasının HTML5 ve CSS3 ile geliştirilen piksel odaklı tasarım klonudur. Projede Apple'ın minimalist, ferah arka planlı ve temiz tipografi yaklaşımı baz alınarak statik bir landing page oluşturulmuştur.

> ⚠️ **Yasal Uyarı / Disclaimer:** Bu proje yalnızca eğitim ve pratik amaçlı geliştirilmiştir. Görsel ve marka materyalleri Apple Inc.'e aittir.

---

## 🚀 Tamamlanan Özellikler

- [x] **Global Navigasyon Çubuğu (Navbar):**
  - Orijinal Apple SVG ikonları (Logo, Arama, Çanta)
  - `position: sticky` ile üstte sabitlenen yapı
  - `backdrop-filter: blur(20px)` ile buzlu cam (frosted glass) efekti
  - Flexbox ile dengeli aralık ve link hover geçişleri

- [x] **Duyuru & Kampanya Bandı (Promo Ribbon):**
  - Eğitime özel kampanya metni ve `<sup>` kullanımı
  - Inline SVG (çember içi artı ikonu) ile dikey hizalı etkileşimli bağlantı

- [x] **Store Karşılama Başlığı (Store Header):**
  - Büyük "Store" tipografisi
  - Sağa yaslı slogan ve harici uzman/mağaza yönlendirme bağlantıları
  - Flexbox `space-between` ile iki yana dağıtılmış düzen

- [x] **Yatay Kaydırılabilir Ürün/Kategori Vitrini (Chapter Navigation):**
  - Mac, iPhone, iPad, Apple Watch, AirPods, AirTag, Apple TV 4K, HomePod, Aksesuarlar
  - `overflow-x: auto` ve gizlenmiş kaydırma çubuğu ile akıcı yatay kaydırma
  - `align-items: flex-end` ile alt tabana hizalı dengeli kart yapısı
  - Hover anında hafif büyüme efekti (`transform: scale(1.05)`)

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5** (Semantik etiketler, Inline SVG)
- **CSS3** (Flexbox, Backdrop Filter, CSS Reset, Custom Transitions)

---

## ▶️ Projeyi Görüntüleme

Bu proje statik bir web sayfasıdır. Görüntülemek için:

1. Proje klasöründeki `index.html` dosyasına çift tıklayarak doğrudan herhangi bir tarayıcıda açabilirsiniz.
2. Veya VS Code kullanıyorsanız **Live Server** eklentisi ile tek tıkla çalıştırabilirsiniz.

---

## 📁 Proje Yapısı

```text
apple-landing-page-clone/
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── images/
│       └── nav-section1/
└── README.md