# Cendol Balang Mat — Promo 40s (Kenduri Kahwin)

Format: 1080×1920 (Reels / TikTok / WhatsApp Status), 30fps, 40.0s.
Status: **PREVIEW sahaja** — `preview/cendol-balang-mat-PREVIEW-540p.mp4` (draft 540p, ada watermark). Final belum di-render.

## 1. Transcript / shot log footage asal

Semua 5 klip di-transcribe dengan Whisper (large-v3-turbo, bahasa Melayu). **Tiada dialog atau voice-over** —
Whisper hanya mengeluarkan hallucination biasa ("Terima kasih kerana menonton") yang menandakan audio
cuma bunyi ambien (bunyi tuang, orang ramai di venue). Jadi "transcript" di bawah ialah log visual + audio
yang digunakan untuk tentukan titik potong, animation dan SFX.

| Klip asal | Masa | Apa berlaku | Keputusan |
|---|---|---|---|
| VID_104627 (16.5s) | 0.0–2.3 | Close-up topping: kacang merah, jagung atas cendol | Buang (statik, tunggu tuang) |
| | 2.3–4.2 | **Santan dituang — "crash" warna putih atas topping** | **HOOK** (slow-mo 0.75×) |
| | 4.2–8.0 | Santan terus dituang, berulang | Guna 8.2–11.2 untuk scene harga |
| | 8.0–16.5 | Balang penuh atas meja, kamera turun perlahan | Guna 12.2–14.2 (balang penuh) — selebihnya berulang, buang |
| VID_104724 (8.7s) | 0.0–1.3 | Balang sebelum gula melaka | Buang |
| | 1.3–4.5 | **Gula melaka dituang** | Brand reveal |
| | 4.5–8.7 | Titisan terakhir, berulang | Buang |
| VID_122844 (7.0s) | 0.2–3.2 | Gula melaka dituang, sudut lain | Scene bahan-bahan |
| | 3.2–7.0 | Berulang | Buang |
| VID_104703 (1.3s) | 0.0–1.3 | Balang wide | Tak guna (terlalu pendek) |
| VID_102649 (39.3s) | 0.0–3.0 | Papan tanda nama pengantin | **Tak guna** — nama peribadi pelanggan |
| | 3.3–5.3 | Papan "Rumah Abang Jamil Seremban" + basikal | Scene venue |
| | 5.3–19.5 | Jalan masuk / laluan — panjang, orang lalu, berulang | Buang (jeda & ulang) |
| | 19.6–21.2 | Gerbang kayu ukir | Scene venue |
| | 21.2–32.0 | Buffet katering lain, orang beratur | Buang (bukan produk kita) |
| | 32.2–35.2 | Gerai Cendol Balang Mat didedahkan | Scene gerai |
| | 36.3–39.3 | Papan "CENDOL MAT 01110171993" close-up | Scene CTA (bukti sebenar) |

Gambar yang digunakan: `mat-stall-2` (Mat di gerai), `stall-wide`, `cendol-top`, `balang-side`, `mat-stall-1`.

Hasil: ~73s footage + 14 gambar → 40s, semua jeda kosong dan shot berulang dibuang.

## 2. Timeline edit

| Masa | Visual | Teks / motion graphics | SFX |
|---|---|---|---|
| 0.0–3.2 | Santan crash (slow-mo) | **HOOK**: "SEBALANG CENDOL" slam (0.1s) → "= 200 MANGKUK" (0.85s, sync dengan santan kena topping + flash) → sticker "RM300 JE!" (1.6s) | Bass impact, pop ×2 |
| 3.2–6.4 | Gula melaka dituang | Kad brand "Cendol Balang Mat — Katering cendol kenduri" | Whoosh, sparkle |
| 6.4–10.0 | Venue Rumah Abang Jamil + gerbang | "Buat kenduri di Seremban?" | Whoosh, pop |
| 10.0–13.0 | Gerai didedahkan | "Kami datang set-up gerai terus di majlis" | Whoosh, pop |
| 13.0–16.0 | Mat di gerai (Ken Burns) | "Siap layan tetamu anda" | Whoosh |
| 16.0–21.0 | Gula melaka + balang penuh | "Dalam sebalang": cendol pandan, kacang merah, jagung, santan, gula Melaka (chip pop satu-satu) | Pop ×5 |
| 21.0–27.0 | Gerai + cendol (dim) | "Kawasan servis": Senawang, Seremban, Port Dickson, Rembau, & kawasan sekitar (pin jatuh) | Click ×4, pop |
| 27.0–33.5 | Balang sisi → santan tuang | Kad harga: RM0→**RM300** count-up, "±200 mangkuk / pax" count-up, tag "≈ RM1.50 semangkuk" | Whoosh, impact + flash, ping, pop |
| 33.5–36.5 | Papan tanda sebenar "CENDOL MAT" | "Tempah sekarang!" | Whoosh |
| 36.5–40.0 | Mat di gerai (dim) | Kad WhatsApp **011-1017 1993** (pulse) + "Tempah awal tarikh kenduri anda" | Notification, click |

Pill jenama "CENDOL BALANG MAT" kekal di atas kiri 6.4–33.5s. Semua teks dalam zon selamat Reels/TikTok
(jauh dari 400px bawah & tepi kanan).

## 3. Audio

**Voice-over (ElevenLabs, suara "Ashraf"):** `assets/audio/vo-ashraf.wav` (dinormalkan ke −16 LUFS), dipecah ikut jeda kepada 7 segmen:

| Masa video | VO |
|---|---|
| 0.0–3.25 | Sebalang cendol... dapat dua ratus mangkuk! |
| 3.3–6.9 | Ini Cendol Balang Mat. Khas untuk kenduri kahwin. |
| 7.0–13.0 | Buat kenduri di Seremban? Kami datang ke majlis anda, set-up gerai, dan siap layan tetamu. |
| 13.0–16.2 | (tiada VO — shot Mat, nafas) |
| 16.2–20.8 | Cendol pandan, kacang merah, jagung, santan, dan gula Melaka. |
| 21.3–26.2 | Kami cover Senawang, Seremban, Port Dickson, Rembau, dan kawasan sekitar. |
| 27.3–31.7 | Sebalang cuma tiga ratus ringgit, dapat lebih kurang dua ratus mangkuk! |
| 33.6–39.9 | Tempah sekarang. WhatsApp 011-1017 1993 (kad WhatsApp keluar 34.85s, serentak nombor disebut) |

Bunyi tuang diturunkan (0.15–0.3) dan SFX diturunkan ~35% supaya suara jelas. Mix akhir: −14.3 LUFS, peak −1.5 dBFS.


- Bunyi asal tuang santan/gula melaka dikekalkan perlahan (ASMR), klip venue di-mute (bising orang).
- SFX dari library HyperFrames (bundled, bebas guna — lihat `assets/sfx/CREDITS.md`).
- Loudness preview: −16.6 LUFS (sesuai untuk social).
- Masih **tiada BGM** — cadangan: tambah lagu trending terus dalam TikTok/IG semasa upload, atau beri fail lagu dan saya mix + duck.

## 4. Gaya

- Warna: pandan (#1D6B34), santan (#FBF3DC), gula Melaka (#4A240C), kuning batik (#F2C230) — diambil dari footage.
- Font: Archivo Black (tajuk), Space Mono (label/harga).

## 5. Cara preview / render

```bash
cd cendol-promo
npx hyperframes preview          # Studio (edit teks/timing dalam browser)
npx hyperframes check            # lint + layout + contrast
npx hyperframes render -q high -o renders/cendol-balang-mat-final.mp4   # FINAL — selepas approve
```
