# Agentlar katalogi — saralash va ustuvorlik

2026-11-27 holatiga katalogda 30 ta loyiha bor. Bu son mustaqil agentlar soni emas: ro‘yxatda agentlar bilan birga framework, model ishga tushirish muhiti va media/hujjat vositalari ham bor.

## Hozirgi ehtiyojlar uchun birinchi navbat

| Loyiha | Turi | Nima uchun kerak |
|---|---|---|
| Hermes Agent | Umumiy agent | Kundalik vazifalar, ko‘nikmalar va turli vositalarni boshqarish |
| Open.Jarvis | Windows uchun Jarvis yordamchisi | Ovozli/matnli buyruqlar va desktop amallari; alohida muhitda xavfsizlik sinovi |
| Leon | Jarvisga o‘xshash shaxsiy yordamchi | Kundalik yordamchi; 2.0 desktop ilovasi hali chiqarilmagan — keyin sinash |
| OpenVoiceOS | Ovozli yordamchi platformasi | Ovoz orqali buyruqlar va ko‘nikmalar; Windows mosligi noma’lum, keyingi bosqich |
| Cline / Continue / Aider | Kodlash agentlari | Mavjud GitHub loyihalarini ishlab chiqish va tuzatish |
| OpenHands | Kodlash agenti | Katta vazifalarni alohida test muhitida bajarish |
| Agent Zero | Umumiy avtonom agent | Docker/Linux ish maydoni va yuqori resurs talabi sababli keyinroq |
| Browser Use | Brauzer agenti | Internetdagi takroriy ishlar va izlanish |
| WhisperX / faster-whisper / F5-TTS / OpenVoice | Ovoz vositalari | Ovoz tahlili, transkripsiya va nutq sintezi |
| Wazuh / osquery | Xavfsizlik vositalari | Windows va fayl holatini kuzatish; FIM loyihasini to‘ldirish |

## Keyingi navbat

| Loyiha | Turi | Nima uchun kerak |
|---|---|---|
| AnythingLLM / MarkItDown / LlamaIndex | Hujjat va bilim bazasi | TATU materiallari, PDF, qidiruv va shaxsiy bilimlar bazasi |
| Mem0 | Agent xotirasi | Shaxsiy yordamchining uzoq muddatli xotira qatlamini qo‘shish |
| Ollama | Mahalliy model muhiti | Internetga ulanmasdan kichik modellarni sinash |
| n8n / CrewAI / LangGraph / Agno / Pydantic AI / Dify | Avtomatlashtirish va agent yaratish | O‘zaro bog‘langan maxsus agentlar yaratish |
| ComfyUI / yt-dlp / RVC | Media vositalari | Rasm, video va ruxsatli media ish jarayonlari |

## Qurilmaga moslik bo‘yicha ogohlantirish

HP Pavilion 15 (Ryzen 7 7730U, 16 GB RAM, integratsiyalashgan Radeon) uchun og‘ir mahalliy model va video generatsiya birinchi navbatda o‘rnatilmaydi. Ollama’da kichik, xotirasi siqilgan modellar; ovozda esa avval CPU yoki yengil model sinovi tanlanadi. ComfyUI keyingi navbatda, ehtimol bulutli GPU bilan ko‘rib chiqiladi.

## Litsenziya va holat

- Litsenziya GitHub API metadata’dan olingan; `NOASSERTION` yoki aniqlashtirish kerak bo‘lganlari alohida tekshirilishi shart.
- GitHub’dagi `archived=true` loyihalar yangi o‘rnatish uchun tavsiya qilinmaydi.
- Roo Code, Flowise va Microsoft AutoGen ushbu yangilanishga kiritilmadi: tekshiruv paytida arxivlangan deb ko‘rindi.
- Tashqi repozitoriyalarning kodi ko‘chirilmaydi. FOYDALI AGENTLAR faqat rasmiy manba, metama’lumot va o‘rnatish yo‘riqnomasini saqlaydi.
- Katalogga qo‘shish o‘rnatish, xavfsizlik auditi yoki Windows sinovidan o‘tganini anglatmaydi.

## O‘rnatishdan oldingi majburiy tekshiruv

1. Rasmiy README va o‘rnatish hujjatini ko‘rish.
2. Litsenziya fayli va uchinchi tomon komponentlarini tekshirish.
3. Windows 11 mosligi va Python/Node/Docker talablarini aniqlash.
4. Disk, RAM, CPU/GPU va internet sarfini baholash.
5. O‘rnatish skriptini ko‘rib chiqish; noma’lum buyruqni avtomatik bajarmaslik.
6. Alohida papka yoki virtual muhitda sinash.
7. O‘chirish va yangilash yo‘lini tasdiqlash.
