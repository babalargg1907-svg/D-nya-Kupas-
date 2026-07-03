# Kupa48 GitHub Pages Kurulum

Bu paket GitHub Pages için hazırdır.

## Zorunlu dosyalar
- `index.html`
- `data/tournament.json`

## Admin güncelleme akışı
1. Siteyi aç.
2. Skorları, takım sahipliğini veya maç detaylarını gir.
3. `tournament.json İndir` butonuyla güncel JSON dosyasını indir.
4. GitHub repo içinde `data/tournament.json` dosyasını bu yeni dosyayla değiştir.
5. Commit et. Arkadaşların sayfayı yenileyince güncel veri görünür.

## Görsel klasörleri
Aşağıdaki dosya adlarıyla görsel koyarsan sistem otomatik kullanır:

- `assets/img/stadium-hero.jpg` — ana dashboard stadyum görseli
- `assets/img/trophy.png` — skorbord kupa görseli
- `assets/img/final-night.jpg` — final/şampiyonluk atmosferi
- `assets/img/group-stage.jpg` — grup aşaması görseli
- `assets/img/fans.jpg` — taraftar/tribün görseli
- `assets/img/pattern-gold.png` — altın desen/texture

Takım logoları için:
- `assets/teams/BRA.png`
- `assets/teams/ARG.png`
- `assets/teams/TUR.png`
- diğer takım kodlarıyla aynı format.

Kullanıcı avatarları için:
- `assets/users/ilker.jpg`
- `assets/users/dogan.jpg`
- `assets/users/giray.jpg`
- `assets/users/eren.jpg`

Görseller yoksa uygulama yine çalışır; emoji ve premium CSS fallback görünür.
