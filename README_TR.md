# Yiğit Simülasyon Online – Güncel Paket

- `public/index.html`: Porsche 918 Spyder ve BMW 330i gömülü 3D modelleri, düzeltilmiş çevrim içi durum eşitlemesi ve çevrim içi yarış sistemi.
- `server.js`: WebSocket oda sunucusu, oyuncu durum senkronizasyonu, yarış daveti/onayı ve ilk bitiren bildirimi.

Render ayarları: Build Command boş; Start Command `npm start`. Node sürümü güncel LTS olmalıdır.

Yarış yalnızca aynı çevrim içi odadaki en az iki oyuncuyla çalışır. Her oyuncu daveti kabul etmelidir. Birinciye 500 sanal oyun parası eklenir; gerçek para değildir.
