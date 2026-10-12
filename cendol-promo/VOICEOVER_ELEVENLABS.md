# Skrip Voice-over ElevenLabs — Cendol Balang Mat (40s)

Copy teks dalam blok "Teks untuk ElevenLabs" terus ke ElevenLabs. Nombor ditulis dalam perkataan
supaya AI sebut dengan betul dalam Bahasa Melayu.

## Teks untuk ElevenLabs

```
Sebalang cendol... dapat dua ratus mangkuk!
<break time="0.6s" />
Ini Cendol Balang Mat. Khas untuk kenduri kahwin.
<break time="0.5s" />
Buat kenduri di Seremban? Kami datang ke majlis anda, set-up gerai, dan siap layan tetamu.
<break time="0.5s" />
Cendol pandan, kacang merah, jagung, santan, dan gula Melaka.
<break time="0.5s" />
Kami cover Senawang, Seremban, Port Dickson, Rembau, dan kawasan sekitar.
<break time="0.5s" />
Sebalang cuma tiga ratus ringgit, dapat lebih kurang dua ratus mangkuk!
<break time="0.5s" />
Tempah sekarang. WhatsApp: kosong satu satu, satu kosong satu tujuh, satu sembilan sembilan tiga.
```

## Susunan masa (ikut video)

| Masa video | Ayat |
|---|---|
| 0.0–3.2s | Sebalang cendol... dapat dua ratus mangkuk! |
| 3.2–6.4s | Ini Cendol Balang Mat. Khas untuk kenduri kahwin. |
| 6.4–16.0s | Buat kenduri di Seremban? Kami datang ke majlis anda, set-up gerai, dan siap layan tetamu. |
| 16.0–21.0s | Cendol pandan, kacang merah, jagung, santan, dan gula Melaka. |
| 21.0–27.0s | Kami cover Senawang, Seremban, Port Dickson, Rembau, dan kawasan sekitar. |
| 27.0–33.5s | Sebalang cuma tiga ratus ringgit, dapat lebih kurang dua ratus mangkuk! |
| 33.5–40.0s | Tempah sekarang. WhatsApp: 011-1017 1993 |

Tak perlu tepat sesaat. Saya akan potong dan susun setiap ayat ikut scene masa mix.

## Setting ElevenLabs yang dicadangkan

- **Model:** Eleven Multilingual v2 (sokong Bahasa Melayu dan tag `<break>`). Kalau guna Eleven v3, buang tag `<break>` dan guna `...` sahaja.
- **Suara:** cari "Malay" atau "Malaysian" dalam Voice Library. Pilih suara lelaki atau perempuan yang mesra dan bertenaga, gaya iklan, jangan suara berita.
- **Stability:** 40–50% · **Similarity:** 75% · **Style:** 15–25% · **Speed:** 1.05–1.1
- **Export:** MP3 44.1 kHz (atau WAV).
- Kalau ada perkataan tersasul, cuba ejaan lain, contohnya "set-ap gerai" atau "Port Dikson".

## Lepas generate

Hantar fail audio (upload ke folder Google Drive tadi atau attach dalam chat). Saya akan:
1. Potong dan susun setiap ayat ikut scene.
2. Perlahankan bunyi ambien dan SFX bila suara bercakap (ducking).
3. Render semula versi final + versi WhatsApp.
