# US Lightroom Notları

Uğur Sezer’in FigJam’deki 123 Lightroom notundan üretilmiş; tekrarları ayıklanmış, 14 ana bölüme ayrılmış ve Notion esintili bir statik bilgi tabanı.

## Yayın adresleri

**GitHub Pages:** https://uursezer.github.io/note27/

**Vercel:** https://us-lightroom-arkadas-dv-os1.vercel.app/

> Vercel adresinin dışarıdan açılması için proje ayarlarında Vercel Authentication kapatılmalıdır.

## Özellikler

- 12 adımlı Lightroom düzenleme rotası
- 14 tekrarsız ana bölüm
- Tam metin arama (`⌘/Ctrl + K`)
- Açık/koyu tema
- Okundu işaretleri ve ilerleme takibi
- Mobil ve masaüstü uyumlu arayüz

## Yerel kullanım

Depoyu klonladıktan sonra klasörün içinde bir statik sunucu başlatın:

```bash
python3 -m http.server 8080
```

Ardından `http://localhost:8080` adresini açın.

Site içeriği `payload/part-*.js` dosyalarında sıkıştırılmış halde tutulur.
