# 🌐 Portfolyo Web Sitesi - Türkçe Versiyon

Kocaeli Üniversitesi Yazılım Mühendisliği öğrencisi ve Full Stack Developer olarak yolculuğumu sergileyen modern, responsive bir portfolyo web sitesi.

## 🚀 Canlı Demo
[Portfolyoyu Görüntüle](https://kemalyavas.github.io/Portfolyo/)



## 🎯 Özellikler

### Ana Özellikler
- **Responsive Tasarım**: Tüm cihaz boyutlarına sorunsuz uyum sağlar
- **Koyu/Açık Tema**: Rahat görüntüleme için temalar arası geçiş
- **Akıcı Animasyonlar**: İlgi çekici kullanıcı deneyimi için AOS (Animate on Scroll)
- **İnteraktif Öğeler**: Özel imleç efektleri ve hover animasyonları
- **Çoklu Dil Desteği**: Türkçe versiyon (İngilizce versiyon ayrı olarak mevcut)

### Bölümler
- **Ana Sayfa**: Animasyonlu metin ile dinamik tanıtım
- **Hakkımda**: Profesyonel geçmiş ve kişisel tanıtım
- **Yetenekler**: İlerleme çubukları ile teknik yetkinliklerin görsel sunumu
- **Deneyim & Eğitim**: Yolculuğu gösteren interaktif zaman çizelgesi
- **Projeler**: Filtreleme özelliği ile portfolyo galerisi
- **İletişim**: EmailJS ile desteklenen fonksiyonel iletişim formu

## 🛠️ Kullanılan Teknolojiler

### Frontend
- HTML5
- CSS3 (CSS Grid & Flexbox ile)
- Vanilla JavaScript

### Kütüphaneler & Araçlar
- **AOS**: Kaydırma animasyonları için Animate on Scroll kütüphanesi
- **Font Awesome**: İkon kütüphanesi
- **EmailJS**: E-posta servisi entegrasyonu
- **Google Fonts**: Tipografi (Poppins, Inter)
- **GitHub Actions**: CI/CD iş akışları

## 📁 Proje Yapısı

```
Portfolyo/
├── index.html          # Ana HTML dosyası
├── css/               
│   ├── style.css       # Ana stil dosyası
│   └── responsive.css  # Medya sorguları
├── js/
│   ├── main.js         # Temel JavaScript işlevleri
│   ├── theme.js        # Tema değiştirme mantığı
│   └── animations.js   # Animasyon kontrolleri
├── assets/
│   ├── images/         # Proje görselleri ve ikonlar
│   └── docs/           # Özgeçmiş ve belgeler
└── .github/
    └── workflows/      # GitHub Actions yapılandırmaları
```

## 🚀 Başlarken

### Gereksinimler
- Modern web tarayıcı (Chrome, Firefox, Safari, Edge)
- Temel web sunucusu (yerel geliştirme için)

### Kurulum

1. Depoyu klonlayın
```bash
git clone https://github.com/Kemalyavas/Portfolyo.git
```

2. Proje dizinine gidin
```bash
cd Portfolyo
```

3. Live Server (VS Code) veya herhangi bir yerel sunucu ile açın
```bash
# Python kullanarak
python -m http.server 8000

# Node.js kullanarak
npx serve
```

4. Tarayıcıyı açın ve `http://localhost:8000` adresine gidin

## ⚙️ Yapılandırma

### EmailJS Kurulumu
1. [EmailJS](https://www.emailjs.com/) sitesinde hesap oluşturun
2. E-posta servisinizi ekleyin
3. E-posta şablonu oluşturun
4. `js/main.js` dosyasında aşağıdakileri güncelleyin:
```javascript
emailjs.init("YOUR_USER_ID");
emailjs.send("YOUR_SERVICE_ID", "YOUR_TEMPLATE_ID", templateParams);
```

### Özelleştirme
- **Renkler**: `style.css` dosyasındaki `:root` bölümündeki CSS değişkenlerini düzenleyin
- **İçerik**: `index.html` dosyasındaki metni güncelleyin
- **Görseller**: `assets/images/` klasöründeki görselleri değiştirin
- **Projeler**: Portfolyo bölümüne yeni projeler ekleyin

## 📱 Responsive Kırılma Noktaları

- Mobil: < 768px
- Tablet: 768px - 1024px
- Masaüstü: > 1024px

## 🎨 Renk Şeması

### Açık Tema
- Birincil: #2563eb
- Arka plan: #ffffff
- Metin: #1f2937

### Koyu Tema
- Birincil: #3b82f6
- Arka plan: #0f172a
- Metin: #e5e7eb

## 🔧 Performans Optimizasyonu

- Görseller için lazy loading
- Küçültülmüş CSS ve JavaScript
- 60fps için optimize edilmiş animasyonlar
- Verimli DOM manipülasyonu
- Önbelleğe alınmış tema tercihleri

## 📈 SEO Özellikleri

- Meta etiket optimizasyonu
- Yapılandırılmış veri
- Semantik HTML
- Open Graph etiketleri
- Twitter Card desteği

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen Pull Request göndermekten çekinmeyin.

1. Projeyi fork'layın
2. Özellik dalınızı oluşturun (`git checkout -b feature/HarikaOzellik`)
3. Değişikliklerinizi commit'leyin (`git commit -m 'Harika özellik eklendi'`)
4. Dalınıza push'layın (`git push origin feature/HarikaOzellik`)
5. Pull Request açın

## 📄 Lisans

Bu proje açık kaynaklıdır ve [MIT Lisansı](LICENSE) altında kullanılabilir.

## 👤 Yazar

**Ali Kemal Yavaş**
- GitHub: [@Kemalyavas](https://github.com/Kemalyavas)
- LinkedIn: [Ali Kemal Yavaş](https://www.linkedin.com/in/alikemalyavas/)
- E-posta: kemalyavas@example.com

## 🙏 Teşekkürler

- Akıcı animasyonlar için AOS Kütüphanesi
- İkonlar için Font Awesome
- İletişim formu işlevselliği için EmailJS
- Hosting için GitHub Pages

---

⭐ Faydalı bulduysanız bu depoyu yıldızlayın!