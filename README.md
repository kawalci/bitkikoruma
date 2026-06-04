# Ders Materyalleri Kütüphanesi

Bu repo; kullanıcı sistemi, backend veya veritabanı gerektirmeyen statik bir ders materyalleri sitesi taslağıdır. Site bir ana sayfadan ve HTML tabanlı alt sayfalardan oluşur.

## İçerik Mantığı

Her ders yalnızca iki ana başlık altında düzenlenir:

- **Çalışma Kağıdı**
- **Örnek Soru**

Ders özeti, konu anlatımı veya farklı içerik kategorileri bu mimaride kullanılmaz.

## Dosya Yapısı

```text
index.html
style.css
script.js
README.md

dersler/
  ders-sablonu.html

calisma-kagitlari/
  calisma-kagidi-sablonu.html

ornek-sorular/
  ornek-soru-sablonu.html

assets/
  images/
```

## Yeni Ders Ekleme

1. `dersler/ders-sablonu.html` dosyasını kopyalayın.
2. Dosyayı küçük harf, tire ve Türkçe karaktersiz adlandırın.
   - Örnek: `dersler/yeni-ders-adi.html`
3. Sayfa başlığını gerçek ders adıyla değiştirin.
4. Ders sayfasında sadece şu iki başlığı kullanın:
   - Çalışma Kağıdı
   - Örnek Soru
5. `index.html` içindeki dersler alanına yeni ders kartı veya bağlantısı ekleyin.

## Yeni Çalışma Kağıdı Ekleme

1. `calisma-kagitlari/calisma-kagidi-sablonu.html` dosyasını kopyalayın.
2. Dosyayı ders ve içerik adına göre adlandırın.
   - Örnek: `calisma-kagitlari/yeni-ders-adi-calisma-kagidi-1.html`
3. Başlık, ders, konu, amaç ve tarih alanlarını doldurun.
4. Soruları ve cevap alanlarını düzenleyin.
5. İlgili ders sayfasında **Çalışma Kağıdı** başlığı altına bağlantıyı ekleyin.

## Yeni Örnek Soru Ekleme

1. `ornek-sorular/ornek-soru-sablonu.html` dosyasını kopyalayın.
2. Dosyayı ders ve içerik adına göre adlandırın.
   - Örnek: `ornek-sorular/yeni-ders-adi-ornek-soru-1.html`
3. Başlık, ders, konu, soru türü ve zorluk alanlarını doldurun.
4. Soruları ve varsa cevap/açıklama bölümünü düzenleyin.
5. İlgili ders sayfasında **Örnek Soru** başlığı altına bağlantıyı ekleyin.

## Dosya Adı Standardı

- Küçük harf kullanın.
- Boşluk yerine tire kullanın.
- Türkçe karakter kullanmayın.
- Kısa ve anlaşılır adlar seçin.

Doğru örnekler:

```text
yeni-ders-adi.html
yeni-ders-adi-calisma-kagidi-1.html
yeni-ders-adi-ornek-soru-1.html
```

## Yayınlama

Bu proje statik HTML/CSS/JS dosyalarından oluştuğu için GitHub Pages, Netlify, Vercel veya herhangi bir statik hosting ortamında doğrudan yayınlanabilir.
