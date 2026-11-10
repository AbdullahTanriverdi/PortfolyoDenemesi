# Kişisel bağlantı ve portfolyo sitesi

Sadece HTML ve CSS ile hazırlanmış, GitHub Pages üzerinde yayınlanabilen kişisel site.

## Düzenlenecek alanlar

1. `index.html` içindeki `Ad Soyad`, açıklama, e-posta ve sosyal medya bağlantılarını değiştirin.
2. `assets/style.css` içindeki `:root` renk değişkenleriyle görünümü kişiselleştirin.
3. Portfolyoya yeni çalışma eklemek için `projects/yeni-proje/index.html` gibi bir klasör ve sayfa oluşturun.
4. Ana sayfadaki `projects-grid` içine yeni bir `project-card` bağlantısı ekleyin. İsterseniz `coming-soon` kartını değiştirin.
5. Dış fontlar Google Fonts'tan yüklenir. İnternet yoksa Arial ile çalışır.

## Yerelde açma

`index.html` dosyasına çift tıklayın. Sunucu veya npm gerekli değildir.

## GitHub Pages

Repo'yu GitHub'a gönderin. Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.

Proje sayfaları göreli yollarla bağlandığı için proje sitesi (`kullanici.github.io/repo-adi/`) olarak da çalışır.

## Yapı

```
index.html
assets/style.css
projects/ornek-proje/index.html
projects/ornek-proje/style.css
README.md
```

Not: Sosyal linkler başlangıçta platform ana sayfalarına gider; kendi profil adreslerinizle değiştirmelisiniz.
