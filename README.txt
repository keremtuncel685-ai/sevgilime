CEREN — CHAPTER 22 / VS CODE KURULUM
====================================

1. Bu klasörü bilgisayarında aç ve VS Code'da File > Open Folder ile seç.
2. index.html dosyasına sağ tıkla: "Open with Live Server".
   Live Server yoksa VS Code > Extensions > "Live Server" yükle.
   Alternatif: index.html dosyasına çift tıklayıp tarayıcıda aç.
3. Kendi fotoğraflarını assets klasörüne aşağıdaki isimlerle ekle:
   biz.jpg      = ortadaki TAM EKRAN romantik arka plan
   foto1.jpg    = galeri fotoğrafı #1
   foto2.jpg    = galeri fotoğrafı #2
   foto3.jpg    = galeri fotoğrafı #3
   foto4.jpg    = galeri fotoğrafı #4
   foto5.jpg    = galeri fotoğrafı #5
   foto6.jpg    = galeri fotoğrafı #6
   foto7.jpg    = galeri fotoğrafı #7
   foto8.jpg    = galeri fotoğrafı #8
   sarkimiz.mp3 = müzik butonuna basılınca çalacak şarkı

   Fotoğrafları jpg olarak kaydet. Başka uzantı kullanırsan
   script.js içindeki SITE.photos adreslerini güncelle.

4. script.js dosyasının EN ÜSTÜNDEKI SITE bölümünden:
   - 22 sevgi nedeni,
   - fotoğraf başlıkları,
   - aşk mektubu,
   - fotoğraf / şarkı dosya adlarını değiştirebilirsin.

5. Ana renkleri değiştirmek için style.css dosyasının başındaki
   :root bölümünü düzenle.

6. Telefonda test etmek için bilgisayar ve telefon AYNI Wi-Fi'da olsun.
   VS Code Live Server bilgisayar IP'niz üzerinden açılabilir.
   Örn. http://192.168.1.100:5500 (IP bilgisayarına göre değişir.)
   Kalıcı internet bağlantısı/linki için Netlify, GitHub Pages veya
   Vercel gibi statik hosting kullanılabilir.

UYARI:
- Telif hakkına uygun / paylaşmaya izinli müzik kullan.
- Tarayıcılar sesi kullanıcı etkileşimi olmadan otomatik başlatmaz;
  bu yüzden "Müziği aç" düğmesi bulunur.
- Gerçek fotoğrafları ve müziği klasöre eklemeden de site açılır.
  Eksik fotoğraflar şık numaralı renk alanları olarak gösterilir.
- Site tamamen statiktir; sunucu veya hesap gerektirmez.

DOSYALAR
index.html   sayfa yapısı
style.css    modern tasarım, animasyon ve mobil uyum
script.js    etkileşimler ve kişisel mesajlar
assets/      fotoğraflar ve müzik

YENİ: HER DOKUNUŞTA BEYAZ KALP 🤍
=================================
- iPhone Safari'de sayfanın herhangi bir yerine dokununca yerinden
  yukarı süzülerek kaybolan iOS tarzı beyaz kalp çıkar.
- Bilgisayarda sol tıklandığında da aynı efekt görünür.
- Kaydırmayı, düğmelere dokunmayı, müziği ve fotoğrafları engellemez.
- iPhone beyaz kalbi kendi Apple Color Emoji yazı tipiyle gösterir.
  Windows ve Android'de cihazın yerel emoji çizimi kullanılır;
  Apple emoji görünümünü Windows'ta bire bir garantilemek mümkün değildir.
- Animasyon ve kalp boyutunu değiştirmek için style.css dosyasında
  ".touch-heart" ve "@keyframes touch-heart-float" bölümlerini düzenle.
- Her tıklandığında kalp çıkma kodu script.js içinde "setupTapHearts".
- Daha az hareket seçeneği etkin kullanıcılar için sade animasyon bulunur.
