# HSU 4 — Demokratie und Gesellschaft

Bayern LehrplanPLUS, HSU 3/4, Lernbereich 1. Almanca ders içeriği ve yanında Türkçe açıklamalar.
Tek sayfalık, çevrimdışı çalışan bir web uygulaması (PWA).

## Dosyalar

| Dosya | Ne işe yarar |
|---|---|
| `index.html` | Sayfanın tamamı (içerik + tasarım) |
| `manifest.webmanifest` | Uygulama adı, ikon, renk bilgisi |
| `sw.js` | Çevrimdışı çalışmayı sağlayan service worker |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Ana ekran ikonları |

## GitHub Pages'te yayınlama

1. GitHub'da yeni bir repo aç, adı `hsu-demokratie` olsun. **Public** seç.
2. Bu klasördeki bütün dosyaları reponun köküne yükle (alt klasör açma).
3. Repo sayfasında **Settings → Pages**.
4. *Source* kısmında **Deploy from a branch** seç, branch `main`, klasör `/ (root)`, **Save**.
5. Bir iki dakika sonra adres hazır olur:
   `https://KULLANICIADIN.github.io/hsu-demokratie/`

## Telefonda uygulama gibi açmak

**Android (Chrome):** Adresi aç → sağ üstteki üç nokta → *Ana ekrana ekle* / *Uygulamayı yükle*.

**iPhone (Safari):** Adresi aç → paylaş simgesi → *Ana Ekrana Ekle*.

Ana ekrandan açınca adres çubuğu görünmez ve ilk açılıştan sonra internet olmadan da çalışır.

## İçeriği güncelleme

`index.html` dosyasını değiştir, GitHub'a yükle. Telefonlardaki kopyanın kendini yenilemesi için
`sw.js` içindeki `VERSION = "hsu-v1"` satırını `"hsu-v2"` yap.

## Kaynak

İçerik Bavyera resmî müfredatına dayanır:
<https://www.lehrplanplus.bayern.de/fachlehrplan/grundschule/4/hsu>
