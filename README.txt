SPEAKLOOP PWA KURULUM

Bu klasor HTTPS uzerinde yayinlanmalidir. GitHub Pages, Netlify, Cloudflare Pages vb. statik hosting yeterlidir.

Dosyalarin tamamini sitenin kok dizinine yukleyin:
- index.html
- manifest.webmanifest
- sw.js
- icons/

iPhone kurulumu:
1. HTTPS adresini Safari'de acin.
2. Paylas butonuna dokunun.
3. Ana Ekrana Ekle secin.
4. SpeakLoop artik uygulama gibi acilir.

Guncelleme:
Yeni index.html veya diger dosyalari ayni web adresine yukleyin. sw.js icindeki VERSION degerini yeni surumde degistirin. Uygulama yeni surumu algiladiginda "Guncelle" cubugu gorunur.

Not: file:// ile acilan eski SpeakLoop localStorage verisi, HTTPS alan adindaki PWA'ya iOS tarafindan otomatik aktarilmaz.
