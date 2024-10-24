# CyclOPedia

CyclOPedia, React kullanılarak geliştirilmiş çok dilli bir web uygulamasıdır. Bu uygulama, sınıf ve fonksiyonel bileşenlerin kullanımını göstermekte, dil değiştirme özelliği sunmakta ve React'in yaşam döngüsü metodlarını ve hooks'larını örneklemektedir.

## İçindekiler

- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Proje Yapısı](#proje-yapısı)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Sık Sorulan Sorular](#sık-sorulan-sorular)
- [Lisans](#lisans)
- [İletişim](#iletişim)

## Özellikler

- 🌐 Çok dilli arayüz (İngilizce ve Türkçe)
- 🧩 Sınıf ve fonksiyonel bileşen örnekleri
- 👨‍🏫 Eğitmen bilgilerini gösterme/gizleme
- 👥 Öğrenci listesi yönetimi (ekleme, tümünü silme)
- 📝 Geri bildirim formu
- 💾 Yerel depolama kullanımı (localStorage)
- 🔄 React yaşam döngüsü metodları ve hooks örnekleri

## Kurulum

1. Repoyu klonlayın:
   ```
   git clone https://github.com/kullaniciadi/cyclopedia.git
   ```

2. Proje dizinine gidin:
   ```
   cd cyclopedia
   ```

3. Bağımlılıkları yükleyin:
   ```
   npm install
   ```

4. Uygulamayı başlatın:
   ```
   npm start
   ```

5. Tarayıcınızda `http://localhost:3000` adresine gidin.

## Kullanım

1. Uygulamayı başlattıktan sonra, sağ üst köşedeki dil seçeneklerinden istediğiniz dili seçebilirsiniz.
2. "Sınıf Bileşeni" ve "Fonksiyonel Bileşen" bölümlerini inceleyerek farklı React yaklaşımlarını görebilirsiniz.
3. Eğitmen bilgilerini göstermek veya gizlemek için "Göster/Gizle" düğmesini kullanın.
4. Öğrenci eklemek için "Öğrenci Ekle" düğmesine tıklayın.
5. Tüm öğrencileri silmek için "Tüm Öğrencileri Kaldır" düğmesini kullanın.
6. Geri bildirim formunu doldurmak için ad ve geri bildirim alanlarını kullanın.

## Proje Yapısı

```
cyclopedia/
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── components/
│   │   ├── CyclOPediaClassPage.jsx
│   │   ├── CyclOPediaFuncPage.jsx
│   │   ├── Header.jsx
│   │   ├── Instructor.jsx
│   │   └── InstructorFunc.jsx
│   │
│   ├── Utility/
│   │   └── api.jsx
│   │
│   ├── images/
│   │   └── react.png
│   │
│   ├── index.js
│   ├── index.css
│   └── translations.js
│
├── package.json
└── README.md
```

## Kullanılan Teknolojiler

- [React](https://reactjs.org/) - Kullanıcı arayüzü oluşturmak için JavaScript kütüphanesi
- [Bootstrap](https://getbootstrap.com/) - Responsive tasarım için CSS framework'ü
- [Axios](https://axios-http.com/) - HTTP istekleri için Promise tabanlı kütüphane
- [React Hooks](https://reactjs.org/docs/hooks-intro.html) - Fonksiyonel bileşenlerde state ve yaşam döngüsü özellikleri

## Katkıda Bulunma

1. Bu repoyu fork edin
2. Yeni bir özellik dalı oluşturun (`git checkout -b yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik: Açıklama'`)
4. Dalınıza push yapın (`git push origin yeni-ozellik`)
5. Bir Pull Request oluşturun

Lütfen katkıda bulunmadan önce [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını okuyun.

## Sık Sorulan Sorular

**S: Uygulamayı nasıl başlatabilirim?**
C: Terminalde proje dizinine gidin ve `npm start` komutunu çalıştırın.

**S: Yeni bir dil nasıl ekleyebilirim?**
C: `src/translations.js` dosyasına yeni bir dil objesi ekleyin ve `Header.jsx` bileşeninde dil seçeneklerini güncelleyin.

## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## İletişim

Proje Sahibi: [Adınız](https://github.com/kullaniciadi)

Proje Linki: [https://github.com/kullaniciadi/cyclopedia](https://github.com/kullaniciadi/cyclopedia)

---

⭐️ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!
