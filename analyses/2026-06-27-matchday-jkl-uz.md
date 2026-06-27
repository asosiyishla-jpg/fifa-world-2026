# 2026 FIFA Jahon Chempionati — Bashorat To'plami (J, K, L guruhlari)

> Guruh bosqichi yakuniy turi (Matchday 17) · 27 iyun 2026 · Faqat bashorat (natija hali yo'q)
> Tizim: INSTRUCTION.md + SOURCES.md + STRUCTURE.md + STYLE.md · Versiya 1.1

---

## Muqaddima — Tekshiruv va Halollik Eslatmasi

**Guruh tekshiruvi (SOURCES.md §4):** J, K, L guruhlari kanonik jadval bilan mos.
- J guruhi: Argentina, Jazoir, Avstriya, Iordaniya
- K guruhi: Portugaliya, O'zbekiston, Kongo DR, Kolumbiya
- L guruhi: Angliya, Xorvatiya, Gana, Panama

**Natija holati:** Bu olti o'yin **27 iyunga (Matchday 17) rejalashtirilgan** — tizim sanasi (24 iyun) holatiga hali o'ynalmagan. Manba: FIFA ("group stage concludes on Saturday, 27 June"). Shuning uchun **faqat bashorat**; real natija o'yinlardan keyin qo'shiladi.

**Joriy forma (Level 2 manbalar — ESPN, USA Today, FIFA):**
- L: Angliya 4 ochko (Xorvatiya 4-2, Gana 0-0), Gana 4, Xorvatiya 3 (Panama 1-0), Panama 0 (chetlatilgan).
- K: Portugaliya 4 (Kongo DR 1-1, O'zbekiston 5-0), Kolumbiya yetakchi (Kongo DR 1-0), O'zbekiston 0 (8 gol o'tkazgan).
- J: Argentina guruh g'olibi (Avstriyani 2-0, Messi rekordi); Jazoir Iordaniyani 2-1 yutgan.

**Kalibrlash:** A/B/C auditidan saboq — kuchli favorit $\lambda$ oshirildi. Real Elo: Argentina ~2192, Angliya ~2073 (eloratings.net shkalasi). Dinamik tarkib/xG → `[MANBA TALAB QILINADI]`.

---

## 1-O'YIN — Panama vs Angliya · L guruhi · 02:00

| Ko'rsatkich | Panama | Angliya | Durrang |
|---|---|---|---|
| Elo (taxminiy/real) | ~1600 | **~2073** | — |
| Elo g'alaba ehtimoli $W_e$ | 6.2% | 93.8% | — |
| Puasson g'alaba ehtimoli | 5.7% | 79.4% | 14.9% |
| Kutilgan gollar $\lambda$ | 0.45 | 2.30 | — |
| Eng ehtimoliy hisob | — | — | **0-2 (~16.9%)**, keyin 0-1 (~14.7%) |

$W_e(\text{ENG}) = \frac{1}{10^{(1600-2073)/400}+1} = 0.938$

**[Bashorat]** 473 ochkolik Elo farqi Angliyaga 93.8% xom ehtimol beradi. Va kalibrlangan $\lambda_{ENG}=2.30$ Puassonda 79.4% toza g'alaba beradi. Panama oltita JCh o'yinining barchasini yutqazgan — $\lambda_{PAN}=0.45$ shu zaiflikni aks ettiradi. Biroq Angliya guruh tepasini ta'minlash uchun rotatsiya qilishi mumkin.

---

## 2-O'YIN — Xorvatiya vs Gana · L guruhi · 02:00

| Ko'rsatkich | Xorvatiya | Gana | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1920 | ~1660 | — |
| Elo g'alaba ehtimoli $W_e$ | 81.7% | 18.3% | — |
| Puasson g'alaba ehtimoli | 53.1% | 22.4% | 24.5% |
| Kutilgan gollar $\lambda$ | 1.65 | 0.95 | — |
| Eng ehtimoliy hisob | — | — | **1-0 (~12.3%)**, keyin 1-1 (~11.6%) |

$W_e(\text{CRO}) = \frac{1}{10^{(1660-1920)/400}+1} = 0.817$

**[Bashorat]** 260 ochkolik Elo farqi Xorvatiyaga 81.7% xom ehtimol beradi. Lekin Puasson uni 53.1% ga tushiradi — chunki Gana 4 ochko bilan kuchli formada va $\lambda_{GHA}=0.95$ ni saqlaydi. Biroq bu o'yin Xorvatiya uchun "o'lim-qol" — yutmasa, chetlatilishi mumkin, va Modric boshchiligidagi markaz $\lambda=1.65$ ni ta'minlaydi.

---

## 3-O'YIN — Kolumbiya vs Portugaliya · K guruhi · 04:30

| Ko'rsatkich | Kolumbiya | Portugaliya | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1985 | ~1995 | — |
| Elo g'alaba ehtimoli $W_e$ | 48.6% | 51.4% | — |
| Puasson g'alaba ehtimoli | 35.0% | 37.7% | 27.3% |
| Kutilgan gollar $\lambda$ | 1.20 | 1.25 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~12.9%)** |

**[Bashorat]** 10 ochkolik Elo farqi statistik shovqin — deyarli teng (guruh tepasi uchun kurash). Va Puasson buni tasdiqlaydi: 37.7% va 35.0%, durrang 27.3%. Biroq Portugaliya O'zbekistonni 5-0 yutgan formada (Ronaldu dubl), lekin Kolumbiya himoyasi mustahkam — modal hisob tor 1-1.

---

## 4-O'YIN — Kongo DR vs O'zbekiston · K guruhi · 04:30

| Ko'rsatkich | Kongo DR | O'zbekiston | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1680 | ~1640 | — |
| Elo g'alaba ehtimoli $W_e$ | 55.7% | 44.3% | — |
| Puasson g'alaba ehtimoli | 40.7% | 31.1% | 28.2% |
| Kutilgan gollar $\lambda$ | 1.25 | 1.05 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~13.2%)**, keyin 1-0 (~12.5%) |

**[Bashorat]** 40 ochkolik Elo farqi Kongo DRga ozgina ustunlik beradi (55.7%). Va Puasson 40.7% toza g'alaba qaytaradi. O'zbekiston debyut turnirida 8 gol o'tkazib, 0 ochkoda — $\lambda_{UZB}=1.05$ baribir kontr-imkoniyatlarni saqlaydi. Biroq durrang ehtimoli yuqori (28.2%) — past-farqli o'yin kutiladi.

---

## 5-O'YIN — Jazoir vs Avstriya · J guruhi · 07:00

| Ko'rsatkich | Jazoir | Avstriya | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1780 | ~1850 | — |
| Elo g'alaba ehtimoli $W_e$ | 40.1% | 59.9% | — |
| Puasson g'alaba ehtimoli | 31.7% | 41.5% | 26.8% |
| Kutilgan gollar $\lambda$ | 1.15 | 1.35 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~12.7%)**, keyin 0-1 (~11.1%) |

