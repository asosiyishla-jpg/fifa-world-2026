# 2026 FIFA Jahon Chempionati — Bashorat To'plami (G, H, I guruhlari)

> Guruh bosqichi yakuniy turi · 26 iyun 2026 · Faqat bashorat (natija hali yo'q)
> Tizim: INSTRUCTION.md + SOURCES.md + STRUCTURE.md + STYLE.md · Versiya 1.1

---

## Muqaddima — Tekshiruv, Kalibrlash va Halollik Eslatmasi

**Guruh tekshiruvi (SOURCES.md §4):** G, H, I guruhlari kanonik jadval bilan mos.
- G guruhi: Belgiya, Misr, Eron, Yangi Zelandiya
- H guruhi: Ispaniya, Cabo Verde, Saudiya Arabistoni, Urugvay
- I guruhi: Fransiya, Senegal, Norvegiya, Iroq

**Nom eslatmasi (STYLE.md §4):** FIFA rasmiy yozuvi **Cabo Verde** (SOURCES.md'dagi "Cape Verde" emas).

**Natija holati:** Bu olti o'yin **26 iyunga rejalashtirilgan** — tizim sanasi (24 iyun) holatiga hali o'ynalmagan (ESPN: "Norway vs France — Jun 26, 2026 Live Score"). Shuning uchun bu yerda **faqat bashorat** bor; real natija taqqoslashi o'yinlar o'ynalgach qo'shiladi.

**Kalibrlash (A/B/C auditidan saboq):** Avvalgi A/B/C taqqoslashida model favoritni 83% to'g'ri topgan, lekin gol hajmini tizimli past baholagan edi. Shu sababli bu to'plamda kuchli favoritlar uchun $\lambda$ qiymatlari biroz oshirildi.

**Real Elo:** Fransiya (~2132) va Ispaniya (~2122) qiymatlari eloratings.net shkalasidagi yangi maʼlumotga asoslangan (macfax/usu, 19 iyun 2026). Qolganlari taxminiy baza. Dinamik tarkib/xG → `[MANBA TALAB QILINADI]`.

---

## 1-O'YIN — Norvegiya vs Fransiya · I guruhi · 00:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Norvegiya | Fransiya | Durrang |
|---|---|---|---|
| Elo (taxminiy/real) | ~1900 | ~2132 | — |
| Elo g'alaba ehtimoli $W_e$ | 20.8% | 79.2% | — |
| Puasson g'alaba ehtimoli | 14.1% | 64.5% | 21.5% |
| Kutilgan gollar $\lambda$ | 0.80 | 2.00 | — |
| Eng ehtimoliy hisob | — | — | **0-1 / 0-2 (~12.2%)** |

$W_e(\text{FRA}) = \frac{1}{10^{(1900-2132)/400}+1} = 0.792$

**[Bashorat]** 232 ochkolik Elo farqi Fransiyaga 79.2% xom ehtimol beradi. Lekin Puasson uni 64.5% ga tushiradi, chunki bitta gol ham guruh g'olibligini hal qilishi mumkin. Va Norvegiyaning Haaland orqali kontrhujum tahdidi $\lambda=0.80$ ni tirik saqlaydi. Biroq Fransiya hujum chuqurligi $\lambda=2.00$ bilan ustun.

---

## 2-O'YIN — Senegal vs Iroq · I guruhi · 00:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Senegal | Iroq | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1900 | ~1650 | — |
| Elo g'alaba ehtimoli $W_e$ | 80.8% | 19.2% | — |
| Puasson g'alaba ehtimoli | 66.7% | 13.0% | 20.3% |
| Kutilgan gollar $\lambda$ | 1.95 | 0.65 | — |
| Eng ehtimoliy hisob | — | — | **1-0 (~14.5%)**, keyin 2-0 (~14.1%) |

$W_e(\text{SEN}) = \frac{1}{10^{(1650-1900)/400}+1} = 0.808$

**[Bashorat]** 250 ochkolik Elo farqi Senegalga 80.8% xom ehtimol beradi. Va Puasson 66.7% toza g'alaba qaytaradi. Biroq Iroqning kompakt himoyasi modal hisobni tor 1-0 da ushlaydi — $\lambda_{IRQ}=0.65$ kam hodisali variansni saqlaydi.

---

## 3-O'YIN — Cabo Verde vs Saudiya Arabistoni · H guruhi · 05:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Cabo Verde | Saudiya Arabistoni | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1630 | ~1660 | — |
| Elo g'alaba ehtimoli $W_e$ | 45.7% | 54.3% | — |
| Puasson g'alaba ehtimoli | 32.9% | 38.0% | 29.1% |
| Kutilgan gollar $\lambda$ | 1.05 | 1.15 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~13.4%)** |

**[Bashorat]** 30 ochkolik Elo farqi statistik shovqin — deyarli teng. Va Puasson buni tasdiqlaydi: 38.0% va 32.9% bilan yaqin, durrang 29.1%. Biroq Cabo Verdening turnirdagi mustahkam darajasi (Ispaniya va Urugvayni durrangda ushlagan) modeldagi Elo bazasidan yuqori bo'lishi mumkin — bu yerda upset xavfi bor.

---

## 4-O'YIN — Urugvay vs Ispaniya · H guruhi · 05:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Urugvay | Ispaniya | Durrang |
|---|---|---|---|
| Elo (taxminiy/real) | ~1990 | ~2122 | — |
| Elo g'alaba ehtimoli $W_e$ | 31.9% | 68.1% | — |
| Puasson g'alaba ehtimoli | 20.9% | 55.1% | 24.0% |
| Kutilgan gollar $\lambda$ | 0.95 | 1.70 | — |
| Eng ehtimoliy hisob | — | — | **0-1 (~12.0%)**, keyin 1-1 (~11.4%) |

$W_e(\text{ESP}) = \frac{1}{10^{(1990-2122)/400}+1} = 0.681$

**[Bashorat]** 132 ochkolik Elo farqi Ispaniyaga 68.1% xom ehtimol beradi. Va Puasson 55.1% toza g'alaba qaytaradi. Biroq Urugvayning tashkillashgan himoyasi $\lambda_{ESP}$ ni 1.70 da cheklaydi — bu o'yin guruh joylashuvini hal qiluvchi yuqori-ulushli to'qnashuv.

---

## 5-O'YIN — Yangi Zelandiya vs Belgiya · G guruhi · 08:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Yangi Zelandiya | Belgiya | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1510 | ~1950 | — |
| Elo g'alaba ehtimoli $W_e$ | 7.4% | 92.6% | — |
| Puasson g'alaba ehtimoli | 8.1% | 74.5% | 17.3% |
| Kutilgan gollar $\lambda$ | 0.55 | 2.15 | — |
| Eng ehtimoliy hisob | — | — | **0-2 (~15.5%)**, keyin 0-1 (~14.4%) |

$W_e(\text{BEL}) = \frac{1}{10^{(1510-1950)/400}+1} = 0.926$

**[Bashorat]** 440 ochkolik Elo farqi — to'plamdagi eng kengi — Belgiyaga 92.6% xom ehtimol beradi. Va kalibrlangan $\lambda_{BEL}=2.15$ Puassonda 74.5% toza g'alaba beradi. Biroq Belgiya oldingi ikki o'yinda gol urolmagan (Eron bilan 0-0, Misr bilan 1-1), shuning uchun real gol hosilasi modeldan past chiqishi mumkin.

---

## 6-O'YIN — Misr vs Eron · G guruhi · 08:00

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)
| Ko'rsatkich | Misr | Eron | Durrang |
|---|---|---|---|
| Elo (taxminiy) | ~1730 | ~1790 | — |
| Elo g'alaba ehtimoli $W_e$ | 41.4% | 58.6% | — |
| Puasson g'alaba ehtimoli (forma-bo'yicha) | 37.5% | 32.6% | 29.9% |
| Kutilgan gollar $\lambda$ | 1.10 | 1.00 | — |
| Eng ehtimoliy hisob | — | — | **1-1 / 1-0 (~13.5%)** |

