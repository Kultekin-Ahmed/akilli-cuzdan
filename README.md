# Akıllı Cüzdan

Gelir, gider, birikim ve kişisel bütçe takibi için çevrimdışı çalışabilen bir PWA.

## Özellikler
- Gelir, gider ve birikim işlemleri
- Hazır ve kullanıcı tarafından eklenebilen kategoriler
- Kalan para özeti, kategori bütçeleri ve birikim hedefleri
- Borç/alacak ve tekrarlayan fatura listeleri
- Aylık gider grafiği
- Açık/koyu tema
- Cihaz üzerinde hesap ve oturum
- JSON yedek dışa aktarma
- PWA olarak ana ekrana yükleme ve temel çevrimdışı önbellek

## Yayınlama
Dosyaları GitHub deposunun kök dizinine yükleyin. GitHub Pages ayarlarında `main` dalı ve `/(root)` seçin. Site HTTPS üzerinden açıldığında desteklenen tarayıcılarda ana ekrana yüklenebilir.

## Veri ve gizlilik
Hesaplar ve finans kayıtları tarayıcının yerel `localStorage` alanında saklanır; bir sunucuya gönderilmez ve cihazlar arasında eşitlenmez. Aynı cihaz/tarayıcıyı kullanan kişiler oturuma erişebilir. Tarayıcı verileri temizlenirse kayıtlar kaybolabilir; JSON yedeği alın. Bu uygulama profesyonel şifreli kasa veya sunucu tabanlı kimlik doğrulama hizmeti değildir.

## Görseller
- `icon.svg`: uygulama içindeki birikim alanları için yuvarlak kumbara çizimi.
- `wallet.svg`, `icon-192.png`, `icon-512.png`: uygulama ve ana ekran cüzdan simgesi.
