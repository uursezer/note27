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

Repository public durumdadır ve GitHub Pages için hazırlanmıştır. Dağıtım `.github/workflows/pages.yml` iş akışıyla yapılır.

Yayın adresi: **https://uursezer.github.io/note27/**

Site içeriği `payload/part-*.js` dosyalarında sıkıştırılmış halde tutulur. `index.html` tarayıcıda bu parçaları birleştirip yerel olarak açar.

> GitHub Pages dağıtımı için son tetikleme: 18 Ağustos 2026, 13:10 UTC.
