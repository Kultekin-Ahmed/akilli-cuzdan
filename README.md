# Akıllı Cüzdan

Telefon ve bilgisayarda kullanılabilen, GitHub Pages ile yayınlanabilen kişisel bütçe takip PWA'sı.

## Yayınlama
1. Bu klasördeki dosyaların tamamını GitHub deposunun kök dizinine yükleyin.
2. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
3. Yayınlanan HTTPS adresini telefon tarayıcısında açıp ana ekrana ekleyin.

## Özellikler
- Gelir, gider ve kumbara simgeli birikim kayıtları
- Kategori bütçeleri ve birikim hedefleri
- Borç/alacak ve tekrarlayan fatura listesi
- Aylık gider grafiği, JSON yedekleme, açık/koyu tema, isteğe bağlı PIN
- Çevrimdışı kullanım için servis çalışanı

## Gizlilik ve sınırlamalar
Kayıtlar yalnızca tarayıcının `localStorage` alanında tutulur; sunucuya gönderilmez. Tarayıcı verileri silinirse kayıtlar kaybolabilir; JSON yedeği alın. PIN, temel bir uygulama kilididir; profesyonel şifreleme değildir. Tekrarlayan faturalar hatırlatma/otomatik ödeme yapmaz.