$W_e(\text{AUT}) = \frac{1}{10^{(1780-1850)/400}+1} = 0.599$

**[Bashorat]** 70 ochkolik Elo farqi Avstriyaga 59.9% xom ehtimol beradi. Va bu 1/32 yo'llanmasini hal qiluvchi to'g'ridan-to'g'ri to'qnashuv — g'olib o'tadi. Biroq farq kichik ($\lambda$ 1.35 vs 1.15), shuning uchun durrang ehtimoli 26.8% va modal hisob 1-1 — yuqori taranglikdagi o'yin.

---

## 6-O'YIN — Iordaniya vs Argentina · J guruhi · 07:00

| Ko'rsatkich | Iordaniya | Argentina | Durrang |
|---|---|---|---|
| Elo (taxminiy/real) | ~1560 | **~2192** | — |
| Elo g'alaba ehtimoli $W_e$ | 2.6% | 97.4% | — |
| Puasson g'alaba ehtimoli | 5.7% | 79.4% | 14.9% |
| Kutilgan gollar $\lambda$ | 0.45 | 2.30 | — |
| Eng ehtimoliy hisob | — | — | **0-2 (~16.9%)**, keyin 0-1 (~14.7%) |

$W_e(\text{ARG}) = \frac{1}{10^{(1560-2192)/400}+1} = 0.974$

**[Bashorat]** 632 ochkolik Elo farqi — to'plamdagi eng kengi — Argentinaga 97.4% xom ehtimol beradi. Va kalibrlangan $\lambda_{ARG}=2.30$ Puassonda 79.4% toza g'alaba beradi. Biroq Argentina guruhni allaqachon yutgani uchun (Messi rekordi) muhim o'yinchilarni dam oldirib, rotatsiya qilishi ehtimoli yuqori — bu real $\lambda$ ni modeldan pasaytirishi mumkin.

---

## To'plam Muvofiqlik Xulosasi (Jadval 3.3 qisqartirilgan)
| Mezon | Holat |
|---|---|
| Guruhlar SOURCES.md §4 bo'yicha tekshirildi | OK (J, K, L) |
| Real Elo qisman (Argentina, Angliya) | OK |
| Kalibrlash (favorit $\lambda$) | OK — A/B/C auditi |
| Puasson/Elo hisoblandi | OK |
| Real natija taqqoslashi | KUTILMOQDA — o'yinlar 27 iyun |
| Dinamik tarkib/xG | `[MANBA TALAB QILINADI]` |

---

*Fayl: analyses/2026-06-27-matchday-jkl-uz.md · Versiya 1.1*
*Bashorat rejimi · Natija taqqoslashi o'yinlardan keyin qo'shiladi*