**[Bashorat]** Bu yerda ikki model bir-biriga zid: Elo tarixiy reyting bo'yicha Eronni biroz favorit qiladi (58.6%), lekin forma-bo'yicha sozlangan $\lambda$ (Misr guruh tepasida, Salah omili) Puassonda Misrga ozgina ustunlik beradi (37.5%). Va Eronning himoyaviy uslubi (Beiranvand, ikki "clean sheet") past gol profilini bashorat qiladi. Biroq durrang ehtimoli yuqori — 29.9% — bu o'yin guruhdagi eng noaniq to'qnashuv.

---

## To'plam Muvofiqlik Xulosasi (Jadval 3.3 qisqartirilgan)
| Mezon | Holat |
|---|---|
| Guruhlar SOURCES.md §4 bo'yicha tekshirildi | OK (G, H, I — tuzatish shart emas) |
| FIFA nomlanishi (Cabo Verde) | OK |
| Real Elo qisman qo'llandi (Fransiya, Ispaniya) | OK |
| Kalibrlash (favorit $\lambda$ oshirildi) | OK — A/B/C auditi asosida |
| Puasson/Elo hisoblandi | OK |
| Real natija taqqoslashi | KUTILMOQDA — o'yinlar 26 iyun |
| Dinamik tarkib/xG | `[MANBA TALAB QILINADI]` |

---

*Fayl: analyses/2026-06-26-matchday-ghi-uz.md · Versiya 1.1*
*Bashorat rejimi · Natija taqqoslashi o'yinlardan keyin qo'shiladi*
