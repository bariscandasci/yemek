# Yemekhane Aylık Menü

Aylık yemek listesini Excel dosyasından okuyup tarayıcıda gösteren tek sayfa. Veriler `localStorage` içinde kalır.

`index.html` dosyasını açın. Tailwind ve SheetJS bir CDN üzerinden gelir, bu yüzden ilk açılışta internet gerekir.

Vercel bu depoyu statik site olarak yayınlar. Kök dizin `index.html` dosyasıdır; ayrıca bir derleme adımı yoktur.

## Excel biçimi

İlk satır başlık olmalıdır.

| Tarih | Öğün | Çorba | Ana Yemek | Yardımcı Yemek | Salata | Tatlı |
| --- | --- | --- | --- | --- | --- | --- |
| 20.10.2026 | Öğle | Mercimek Çorbası | Izgara Tavuk | Pirinç Pilavı | Mevsim Salata | Sütlaç |
| 20.10.2026 | Akşam | Domates Çorbası | Tavuk Şiş | Bulgur Pilavı | Çoban Salata | Meyve |

`Öğün` sütunu isteğe bağlıdır. Tarih `GG.AA.YYYY`, `YYYY-AA-GG` veya Excel tarih hücresi olabilir. Sayfanın üstünde `Ekim 2026` yazıyorsa gün numarası da yeterlidir. Uygulamadaki **Şablon** düğmesi bu ayın örneğini indirir.
