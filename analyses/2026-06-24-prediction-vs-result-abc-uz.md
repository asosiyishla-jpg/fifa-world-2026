# Bashorat vs Real Natija — A, B, C guruhlari (24 iyun 2026)

> Model bashorati (Puasson & Elo) bilan haqiqiy natijalarning taqqoslashi
> Tizim: INSTRUCTION.md + SOURCES.md + STRUCTURE.md + STYLE.md · Versiya 1.1

---

## Metodologiya va Manba

Quyidagi taqqoslash `analyses/2026-06-26-matchday-uz.md` faylidagi **o'yin oldidan** chiqarilgan Puasson/Elo bashoratlarini, 24 iyun 2026'da o'ynalган o'yinlarning **haqiqiy natijalari** bilan solishtiradi.

**Real natija manbalari (SOURCES.md Level 2):** NBC News, USA Today, AP, Sporting News, ESPN, SBS. Barcha hisoblar kamida 2 ta mustaqil manbada tasdiqlangan (SOURCES.md §1, Level 2 qoidasi). *Maʼlumot litsenziya talablariga moslab qayta yozildi.*

**Eslatma:** Model bashorati taxminiy ochiq Elo bazasidan chiqarilgan edi. Bu taqqoslash modelning kuchli va zaif tomonlarini halol baholash uchun.

---

## O'yin-bo'yicha Taqqoslash

### 1. Shveytsariya vs Kanada · B guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | Shveytsariya (46.0%) | **Shveytsariya** |
| Modal hisob | 1-1 (~12.3%) | **2-1** |
| Yakun | Shveytsariya g'alabasi eng yuqori ehtimol | Shveytsariya 2-1 g'alaba |

**Verdikt:** ✅ Favorit to'g'ri. Model durrangni modal deb belgilagan bo'lsa-da, eng yuqori bitta natija (Shveytsariya g'alabasi, 46.0%) amalga oshdi. 2-1 hisob modelning 3-eng ehtimoliy stsenariysi edi.

---

### 2. Bosniya va Gertsegovina vs Qatar · B guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | Bosniya (42.0%) | **Bosniya** |
| Modal hisob | 1-1 (~13.0%) | **3-1** |
| $\lambda$ | 1.30 / 1.05 | Real: 3 / 1 |

**Verdikt:** ✅ Favorit to'g'ri. Lekin $\lambda_{BIH}=1.30$ aniq goldan past edi — Bosniya 3 gol urdi. Model g'olibni topdi, ammo gol hajmini past baholadi.

---

### 3. Marokash vs Gaiti · C guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | Marokash (64.6%) | **Marokash** |
| Modal hisob | 1-0 (~14.1%) | **4-2** |
| $\lambda$ yig'indisi | 1.90 + 0.70 = 2.60 | Real: 4 + 2 = 6 gol |

**Verdikt:** ✅ Favorit to'g'ri. Lekin bu modelning eng katta gol-baholash xatosi — jami 6 gol modellashtirilgan 2.60 ga qarshi. Gaiti 2 gol urdi ($\lambda=0.70$ dan ancha yuqori), Marokash esa 4 — past blokka qarshi past gol farazimiz noto'g'ri chiqdi.

---

### 4. Shotlandiya vs Braziliya · C guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | Braziliya (64.6%) | **Braziliya** |
| Modal hisob | 0-1 (~14.1%) | **0-3** (Vinicius x2, Cunha) |
| $\lambda_{BRA}$ | 1.90 | Real: 3 |

**Verdikt:** ✅ Favorit to'g'ri. Braziliya kutilgandan kattaroq farq bilan yutdi; $\lambda_{BRA}=1.90$ biroz past edi. Shotlandiya himoyasi modeldagidan zaifroq chiqdi.

---

### 5. Janubiy Afrika vs Koreya Respublikasi · A guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | **Koreya Respublikasi (48.7%)** | **Janubiy Afrika** |
| Modal hisob | 0-1 (~13.2%) | **1-0** (Maseko) |
| Janubiy Afrika g'alaba ehtimoli | 24.7% | — |

**Verdikt:** ❌ **Modelning yagona xatosi.** Model Koreya Respublikasini favorit qildi (48.7%), lekin Janubiy Afrika 1-0 yutdi. Bu modelning taxminiy Elo bazasi (RSA ~1720 vs KOR ~1840) haqiqatni aks ettirmaganini ko'rsatadi — real natija Janubiy Afrikaning kuchini past baholaganimizni isbotladi. Bu aniq "upset" (24.7% ehtimolli stsenariy).

---

### 6. Chexiya vs Meksika · A guruhi
| | Bashorat (model) | Real natija |
|---|---|---|
| Favorit | Meksika (45.2%) | **Meksika** |
| Modal hisob | 1-1 (~12.5%) | **0-3** |
| $\lambda_{MEX}$ | 1.45 | Real: 3 |

**Verdikt:** ✅ Favorit to'g'ri. Meksika kutilgandan ancha katta farq bilan yutdi (Elo ~2072 — turnirning eng yuqori uy-egasi reytingi buni qisman tushuntiradi).

---

## Umumiy Aniqlik Tahlili (Jadval 3.1 — Model Auditi)

| Ko'rsatkich | Natija |
|---|---|
| **G'olibni (1X2) to'g'ri topish** | **5 / 6 (83.3%)** |
| Aniq hisobni (modal) to'g'ri topish | 0 / 6 (kutilgan — modal ehtimollar atigi ~12–14%) |
| Tizimli xato | $\lambda$ qiymatlari past — 4/6 o'yinda gol hajmi past baholandi |
| Yagona "upset" | Janubiy Afrika 1-0 Koreya Respublikasi (model 24.7% bergan) |

### Asosiy xulosalar
1. **Model g'olibni topishda kuchli** — 6 tadan 5 tasida favorit to'g'ri (83%). Va bu Elo asosli ehtimol modelining ishonchli ekanini ko'rsatadi.
2. **Gol hajmi tizimli ravishda past baholandi.** Real o'yinlarda favoritlar kutilgandan kattaroq farq bilan yutdi (3-0, 3-0, 4-2, 3-1). Demak kelgusi bashoratlar uchun favorit $\lambda$ qiymatlarini biroz oshirish kerak.
3. **Yagona xato taxminiy Elo bazasidan keldi** — Janubiy Afrika–Koreya Respublikasi. Real (tasdiqlangan) Elo bilan model bu o'yinni boshqacha baholashi mumkin edi. Bu SOURCES.md §2 "tasdiqlangan maʼlumotdan foydalanish" prinsipining qiymatini isbotlaydi.

---

## D, E, F guruhlari — Natija holati

D/E/F guruhi o'yinlari (Kurasao–Côte d'Ivoire, Ekvador–Germaniya, Tunis–Niderlandiya, Yaponiya–Shvetsiya, Türkiye–AQSH, Paragvay–Avstraliya) **25–26 iyunga rejalashtirilgan** — tizim sanasi (24 iyun) holatiga hali o'ynalmagan. Manbalar ularni "kelgusi" deb ko'rsatadi (ESPN: "Ecuador vs Germany — Live Score, June 25, 2026"). Shuning uchun bu o'yinlar uchun **real natija taqqoslashi hali mumkin emas** — bashoratlar `analyses/2026-06-26-matchday-def-uz.md` faylida tayyor, natijalar chiqqach taqqoslash qo'shiladi.

---

*Fayl: analyses/2026-06-24-prediction-vs-result-abc-uz.md · Versiya 1.1*
*Model auditi: Puasson/Elo bashorati vs tasdiqlangan real natija*
