# 🔥 Instagram Roasting Skill

**3 AI personas yang menilai estetika akun Instagram kamu: dari roasting pedas sampai rencana perbaikan yang konkret.**

Kamu kirim screenshot akun Instagram-mu sendiri, lalu tiga karakter AI ini beraksi:

| Karakter | Peran | Gaya |
|---|---|---|
| 🔥 **Shareen** | Si Roaster: menyorot semua yang berantakan | Sarkas, Gen Z, pedas tapi sayang |
| 💛 **Nolan** | Si Hype Man: mencari kekuatan akunmu | Hangat, tulus, suportif |
| ⚖️ **Dest** | Si Penengah: menyimpulkan plus-minus dan memberi arahan | Tenang, adil, solutif |

Cocok untuk:
- Kamu yang ingin **merapikan estetika** akun Instagram pribadi.
- **Influencer / kreator** yang bingung menentukan *vibes* dan personal branding akunnya.
- Siapa pun yang penasaran akunnya dinilai AI (dan kuat mental dibilang "ini sih template banget").

> ⚠️ Skill ini dirancang untuk menilai **akun milik sendiri**, bukan untuk menyerang atau mempermalukan orang lain.

---

## ✨ Fitur

- Roasting yang **spesifik**, menunjuk bukti dari screenshot, bukan komentar generik.
- Pujian yang **jujur**, bukan "bagus semua!".
- Kesimpulan berisi **plus, minus, skor, dan 3 langkah perbaikan** yang bisa langsung dikerjakan.
- **Portabel**: satu prompt inti yang bisa dipakai di Claude, ChatGPT, Gemini, atau AI lain.
- Ada **batasan konten**: tidak menyinggung tubuh, wajah, ras, agama, dan hal sensitif lainnya.

---

## 📥 Input yang Dibutuhkan

AI **tidak bisa membuka Instagram** langsung dari link atau username (Instagram menutup kontennya di balik login). Jadi kirim:

1. 📱 **Screenshot halaman profil**: foto profil, bio, highlight.
2. 🖼️ **Screenshot grid feed**: 9-12 postingan terakhir.
3. *(Opsional)* 2-3 caption andalanmu.
4. *(Opsional)* Tujuan akun, misalnya "mau vibes minimalis" atau "konten kuliner, bingung branding".

Kalau hanya mengirim username atau link, AI akan meminta screenshot dulu supaya tidak mengarang.

---

## 🚀 Cara Pakai

Isi prompt ada di [`core-prompt.md`](./core-prompt.md). Salin bagian di bawah garis `---` pada file itu, lalu pakai sesuai AI yang kamu mau.

### Claude

**Cara cepat:**
1. Buka percakapan baru di Claude.
2. Tempel isi `core-prompt.md` sebagai pesan pertama.
3. Kirim screenshot profil dan feed-mu.

**Cara rapi (disarankan):**
1. Buat sebuah **Project** di Claude.
2. Tempel isi `core-prompt.md` ke **Project instructions**.
3. Setiap mau dinilai, buka chat baru di Project itu dan kirim screenshot.

### ChatGPT

**Cara cepat:** tempel isi `core-prompt.md` di chat baru, lalu kirim screenshot.

**Cara rapi:** buat **Custom GPT** (menu *Explore GPTs → Create*), lalu tempel isi `core-prompt.md` ke kolom **Instructions**. Simpan, dan GPT itu siap dipakai kapan saja.

### Gemini

**Cara cepat:** tempel isi `core-prompt.md` di chat baru, lalu kirim screenshot.

**Cara rapi:** buat **Gem** (menu *Gems → New Gem*), tempel isi `core-prompt.md` ke kolom instruksi, lalu simpan.

### AI lain

Selama AI-nya bisa membaca gambar, tempel `core-prompt.md` sebagai instruksi atau pesan pertama, lalu kirim screenshot. Kalau AI-nya tidak bisa membaca gambar, kirim deskripsi teks: isi bio, daftar warna dominan, dan ringkasan tiap postingan.

