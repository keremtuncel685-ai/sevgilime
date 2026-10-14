CEREN — CHAPTER 22 + 99 DILDE SENI SEVIYORUM
=============================================

VS Code ile:
1) Bu klasoru ac.
2) index.html dosyasini Live Server ile baslat.
3) Sayfayi asagi kaydir. Mumlari ufle bolumunden sonra siyah 99 dil bolumu var.
4) Kirmizi daktilo yazilari otomatik baslar; 99 dilden sonra yazilar
   buyuk bir kalp bicimine donusur; ortada buyuk beyaz C gorunur.
5) 'Kalbi goster' tusuna basarak animasyonu hizlica bitirebilir,
   'Yeniden izle' ile bastan baslatabilirsin.

DOSYALAR
--------
index.html      -> mevcut sitedeki yeni 'love99' bolumunu barindirir
style.css       -> onceki sitenin tasarimi
script.js       -> onceki sitenin islevleri / beyaz dokunma kalpleri
love99.css      -> sadece yeni siyah bolumun tasarimi
love99.js       -> 99 dil, yazma animasyonu, kalbe donusme mantigi
assets/         -> kendi fotograflarin ve muzigin (aynen korunur)

OZELLESTIRME
------------
Daktilo hizi: love99.js icindeki await wait(27)
Iki dil arasindaki sure: love99.js icindeki await wait(205)
Kirmizi renk: love99.css dosyasinda --love-red: #ff3159
C yerine baska harf: love99.js dosyasinda initialC.textContent = 'C'

TELEFON / iOS SAFARI
-------------------
IPhone Safari'de en saglikli deneyim icin siteyi statik hosting'e
(Netlify, Cloudflare Pages vb.) yukleyip HTTPS linkiyle ac.
Animasyonun ilk baslamasi icin siyah bolume kaydirman gerekir.
Tarayicinin 'hareketi azalt' ayari aciksa animasyon finale gecerek
hassasiyet tercihini korur.

Not: 99 farkli dil veya dil cesidinden yaygin sevgi ifadeleri
kullanilmistir. Bazi dillerde hitap ve konusmacinin cinsiyetine
gore ifadelerin baska bicimleri de vardir.

YENI SURUM — KALP ARTIK YAZILARDAN OLUSUYOR
- Kirmizi SVG kalp cizgisi kaldirildi.
- 99 sevgi sozu, 4 katmanli kalp cevresine diziliyor.
- Kalp boyutu: love99.css -> .love99-heart -> width
- Beyaz C boyutu: love99.css -> .love99-letter -> font-size
- Kalp yazilarinin boyutu: love99.css -> .love99-word -> font-size
- Yazi katmanlari ve yogunlugu: love99.js -> ringScales ve counts
