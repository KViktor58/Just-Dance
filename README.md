# Just Dance – statikus egyesületi weboldal

**EN:** Multi-page static website for a dance/sports club. Built with HTML/CSS (Flexbox + Grid), responsive sections, cards, and image galleries. No framework/build step.

Többoldalas, statikus bemutatkozó weboldal egy tánc/sportegyesület számára.
Egységes arculat, hero szekció, kártyás elrendezések, galériák és több aloldal.

## Oldalak
- **Főoldal** (`index.html`)
- **Rólunk** (`html/rolunk.html`)
- **Időpontok** (`html/idopontok.html`)
- **Közelgő események** (`html/esemenyek.html`)
- **Eredményeink** (`html/eredmenyek.html`)
- **Támogatás** (`html/tamogatas.html`)
- **Elérhetőségek** (`html/elerhetosegek.html`)

## Technológiák
- HTML5
- CSS3 (Flexbox + Grid)
- Nincs framework / build lépés, tisztán statikus oldal

## Főbb UI elemek / megoldások
- Header több “band”-del + navigáció
- Hero kép overlay gradienttel
- Reszponzív grid layoutok:
  - Időpontok: kártyák (2 oszlop → mobilon 1)
  - Események: kártyák (3 → 2 → 1 oszlop)
  - Eredmények: kártyák + galéria grid
- Egységes footer social linkekkel

## Projektstruktúra
```Just Dance
/
├─ index.html
├─ css/
│  └─ style.css
├─ html/
│  ├─ rolunk.html
│  ├─ idopontok.html
│  ├─ esemenyek.html
│  ├─ eredmenyek.html
│  ├─ tamogatas.html
│  └─ elerhetosegek.html
└─ img/
   ├─ logo.jpg
   ├─ heroImg.png
   ├─ adomany.png
   ├─ insta_logo.png
   ├─ facebook_logo.png
   ├─ youtube_logo.png
   ├─ tmplmg1.png
   ├─ esemenyek/
   │  ├─ img1.png
   │  ├─ img2.png
   │  └─ img3.png
   ├─ 2025_jun_09/
   │  ├─ img1.jpg
   │  ├─ img2.jpg
   │  ├─ img3.jpg
   │  ├─ img4.jpg
   │  └─ img5.jpg
   └─ 2025_maj_11/
      ├─ img1.jpg
      ├─ img1.png
      ├─ img2.jpg
      ├─ img3.jpg
      ├─ img4.jpg
      └─ img5.jpg
