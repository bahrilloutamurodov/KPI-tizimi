# Maktab maslahatçilari KPI tizimi

Maktab maslahatçilarining faoliyatini nazorat qiliş, ularga metodik yordam körsatiş va rağbatlantiriş uçun KPI baholaş tizimi (8 mezon — har oy 100 ball, 12 oy — yillik reyting).

**Namuna (demo) versiya:** https://bahrilloutamurodov.github.io/KPI-tizimi/

Demo versiyadagi barça ma'lumotlar soxta. Ular faqat foydalanuvçining öz brauzerida saqlanadi va boşqalarga körinmaydi. "Qaytadan boşlaş" havolasi namuna ma'lumotlarni tiklaydi.

## Imkoniyatlar

- **Kiriş:** administrator, viloyat va tuman (şahar) mutaxassislari, maslahatçilar va kuzatuvçilar uçun alohida kiriş; mutaxassislar uçun kiriş kodi.
- **Ierarxiya:** Respublika viloyat mutaxassislarini, viloyat mutaxassisi tuman mutaxassislarini biriktiradi, tuman mutaxassisi maslahatçilarni qöşadi. 14 hudud, 208 ta tuman va şahar.
- **Baholaş:** ballni faqat tuman (şahar) mutaxassisi kiritadi; mezonlar böyiça izoh, maslahatçining 5 kun içida e'tiroz bildirişi.
- **Maslahatçi sahifasi:** rasm, bajarilgan işlar (dalil havolasi bilan), yutuq va sertifikatlar, natija körsatkiçlari.
- **Monitoring:** Respublika har oy qöşimça monitoring topşiriqlarini beradi.
- **Tahlil:** Özbekiston xaritasi, erkak/ayol nisbati, maslahatçilar darajalari, xavf guruhi, baholaş adolatini tekşiriş, nominatsiyalar, Word/CSV hisobotlar, özgarişlar tarixi.

## Fayllar

- `index.html` — joriy versiya (yagona HTML fayl).
- `eski/index_v1.html` — avvalgi versiya.

Haqiqiy foydalaniş uçun umumiy ma'lumotlar bazasi claude.ai artefakti orqali işlaydi. Rasmiy davlat tizimi sifatida joriy etişda ma'lumotlarni Özbekistondagi serverga köçiriş va OneID orqali kiriş talab etiladi.
