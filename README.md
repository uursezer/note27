# US Lightroom Notları

Uğur Sezer’in FigJam’deki 123 Lightroom notundan üretilmiş, tekrarları ayıklanmış ve Notion esintili kişisel bilgi tabanı.

## Canlı site

GitHub Pages dağıtımı tamamlandığında proje adresi:

**https://uursezer.github.io/note27/**

## İçerik

- 123 ham nottan 14 düzenli bölüm
- 12 adımlı Lightroom düzenleme rotası
- Tam metin arama (`⌘/Ctrl + K`)
- Açık/koyu tema
- Okundu işaretleri ve ilerleme takibi
- Mobil uyumlu, bağımlılıksız statik site

## Yayınlama

`.github/workflows/pages.yml`, `main` dalına yapılan her push sonrasında siteyi GitHub Pages’e dağıtır. Site kaynağı, GitHub dosya boyutu ve aktarım güvenilirliği için `site/part-*.b64` parçalarında sıkıştırılmış olarak tutulur; workflow bu parçaları birleştirip doğrular ve `index.html` üretir.

> Repository özel olduğu için GitHub Pages kullanılabilirliği GitHub hesap planına bağlıdır. Pages yayın kaynağı repository ayarlarında **GitHub Actions** olarak etkinleştirilmelidir.
