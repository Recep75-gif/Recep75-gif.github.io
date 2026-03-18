# Mavzer Reklam Tabela & Dijital Baskı

Bu proje GitHub Pages için hazırlanmış statik web sitesidir.

## Dosyalar
- `index.html`
- `style.css`
- `script.js`
- `assets/`
- `CNAME`
- `.nojekyll`

## GitHub'a yükleme
1. GitHub'da yeni bir repository oluştur.
2. ZIP dosyasını çıkar.
3. Tüm dosyaları repository kök dizinine yükle.
4. `Settings > Pages` bölümüne gir.
5. Source olarak `Deploy from a branch` seç.
6. Branch olarak `main` ve `/root` seç.
7. Birkaç dakika içinde site yayına girer.

## Domain ayarı
Repository içinde `CNAME` dosyası hazırdır:

```
mavzerreklam.com.tr
```

Domain sağlayıcında aşağıdaki DNS ayarlarını yap:

### A kayıtları (root domain için)
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

### CNAME kaydı (www için)
- Host: `www`
- Value: `<github-kullanici-adin>.github.io`

Not: `<github-kullanici-adin>` kısmını GitHub kullanıcı adınla değiştir.
