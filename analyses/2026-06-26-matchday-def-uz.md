# 2026 FIFA Jahon Chempionati — To'liq Tahliliy To'plam (D, E, F guruhlari)

> Guruh bosqichi · Juma, 26 iyun 2026
> Tizim: INSTRUCTION.md + SOURCES.md + STRUCTURE.md + STYLE.md asosida
> Versiya: 1.1

---

## Muqaddima — Tekshiruv va Halollik Eslatmasi

**Guruh tekshiruvi (SOURCES.md §4):** Barcha guruhlar kanonik jadval bilan to'liq mos, tuzatish talab qilinmadi.
- E guruhi: Germaniya, Kurasao, Côte d'Ivoire, Ekvador
- F guruhi: Niderlandiya, Yaponiya, Shvetsiya, Tunis
- D guruhi: AQSH (Amerika Qo'shma Shtatlari), Paragvay, Avstraliya, Türkiye

**Nom eslatmasi (STYLE.md §4):** Rasmiy FIFA nomlanishi saqlangan — Côte d'Ivoire, Curaçao (Kurasao), Türkiye.

**Maʼlumot halolligi (SOURCES.md §2 — "Bilmayman" prinsipi):** Jonli tarkib, jarohat va real xG 24 soatlik talab darajasida tasdiqlanmagani uchun `[MANBA TALAB QILINADI]` deb belgilangan. Elo raqamlari — taxminiy ochiq bazaviy qiymatlar (tasdiqlangan jonli qiymat emas). Puasson hisobi shu bazaviy qiymatlardan aniq hisoblangan va ichki izchil.

**Matematik asos:**
- Elo: $W_e = \frac{1}{10^{(R_B - R_A)/400}+1}$
- Puasson: $P(x) = \frac{\lambda^x e^{-\lambda}}{x!}$
- Aerodinamika: $F_d = \frac{1}{2}\rho v^2 C_d A$

---

## 1-O'YIN — Kurasao vs Côte d'Ivoire · E guruhi · 01:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Kurasao | ~1530 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-4-2, ixcham past blok | Tashkillashgan himoya |
| Côte d'Ivoire | ~1770 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-3-3, jismoniy hujum | Qanot kuchi + tezlik |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Kurasao | Côte d'Ivoire | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 20.1% | 79.9% | — |
| Puasson g'alaba ehtimoli | 17.4% | 58.8% | 23.8% |
| Kutilgan gollar $\lambda$ | 0.80 | 1.70 | — |
| Eng ehtimoliy hisob | — | — | **0-1 (~14.0%)**, keyin 0-2 (~11.9%) |

$W_e(\text{CIV}) = \frac{1}{10^{(1530-1770)/400}+1} = 0.799$

**[1-blok]** 240 ochkolik Elo farqi Côte d'Ivoirega 79.9% xom ehtimol beradi. Lekin Puasson toza g'alabani 58.8% ga tushiradi, chunki $\lambda_{CUW}=0.80$ baribir 23.8% durrang massasini saqlaydi.

**[2-blok]** Kurasao ixcham past blok orqali maydon yuzasini kamaytirib, Côte d'Ivoire jismoniy ustunligini neytrallashga harakat qiladi. Va agar markaziy zona yopiq qolsa, hujum qanotlarga suriladi. Biroq $\lambda_{CIV}=1.70$ aynan shu qanot hajmidan oziqlanadi.

**[3-blok]** Hal qiluvchi o'zgaruvchi — Côte d'Ivoire qanot o'yinchilarining sprint tezligi `[MANBA TALAB QILINADI]`. Past blokka qarshi $F_d = \tfrac{1}{2}\rho v^2 C_d A$ bilan boshqariladigan kuchli uzatmalar rikoshet goli ehtimolini oshiradi.

**[4-blok]** 0-1 va 0-2 birgalikda ~25.9%. Demak model hajm hisobiga ishonchli g'alabani kutadi.

---

## 2-O'YIN — Ekvador vs Germaniya · E guruhi · 01:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Ekvador | ~1830 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-4-2, intensiv himoya | Jismoniylik + kontrhujum |
| Germaniya | ~1960 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-2-3-1, pozitsion hujum | To'p egallash + chiziq buzish |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Ekvador | Germaniya | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 32.1% | 67.9% | — |
| Puasson g'alaba ehtimoli | 21.3% | 52.6% | 26.2% |
| Kutilgan gollar $\lambda$ | 0.85 | 1.50 | — |
| Eng ehtimoliy hisob | — | — | **0-1 (~14.3%)**, keyin 1-1 (~12.2%) |

$W_e(\text{GER}) = \frac{1}{10^{(1830-1960)/400}+1} = 0.679$

**[1-blok]** 130 ochkolik Elo farqi Germaniyaga 67.9% xom ehtimol beradi. Va Puasson 52.6% toza g'alaba qaytaradi, chunki Ekvadorning mustahkam himoyasi $\lambda$ ni 0.85 da ushlab turadi.

**[2-blok]** Ekvador intensiv 4-4-2 bloki orqali Germaniyaning markaziy chiziq buzishini cheklashga intiladi. Lekin Germaniyaning pozitsion strukturasi son bilan yopib bo'lmaydigan sifatli holatlar yaratadi. Biroq Ekvador kontrhujumi $\lambda=0.85$ ni tirik saqlaydigan yagona real tahdid.

**[3-blok]** Hal qiluvchi ko'rsatkich — Ekvador bloki intensivligini 90 daqiqa ushlab turishi `[MANBA TALAB QILINADI]`. PPDA qiymati 60-daqiqadan keyin pasaysa, Germaniya o'tish hajmi keskin oshadi.

**[4-blok]** 0-1 va 1-1 birgalikda ~26.5%. Demak Germaniya favorit, lekin Ekvador durrang zonasida raqobatbardosh.

---

## 3-O'YIN — Tunis vs Niderlandiya · F guruhi · 04:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Tunis | ~1690 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-5-1, chuqur past blok | Tashkillashgan himoya |
| Niderlandiya | ~1970 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-3-3, nazoratli hujum | Strukturali progress + xG |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Tunis | Niderlandiya | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 16.6% | 83.4% | — |
| Puasson g'alaba ehtimoli | 13.5% | 64.8% | 21.7% |
| Kutilgan gollar $\lambda$ | 0.70 | 1.85 | — |
| Eng ehtimoliy hisob | — | — | **0-1 (~14.4%)**, keyin 0-2 (~13.4%) |

$W_e(\text{NED}) = \frac{1}{10^{(1690-1970)/400}+1} = 0.834$

**[1-blok]** 280 ochkolik Elo farqi Niderlandiyaga 83.4% xom ehtimol beradi. Lekin Puasson toza g'alabani 64.8% ga tushiradi, chunki $\lambda_{TUN}=0.70$ kam hodisali dispersiya orqali 21.7% durrang massasini kiritadi.

**[2-blok]** Tunis chuqur 4-5-1 bloki orqali maydon yuzasini minimallashtirib, Niderlandiyani kamroq qiymatli uzatmalarga majburlaydi. Va chuqur blokka qarshi Niderlandiya vazifasi yaratishdan penetratsiyaga aylanadi. Biroq $\lambda=1.85$ doimiy hududiy bosim asosida saqlanadi.

**[3-blok]** Hal qiluvchi o'zgaruvchi — Niderlandiya oxirgi uchdan birdagi yuqori intensivlikdagi takrorlar soni `[MANBA TALAB QILINADI]`. Past blokka qarshi $F_d = \tfrac{1}{2}\rho v^2 C_d A$ aerodinamik hadi uzoqdan urishlar qiymatini oshiradi.

**[4-blok]** 0-1 va 0-2 birgalikda ~27.8%. Demak model nazoratli, lekin tor hisobli g'alabani kutadi.

---

## 4-O'YIN — Yaponiya vs Shvetsiya · F guruhi · 04:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Yaponiya | ~1850 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-2-3-1, tez kombinatsiya | Tempo + texnik progress |
| Shvetsiya | ~1780 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-4-2, jismoniy struktura | Standart holat + balandlik |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Yaponiya | Shvetsiya | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 59.9% | 40.1% | — |
| Puasson g'alaba ehtimoli | 43.6% | 30.4% | 26.0% |
| Kutilgan gollar $\lambda$ | 1.45 | 1.15 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~12.4%)**, keyin 1-0 (~10.8%) |

