# US Lightroom Notları

Uğur Sezer’in FigJam’deki 123 Lightroom notundan üretilmiş; tekrarları ayıklanmış, 14 ana bölüme ayrılmış ve Notion esintili bir statik bilgi tabanı.

## Özellikler

- 12 adımlı Lightroom düzenleme rotası
- 14 tekrarsız ana bölüm
- Tam metin arama (`⌘/Ctrl + K`)
- Açık/koyu tema
- Okundu işaretleri ve ilerleme takibi
- Mobil ve masaüstü uyumlu arayüz
- Vercel veya başka bir çalışma zamanı hizmetine bağımlılık yok

## Yerel kullanım

Depoyu klonladıktan sonra klasörün içinde bir statik sunucu başlatın:

```bash
python3 -m http.server 8080
```

Ardından `http://localhost:8080` adresini açın.

## GitHub Pages

Depo GitHub Pages için hazırlanmıştır. Repository ayarlarında **Settings → Pages → Source: GitHub Actions** seçildiğinde, `main` dalına gelen her değişiklik otomatik olarak yayınlanır.

Yayın adresi: **https://uursezer.github.io/note27/**

Site içeriği, GitHub aktarım sınırlarına uygun olması için `payload/part-*.js` dosyalarında sıkıştırılmış halde tutulur. `index.html` tarayıcıda bu parçaları birleştirip yerel olarak açar.
