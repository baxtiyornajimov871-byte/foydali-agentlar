# FOYDALI AGENTLAR

Windows 11 uchun o‘zbek tilidagi AI agentlar markazi.

Maqsad — foydalanuvchiga kerakli ochiq manbali agentlarni bir joydan topish, tekshirish, o‘rnatish, sozlash, ishga tushirish va yangilash imkonini beruvchi yagona desktop dastur yaratish.

## Asosiy tamoyillar

- Dastur interfeysi, menyulari va yo‘riqnomalari o‘zbek tilida bo‘ladi.
- Agentlar katalogi va agentlarning o‘zi alohida saqlanadi.
- Tashqi loyihalarning kodini ruxsatsiz ko‘chirib olmaymiz; rasmiy GitHub manbasidan foydalanamiz.
- Har bir agent Windows mosligi, litsenziyasi, xavfsizligi, resurs talabi va yangilanish faolligi bo‘yicha tekshiriladi.
- O‘rnatishdan oldin foydalanuvchiga nimalar yuklanishi, qancha joy va qanday ruxsatlar kerakligi ko‘rsatiladi.
- API kalitlari va maxfiy ma’lumotlar repozitoriyga kiritilmaydi.
- Xavfli buyruqlar va tizimga ta’sir qiluvchi amallar foydalanuvchi tasdig‘isiz bajarilmaydi.

## Hozirgi bosqich

1. GitHub’dagi rasmiy agent manbalarini katalogga kiritish.
2. Litsenziya, Windows mosligi, resurs talabi va xavfsizlikni tekshirish.
3. Har bir agent uchun alohida o‘rnatish yo‘riqnomasi va tekshiruv ro‘yxatini tayyorlash.
4. O‘rnatishdan oldin foydalanuvchiga yuklama va ruxsatlarni ko‘rsatadigan mexanizm yaratish.
5. Windows desktop interfeysini yaratish va agentlarni bittadan sinash.

## Katalogning hozirgi holati

- 24 ta loyiha katalogga kiritilgan.
- Ularning barchasi o‘rnatilmagan; Windows mosligi va resurs sarfi alohida sinovdan o‘tadi.
- `project_type` maydoni haqiqiy agentni, frameworkni, model muhitini va yordamchi vositani farqlaydi.

## Birinchi qo‘shilgan asosiy agent

- **Hermes Agent** — umumiy shaxsiy yordamchi. Rasmiy repozitoriyada native Windows o‘rnatish yo‘li ko‘rsatilgan. Hozircha katalogga kiritilgan, lekin noutbukga o‘rnatilmagan va amaliy sinovdan o‘tmagan.
- Rasmiy manba: https://github.com/NousResearch/hermes-agent
- O‘rnatish faqat alohida tekshiruv va foydalanuvchi tasdig‘idan keyin amalga oshiriladi.

## Katalog

Hozirgi katalogda **24 ta loyiha** bor: agentlar, agent frameworklari, mahalliy model muhiti va yordamchi media/hujjat vositalari. Ro‘yxat: [catalog/agents.json](catalog/agents.json)

Yangi qo‘shilgan loyihalar bo‘yicha qisqa saralash: [docs/KATALOG_SARALASH.md](docs/KATALOG_SARALASH.md)

Tanlash va xavfsizlik qoidalari: [docs/AGENT_TANLASH_QOIDALARI.md](docs/AGENT_TANLASH_QOIDALARI.md)

## Muhim

Katalogdagi loyiha — o‘rnatishga tayyor yoki to‘liq sinovdan o‘tgan degani emas. Har bir agentning holati alohida belgilanadi. Dastur avval tekshiradi, keyin o‘rnatishga ruxsat beradi.