$W_e(\text{JPN}) = \frac{1}{10^{(1780-1850)/400}+1} = 0.599$

**[1-blok]** 70 ochkolik Elo farqi Yaponiyaga 59.9% xom ehtimol beradi, biroq Puasson uni 43.6% ga siqadi. Va modal yakun ~12.4% bilan 1-1.

**[2-blok]** Yaponiya tez kombinatsion o'yin orqali Shvetsiya 4-4-2 bloki orasida bo'shliqlar yaratishga intiladi. Lekin Shvetsiyaning jismoniy balandligi standart holatlarda alohida tahdid. Biroq Yaponiya tempi blokni cho'zsa, $\lambda=1.45$ gol hosilasi ochiladi.

**[3-blok]** Hal qiluvchi ko'rsatkich — Shvetsiyaning havo duellaridagi g'alaba foizi `[MANBA TALAB QILINADI]`. Standart holatlardagi $F_d = \tfrac{1}{2}\rho v^2 C_d A$ bilan boshqariladigan uzatmalar gol ehtimolini oshiradi.

**[4-blok]** 1-1 va 1-0 birgalikda ~23.2%. Demak Yaponiya favorit, lekin Shvetsiya standart holatlar orqali raqobatbardosh.

---

## 5-O'YIN — Türkiye vs AQSH · D guruhi · 07:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Türkiye | ~1820 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-2-3-1, ijodiy markaz | Markaziy ijodkorlik |
| AQSH | ~1800 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-3-3, energiyali bosim | Jismoniylik + tezlik |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Türkiye | AQSH | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 52.9% | 47.1% | — |
| Puasson g'alaba ehtimoli | 38.9% | 34.7% | 26.4% |
| Kutilgan gollar $\lambda$ | 1.35 | 1.25 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~12.5%)**, keyin 1-0 (~10.0%) |

