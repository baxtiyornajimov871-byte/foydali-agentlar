# Agentlarni tanlash va xavfsizlik qoidalari

## 1. Tanlash mezonlari

Har bir nomzod quyidagi bandlar bo‘yicha tekshiriladi:

1. Rasmiy GitHub manzili va loyiha egasi.
2. Loyiha faolmi, oxirgi relizlari va muammolariga javob beriladimi.
3. Litsenziya turi va tijoriy foydalanish cheklovlari.
4. Windows 11 bilan mosligi va rasmiy o‘rnatish yo‘riqnomasi.
5. Python, Node.js, Docker, WSL yoki boshqa bog‘liqliklar.
6. Disk, RAM, CPU va GPU talablari.
7. Internet, API kaliti va pullik xizmatga ehtiyoj.
8. Fayl, terminal, brauzer va tarmoq ruxsatlari.
9. Yangilash, o‘chirish va ma’lumotlarni tozalash imkoniyati.
10. Boshqa agentlar bilan integratsiya imkoniyati.

## 2. Holat belgilari

- `nomzod` — dastlabki qidiruvda topilgan.
- `manba tekshiruvi kerak` — repozitoriy yoki rasmiy hujjatlar qayta tekshiriladi.
- `tekshiruvda` — litsenziya, Windows mosligi va talablar o‘rganilmoqda.
- `sinovga tayyor` — xavfsizlik va o‘rnatish rejasi tayyor.
- `sinovdan o‘tgan` — aynan shu Windows muhitida amaliy tekshirildi.
- `o‘rnatilgan` — foydalanuvchi qurilmasiga muvaffaqiyatli o‘rnatildi.
- `rad etilgan` — xavfsizlik, litsenziya yoki moslik sababli katalogdan chiqarildi.

## 3. Xavfsizlik talablari

- Tashqi repozitoriy kodini ko‘r-ko‘rona ishga tushirmaslik.
- O‘rnatish skriptlarini avval o‘qish va tekshirish.
- Agentlarni imkon qadar alohida virtual muhit yoki konteynerda ishlatish.
- Administrator huquqini faqat zarur bo‘lganda so‘rash.
- Agentga faqat vazifasi uchun zarur bo‘lgan papka va ruxsatlarni berish.
- Terminal buyruqlari, fayl o‘chirish, tashqi xabar yuborish, xarid va nashr qilish kabi amallardan oldin foydalanuvchi tasdig‘ini olish.
- API kalitlari, parollar va tokenlarni GitHub’ga hech qachon joylamaslik.
- Ovoz klonlashda ovoz egasining aniq roziligini talab qilish.
- Har bir agentni yangilashdan oldin versiya, o‘zgarishlar va xavfsizlik xatarlarini ko‘rsatish.

## 4. Noutbuk resurslarini hisobga olish

Dastlabki maqsadli qurilma: Windows 11, Ryzen 7 7730U, 16 GB RAM va integratsiyalashgan Radeon grafikasi.

Shu sababli:
- Katta modellarni avtomatik ravishda mahalliy yuklab olmaymiz.
- GPU talab qiladigan ovoz/video modellarini alohida ogohlantiramiz.
- Bulut/API orqali ishlaydigan va mahalliy ishlaydigan agentlarni ajratamiz.
- Bir vaqtning o‘zida ko‘p og‘ir agentni ishga tushirmaymiz.
- Har bir agent uchun taxminiy disk va xotira talabi aniqlanmaguncha o‘rnatishni taklif qilmaymiz.

## 5. Tashqi loyihalarni ko‘chirish siyosati

FOYDALI AGENTLAR repozitoriyasiga boshqa loyihalarning butun manba kodini nusxalash rejalashtirilmaydi. Katalogda rasmiy havola, tavsif, litsenziya va tekshiruv holati saqlanadi. Agent kerak bo‘lganda rasmiy manbadan, litsenziya shartlariga muvofiq o‘rnatiladi.

Agar kelajakda kodning bir qismi vendoring qilinsa, uning litsenziyasi, mualliflik bildirishnomalari va manbasi alohida saqlanishi shart.
