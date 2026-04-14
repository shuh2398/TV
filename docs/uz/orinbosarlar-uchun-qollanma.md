# Tuman hokimi o'rinbosarlari uchun qo'llanma

> **Auditoriya:** Qashqadaryo viloyatining 13 tumani bo'yicha tuman
> hokimining investitsiyalar masalalari bo'yicha o'rinbosarlari.
> **Maqsad:** har bir o'rinbosar har chorakda (va undan tez-tez) o'z
> tumani ma'lumotlarini yagona tizimga kiritadi, viloyat hokimining
> o'rinbosari apparati to'liq manzarani ko'radi.

## GitHub nima va ushbu ombor haqida

GitHub — hujjatlar bilan birgalikda ishlash tizimi. Barcha ma'lumotlar
markazlashtirilgan holda saqlanadi, har bir o'zgarish muallif tomonidan
imzolanadi va tarixda saqlanadi. Siz tasodifan boshqalarning
ma'lumotlarini o'chira olmaysiz — tizim buni taqiqlaydi.

Ombor manzili: `https://github.com/shuh2398/TV`

## Siz nimani to'ldirasiz

`districts/` papkasida 13 ta quyi papka mavjud — har bir tuman uchun
bitta. Sizning papkangizda (masalan, `districts/03-shahrisabz/`) 4 ta
fayl bor:

| Fayl | Nimani kiritish | Chastota |
|------|-----------------|----------|
| `plan.md` | Yillik reja: investitsiyalar, loyihalar, ish o'rinlari, eksport | Yiliga bir marta |
| `execution.md` | Chorak bo'yicha haqiqat, bajarilish foizi | Har chorakda |
| `projects.md` | Muayyan loyihalar ro'yxati xarakteristikalari bilan | O'zgarishlar sari |
| `sites.md` | Bo'sh yer uchastkalari va binolar | Har oyda |

**Siz FAQAT o'z tumaningiz papkasini tahrirlay olasiz.** Boshqa tumanni
o'zgartirishga urinish tizim tomonidan avtomatik bloklanadi
(CODEOWNERS).

## Birlamchi sozlash (bir marta)

1. **GitHub'da ro'yxatdan o'tish.** `https://github.com` saytiga o'ting,
   ish pochtasi bilan hisob yarating. Loginni (username) eslab qoling va
   viloyat hokimi o'rinbosari apparatiga xabar qiling.
2. **Ikki bosqichli autentifikatsiya.** Sozlamalarda 2FA'ni yoqing
   (SMS yoki Google Authenticator ilovasi) — bu axborot xavfsizligi
   talabi.
3. **Omborga taklif.** Viloyat apparati pochtangizga taklifnoma
   yuboradi — **«Accept invitation»** tugmasini bosing.
4. **Kirishni tekshirish.** Ombor havolasini oching, o'z tumaningiz
   papkasiga kiring, fayllarni ko'rayotganingizga ishonch hosil qiling.

## O'zgartirish qanday kiritiladi (har safar)

### A variant: GitHub veb-interfeysi orqali (tavsiya etiladi)

1. Kerakli faylni oching, masalan `districts/03-shahrisabz/execution.md`.
2. Yuqori o'ng burchakdagi qalam belgisini bosing (✏️ **Edit this file**).
3. Brauzerda to'g'ridan-to'g'ri tahrirlang — jadvallar Markdown
   formatida, `|` belgisi ustunlarni ajratadi.
4. Sahifaning pastki qismidagi **«Commit changes»** blokiga o'ting.
5. Birinchi maydonda qisqacha yozing: `Q1 2026 haqiqat yangilandi`.
6. **«Create a new branch and start a pull request»** tanlang.
7. Branch nomini o'zgartirmay **«Propose changes»** bosing.
8. Keyingi ekranda **«Create pull request»** bosing.
9. PR shabloni maydonlarini to'ldiring (davr, manba, imzo).
10. Yana **«Create pull request»** bosing.
11. Viloyat apparatining tasdig'ini kuting (odatda 1–2 ish kuni).

### B variant: GitHub mobil ilovasi orqali

Xuddi shunday, telefondan — iOS va Android uchun GitHub ilovasi mavjud.

## Jadvallarni to'ldirish qoidalari

- **Summalar** — million AQSh dollarida (boshqacha ko'rsatilmagan
  bo'lsa), vergul emas, nuqta ishlating: `12.5`, `12,5` emas.
- **Sonlar** — bo'sh joylarsiz butun: `245`, `245 kishi` emas.
- **Sanalar** — `YYYY-MM-DD` formatida: `2026-04-14`.
- **Bo'sh maydonlar** — bo'sh qoldiring, mavjud bo'lmagan ma'lumot
  o'rniga `0` qo'ymang.
- Jadval satrlari va ustunlarini o'chirmang. Qator yetishmasa —
  oxirgisini nusxalab, pastga qo'shing.

## Xato yuz bersa nima qilish kerak

- PR tasdiqlanmagan bo'lsa — faylni oching, yana qalam bosib, **o'sha
  branch**ga tuzatish kiriting.
- PR tasdiqlangan va qo'shilgan bo'lsa — yangi PR yarating.
- Ishlamasa — viloyat apparatiga `TODO@email` yoki `TODO-raqam`
  orqali bog'laning.

## Nima qilmaslik kerak

- ❌ Jadvallar tuzilmasini (sarlavhalar, ustunlar tartibi)
  o'zgartirmang.
- ❌ Boshqalarning ma'lumotlarini — noto'g'ri tuyulsa ham —
  o'chirmang, viloyat apparatiga xabar bering.
- ❌ Omborga jismoniy shaxslarning shaxsiy ma'lumotlarini (pasport,
  STIR, yashash manzili) joylamang.
- ❌ GitHub parolingizni hamkasblarga bermang.

## Qo'llab-quvvatlash aloqalari

- **Qashqadaryo viloyati hokimi o'rinbosari apparati:**
  `TODO@email`, tel. `TODO`
- **GitHub texnik qo'llab-quvvatlash (ingliz tilida):**
  `https://support.github.com`
