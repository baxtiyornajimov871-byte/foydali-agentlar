# Hermes Agent — dastlabki tekshiruv

## Katalogdagi holati

- Toifa: shaxsiy yordamchi
- Ustuvorlik: hozir
- Litsenziya: MIT (GitHub repo metama’lumotida)
- Dasturlash tili: Python
- Windows: rasmiy README native Windows qo‘llab-quvvatlanishini bildiradi
- Holat: katalogga kiritilgan; hali o‘rnatilmagan va mahalliy sinovdan o‘tmagan

## Rasmiy manbalar

- Repozitoriya: https://github.com/NousResearch/hermes-agent
- Rasmiy hujjatlar: https://hermes-agent.nousresearch.com/docs/
- O‘rnatish hujjati: https://hermes-agent.nousresearch.com/docs/getting-started/installation

## Windows talablari va o‘rnatish

Rasmiy README'da PowerShell orqali quyidagi o‘rnatish usuli ko‘rsatilgan:

```powershell
iex (irm https://hermes-agent.nousresearch.com/install.ps1)
```

**Bu buyruqni hozircha avtomatik bajarmaymiz.** U internetdan skript olib, ishga tushiradi va bir nechta bog‘liqliklarni o‘rnatishi mumkin. Avval skript mazmuni, yuklanadigan komponentlar, disk hajmi, ruxsatlar va yangilanish mexanizmi tekshiriladi.

Rasmiy README o‘rnatuvchi Python 3.14, Node.js, npm, pnpm, ripgrep, FFmpeg va Python bog‘liqliklarini boshqarishini aytadi. Mavjud Python 3.13 muhitini almashtirish yoki buzishiga yo‘l qo‘ymaslik uchun o‘rnatish alohida muhitda bajarilishi kerak.

## Xavfsizlik tekshiruvi

Hermes terminal, brauzer va tashqi xizmatlar bilan ishlashi mumkin. Shu sababli:

1. O‘rnatishdan oldin PowerShell skripti ko‘rib chiqiladi.
2. API kalitlari faqat foydalanuvchi kompyuterida saqlanadi; GitHub'ga yuborilmaydi.
3. Fayl o‘zgartirish, terminal buyrug‘i, xabar yuborish va tashqi amallar tasdiq talab qiladi.
4. Dastlab test papkasi va maxsus sinov hisobi bilan tekshiriladi.
5. O‘rnatish va olib tashlash yo‘li hujjatlashtiriladi.

## Noutbukda sinovdan o‘tkazish mezonlari

- Windows 11'da o‘rnatish muvaffaqiyatli yakunlanishi.
- Ishga tushirish, sozlash va to‘xtatish ishlashi.
- RAM, protsessor, disk va tarmoq sarfi o‘lchanishi.
- Mahalliy fayllarga ruxsatlar tekshirilishi.
- API kalitlari va maxfiy ma’lumotlar log yoki repozitoriyga chiqmasligi.
- O‘chirishdan keyin keraksiz xizmat va jarayonlar qolmasligi.

## Qaror

Hozircha Hermes Agent — yuqori ustuvor nomzod. Windows qo‘llab-quvvatlashi rasmiy manbada ko‘rsatilgan, ammo HP Pavilion 15 (Ryzen 7 7730U, 16 GB RAM) qurilmasida amaliy sinov tugamaguncha uni **sinovdan o‘tgan** deb belgilamaymiz.
