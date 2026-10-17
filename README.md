# slop detector

Deteksi AI slop dalam teks. Paste tulisan, dapat skor + saran perbaikan.

🔗 **Live:** https://slop.ai.id

## Yang dideteksi

- 🗣️ **Frase khas AI** — "delve", "game-changer", "in today's fast-paced world", "di era digital yang serba cepat", "tak dapat dipungkiri", dll. (40+ pattern Indonesia + Inggris)
- 😂 **Emoji berlebihan** — AI demen naro emoji di setiap poin
- ❗ **Tanda seru berlebihan**
- 📋 **Struktur list berlebihan** — >50% baris adalah list
- 🔁 **Paragraf repetitif** — pola pembuka yang sama berulang
- 🔢 **Enumerasi kaku** — Firstly/Secondly/Thirdly

## Skor

0-100 (semakin tinggi = semakin slop):
- 70+: SLOP BERAT 🚨
- 40-69: Agak slop ⚠️
- 15-39: Sedikit bau AI 👀
- 0-14: Bersih ✨

## Cara kerja

100% client-side (HTML + JS + CSS, tanpa framework, tanpa backend). Semua analisis jalan di browser — teks tidak dikirim ke mana-mana.

## Keterbatasan

Deteksi berbasis pattern, bukan AI detector sempurna. Teks natural yang rapi bisa lolos; slop yang obvious pasti ketangkep.

---

Dibuat oleh [chospace](https://chospace.github.io) · slop.ai.id