---

## 🎬 Contoh Output

> Contoh di bawah memakai akun **fiktif** (`@kopi.sore.id`, akun kopi lokal) hanya untuk ilustrasi.

```
🔥 SHAREEN (Roasting)
1. Tiga foto latte art berturut-turut, tiga filter berbeda. Kamu lagi cari
   jati diri atau lagi coba-coba preset gratisan?
2. Bio-nya "Ngopi dulu, hidup nanti". Jujur, itu bio punya 40 ribu akun lain.
3. Grid-nya kayak galeri HP: kopi, kucing, screenshot menu, kopi lagi.
   Mau jadi cafe atau jadi diary?
4. Foto profilmu logo yang burem. Hal pertama yang dilihat orang itu, lho.

💛 NOLAN (Sisi Terang)
1. Foto kedua (cahaya jendela sore) itu cakep banget. Hangat, natural, dan
   langsung bikin pengen mampir.
2. Warna cokelat-krem yang muncul di beberapa postingan itu sebenarnya sudah
   jadi identitas, tinggal dipertahankan.
3. Caption "ceritanya kopi hari ini" itu punya karakter. Orang suka akun yang
   terasa manusiawi.
4. Shareen terlalu keras soal bio. Konsepnya santai, tinggal dipertajam.

⚖️ DEST (Kesimpulan)
Plus: cahaya alami yang bagus, palet cokelat-krem yang potensial, nada
caption yang ramah.
Minus: filter tidak konsisten, kontennya campur aduk, bio dan foto profil
belum mewakili brand.
Vibes saat ini: "kafe hangat yang belum punya arah visual."
Skor: Konsistensi 4/10 · Kualitas visual 6/10 · Personal branding 4/10

Rencana perbaikan:
1. Kunci satu preset warna hangat (cokelat-krem) dan pakai di semua foto.
2. Batasi tema feed jadi 3: produk, suasana kafe, di balik layar. Hapus
   screenshot menu dari grid (pindahkan ke highlight).
3. Ganti foto profil dengan logo yang tajam dan tulis bio yang menyebut
   lokasi plus keunikan, misalnya "Kopi susu gula aren | Jakarta Selatan".

Hal yang tidak bisa kunilai: engagement dan performa postingan.
```

---

## 🛡️ Batasan & Privasi

- Kritik hanya soal **pilihan visual dan branding**, bukan tubuh atau wajah.
- Tidak menyinggung ras, agama, orientasi, disabilitas, kondisi kesehatan, atau status ekonomi.
- Orang lain yang muncul di foto (teman, keluarga, pasangan) **tidak dikomentari**.
- Akun anak di bawah umur **tidak di-roast**, hanya diberi masukan yang lembut.
- Screenshot kamu diproses oleh AI yang kamu pakai. Perhatikan kebijakan privasi masing-masing layanan sebelum mengirim, dan **jangan kirim informasi pribadi** (nomor HP, alamat, dll).

---

## 🗂️ Struktur Repo

```
instagram-roasting-skill/
├── core-prompt.md   # prompt inti (bisa dipakai di AI apa pun)
├── README.md        # dokumentasi ini
└── LICENSE          # MIT
```

**Rencana ke depan:**
- [ ] `SKILL.md` khusus Claude
- [ ] Panduan Custom GPT dan Gemini Gem yang lebih detail
- [ ] Mode "roasting level" (lembut / sedang / pedas)
- [ ] Contoh output tambahan untuk niche lain (fashion, travel, kuliner, personal brand)

---

## 🤝 Kontribusi

Ide dan perbaikan sangat diterima! Buka **Issue** untuk saran atau laporan masalah, atau kirim **Pull Request** kalau mau memperbaiki prompt-nya.

---

## 📄 Lisensi

Dirilis di bawah lisensi [MIT](./LICENSE).