$W_e(\text{TUR}) = \frac{1}{10^{(1800-1820)/400}+1} = 0.529$

**[1-blok]** 20 ochkolik Elo farqi statistik shovqin — deyarli teng 52.9%. Va Puasson zichlikni tasdiqlaydi: g'alaba ehtimollari 38.9% va 34.7% bilan yaqin, modal yakun 1-1.

**[2-blok]** Türkiye markaziy ijodkorlik orqali AQSH bosim chizig'i orasidan kirishga intiladi. Lekin AQSH energiyali yuqori bosimi bu ijod fazasini buzishga qaratilgan. Biroq ikkala $\lambda$ ham 1.35 dan oshmaydi, shuning uchun farq bitta zarba ichida.

**[3-blok]** Hal qiluvchi o'zgaruvchi — AQSH bosim intensivligining davomiyligi `[MANBA TALAB QILINADI]`. PPDA 60-daqiqadan keyin pasaysa, Türkiye markaziy ijodkorlari ko'proq makon oladi.

**[4-blok]** 26.4% durrang massasi va 0.10 lik $\lambda$ farqi bilan bu yuqori dispersiyali o'yin. Demak uni bitta individual lahza hal qiladi.

---

## 6-O'YIN — Paragvay vs Avstraliya · D guruhi · 07:00

### Jadval 2.1 — Tarkiblar va Jismoniy Holat

| Terma jamoa | Elo (taxminiy baza) | Asosiy yulduz | Holati | Taktik tizim | Kuchli tomoni |
|---|---|---|---|---|---|
| Paragvay | ~1730 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-4-2, qattiq himoya | Tashkillashgan blok + duel |
| Avstraliya | ~1720 | `[MANBA TALAB QILINADI]` | `[MANBA TALAB QILINADI]` | 4-3-3, jismoniy intensivlik | Chidamlilik + qanot |

### Jadval 2.2 — Bashorat Matritsasi (Puasson & Elo)

| Ko'rsatkich | Paragvay | Avstraliya | Durrang |
|---|---|---|---|
| Elo g'alaba ehtimoli $W_e$ | 51.4% | 48.6% | — |
| Puasson g'alaba ehtimoli | 36.4% | 34.1% | 29.5% |
| Kutilgan gollar $\lambda$ | 1.10 | 1.05 | — |
| Eng ehtimoliy hisob | — | — | **1-1 (~13.5%)**, keyin 1-0 (~12.8%) |

$W_e(\text{PAR}) = \frac{1}{10^{(1720-1730)/400}+1} = 0.514$

**[1-blok]** 10 ochkolik Elo farqi deyarli nol — 51.4% bilan eng teng o'yin. Va Puasson buni tasdiqlaydi: g'alaba ehtimollari 36.4% va 34.1%, durrang esa eng yuqori — 29.5%.

**[2-blok]** Paragvay qattiq 4-4-2 bloki orqali maydon markazini yopib, Avstraliyani qanotlarga majburlaydi. Lekin Avstraliyaning jismoniy intensivligi va chidamliligi o'yin oxirida tahdid bo'lib qoladi. Biroq ikkala $\lambda$ ham past — 1.10 va 1.05 — bu kam gol profilini bildiradi.

**[3-blok]** Hal qiluvchi ko'rsatkich — Avstraliyaning oxirgi 15 daqiqadagi yuqori intensivlikdagi sprintlar soni `[MANBA TALAB QILINADI]`. Bu jismoniy chiqish kech bosqichdagi gol ehtimolini oshiradi.

**[4-blok]** 1-1 va 1-0 birgalikda ~26.3% va 29.5% durrang massasi bilan bu to'plamdagi eng yuqori durrang ehtimolli o'yin. Demak model tor farqli yakunni kutadi.

---

## To'plam Muvofiqlik Xulosasi (Jadval 3.3 qisqartirilgan)

| Mezon | Holat |
|---|---|
| Guruhlar SOURCES.md §4 bo'yicha tekshirildi | OK (D: 2, E: 2, F: 2 — tuzatish shart emas) |
| FIFA nomlanishi (Côte d'Ivoire, Curaçao, Türkiye) | OK |
| Taqiqlangan klişelar (STYLE.md §2) | OK — 0 ta |
| Bog'lovchi bilan boshlanuvchi gaplar ~33% | OK (Lekin/Va/Biroq/Demak) |
| Formulalarda LaTeX; hisoblarda raqamlar | OK |
| Puasson/Elo matndan oldin hisoblandi | OK |
| Dinamik tarkib/xG | OGOHLANTIRISH — `[MANBA TALAB QILINADI]` |
| Tikish/tipster kontenti yo'q | OK |

---

*Fayl: analyses/2026-06-26-matchday-def-uz.md · Niche: Football Analytics · Versiya 1.1*
*Tizim asosida: INSTRUCTION.md + SOURCES.md + STRUCTURE.md + STYLE.md*
