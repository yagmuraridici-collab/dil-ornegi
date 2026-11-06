# Dil Örneği uygulamasını yayına alma

Bu klasör, telefona ve tablete ana ekrandan kurulabilen bir web uygulamasıdır (PWA).
Bir kez internete koyduktan sonra internetsiz de çalışır.

## 1. GitHub Pages'e yükle (ücretsiz, bir kez yapılır)

1. github.com adresinde ücretsiz bir hesap aç.
2. Sağ üstteki **+** → **New repository**. Adı: `dil-ornegi`. **Public** seçili kalsın → **Create repository**.
3. Açılan sayfada **uploading an existing file** bağlantısına tıkla.
4. Bu klasörün içindekileri (index.html, manifest.webmanifest, sw.js ve icons klasörü) sürükleyip bırak → **Commit changes**.
5. **Settings** → soldan **Pages** → *Source*: **Deploy from a branch**, *Branch*: **main** ve **/(root)** → **Save**.
6. Birkaç dakika sonra uygulaman şu adreste açılır:
   `https://KULLANICI-ADIN.github.io/dil-ornegi/`

Not: Depo herkese açıktır ama içinde yalnızca uygulamanın kodu var. Danışan verisi, döküm ve ses kaydı asla buraya gitmez.

## 2. Telefona / tablete kur

- **iPhone / iPad (Safari):** Adresi aç → **Paylaş** düğmesi → **Ana Ekrana Ekle**.
- **Android (Chrome):** Adresi aç → sağ üstteki **⋮** → **Uygulamayı yükle** ya da **Ana ekrana ekle**.

İlk kayıtta telefon mikrofon izni ister, **İzin ver** de.

## 3. Güncelleme yaparken

1. Yeni dosyaları aynı depoya tekrar yükle (eskilerin üzerine yazılır).
2. `sw.js` dosyasının en üstündeki `doa-v1` yazısını bir artır (`doa-v2`). Böylece telefonlar yeni sürümü alır.

## Veri ve gizlilik

- Döküm, danışan bilgileri ve son ses kaydı yalnızca o cihazda saklanır.
- Tarayıcı verisini silmek ya da uygulamayı ana ekrandan kaldırmak bunları da siler. Önemli kayıtları **Kaydı cihaza indir**, raporları **Raporu kopyala** ile ayrıca sakla.
- Cihazda ekran kilidi kullan; danışan kodu yerine gerçek isim yazma.
