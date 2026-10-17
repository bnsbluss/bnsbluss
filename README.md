# 👋 About Me

> **Independent Developer • Game Tools Builder • Point Blank Server Administrator • Computer & Laptop Enthusiast**

Saya adalah developer yang banyak mengerjakan **tools, server, modding, reverse engineering format file game, dan otomasi**—terutama di ekosistem **Point Blank**. Saya lebih suka membangun tool yang benar-benar menyelesaikan masalah daripada sekadar membuat prototype.

Saya tertarik membongkar cara kerja sebuah sistem dari level data/file hingga menjadi tool yang mudah digunakan. Dari format binary seperti `.I3S`, `.I3CHR`, `.i3Pack`, `.RSC`, dan `.i3AnimPack`, sampai server game, web panel, database, pembayaran, dan watchdog Windows.

Saya mengerjakan project-project ini secara mandiri, dengan sebagian proses pengembangan dibantu oleh **AI Claude**—terutama saat menghadapi kode, struktur file, algoritma, debugging, atau masalah teknis yang sangat sulit. AI saya gunakan sebagai partner untuk analisis, eksplorasi solusi, dan memecahkan masalah; proses pengujian, validasi, eksperimen, dan keputusan akhir tetap saya lakukan sendiri.

### 🧠 Fokus & Keahlian

- 🎮 **Point Blank / Game Modding & Development Tools**
- 🔬 **Binary File Format Analysis**
- 🧩 **I3 Engine / `.I3S` / `.I3CHR` / `.i3Pack` / `.RSC` / Animation**
- 🐍 **Python Tooling & CLI**
- 💻 **Windows / PowerShell / C#**
- 🌐 **PHP Native + PostgreSQL**
- 🎨 **3D Model, Skin, Texture & Game Asset Pipeline**
- 💻 **Teknik Komputer & Laptop**
- 🛠️ **Membangun utility dari kebutuhan nyata**

---

# 🚀 Project Showcase

Berikut beberapa project dan sistem yang saya kerjakan atau kembangkan. Sebagian merupakan project publik, sebagian lainnya adalah project personal/private yang menjadi bagian dari eksperimen dan pengembangan sistem Point Blank.

| Project | Fokus | Deskripsi |
|---|---|---|
| 🎮 **I3 Engine Editor V3** | Game Tools / Reverse Engineering | Suite tools untuk membaca, mengedit, mengonversi, dan membangun berbagai format data Point Blank berbasis I3 Engine. Project ini merupakan fokus utama repository ini. |
| 🧰 **I3 Engine Tools V3** | Tool Suite | Launcher terpadu yang mengumpulkan berbagai editor dan converter I3 Engine dalam satu aplikasi dengan pencarian, kategori, serta tema dark/light. |
| 🧍 **I3 Character Pipeline** | Character / Skeleton | Konversi skin Avatar V2 agar dapat menggunakan skeleton, ragdoll, weapon point, dan helmet point karakter V1 tanpa kehilangan mesh dan tekstur aslinya. |
| 🔫 **I3 Weapon Pipeline** | Weapon / Animation | Eksperimen dan tools untuk membuat, memperbaiki, mengonversi, serta mengatur state, animasi, suara, dan resource senjata Point Blank. |
| 🗺️ **I3 Map Tools** | Map Editing | Editor `i3Path`, `i3INS`, collision, serta viewer untuk membantu mengedit jalur AI, objek map, collision, dan model dalam scene Point Blank. |
| 📦 **I3Pack / RSC Tools** | Resource / Archive | Editor dan library untuk membaca, mengubah, mengekstrak, memasukkan kembali, dan memeriksa resource `.i3Pack` serta `.RSC`. |
| 🎞️ **I3 Animation Tools** | Animation | Editor `.i3AnimPack` dan workflow animasi untuk membaca track, keyframe, durasi, serta memindahkan gerakan antar paket animasi. |
| 🖥️ **Point Blank Server Ecosystem** | Game Server | Pengembangan dan administrasi ekosistem private server Point Blank, termasuk server, database, web account system, voucher, inbox, dan berbagai utility pendukung. |
| 🌐 **Web System** | PHP / PostgreSQL | Sistem web pendukung server dengan account, inbox, redeem voucher, package, dan integrasi pembayaran untuk distribusi item/game package. |
| 🎨 **Point Blank Asset / Texture Workflow** | 3D / Texture | Workflow pengolahan model, skin, texture, bone, LOD, material, dan asset game untuk kebutuhan modding serta pengembangan content. |

> **Catatan:** Tidak semua project di atas merupakan repository publik. Sebagian adalah project pribadi, eksperimen, atau sistem yang digunakan dalam pengembangan server dan tooling.

---

# 🧭 Cara Saya Mengerjakan Project

Saya biasanya memulai dari **masalah nyata**, kemudian membongkar struktur sistemnya sampai ditemukan cara kerja yang dapat direproduksi.

**Problem → Analisis → Eksperimen → Tool → Validasi → Otomasi**

Contohnya pada I3 Engine Editor V3:

```text
Game File
   ↓
Analisis struktur binary
   ↓
Identifikasi object / node / bone / material
   ↓
Reverse engineering format
   ↓
Python parser / writer
   ↓
Editor GUI
   ↓
Verifikasi otomatis
   ↓
Testing di i3Viewer2 / Client
   ↓
Tool siap digunakan
```

Saya juga sangat memperhatikan **data integrity**. Banyak tool di project ini tidak sekadar "bisa membuka file", tetapi berusaha menjaga struktur file asli, melakukan read-back verification setelah penyimpanan, dan menghindari perubahan yang tidak diperlukan.

---

# 🏗️ Teknologi yang Sering Saya Gunakan

```text
Languages
├── Python
├── PHP
├── C#
├── PowerShell
└── SQL

Game / 3D
├── Point Blank / I3 Engine
├── I3S
├── I3CHR
├── I3AnimPack
├── I3Pack
├── RSC
├── OBJ
└── Texture / LOD / Skeleton / Animation

Backend
├── PostgreSQL
├── PHP Native
├── Web Server
├── Payment / Webhook
└── Server Automation

Windows
├── PowerShell
├── C#
├── Executable tooling
├── Process monitoring
└── Crash / restart automation
```

---

# 🤖 AI-Assisted Development

Beberapa bagian dari project ini dikembangkan dengan bantuan **AI Claude** sebagai technical assistant. Bantuan tersebut terutama digunakan ketika menemukan masalah yang kompleks, kode yang sulit dipahami, reverse engineering yang membutuhkan banyak eksperimen, debugging yang panjang, atau ketika diperlukan pendekatan alternatif untuk memecahkan suatu masalah.

AI membantu dalam hal seperti:

- 🔎 Menganalisis kode dan struktur data yang kompleks
- 🧩 Mencari kemungkinan solusi untuk masalah yang sulit
- 🐛 Membantu debugging dan menemukan sumber error
- 🧠 Mengeksplorasi algoritma dan pendekatan teknis
- 🧪 Membantu merancang eksperimen dan validasi
- ⚙️ Mengembangkan atau menyempurnakan utility dan tooling

Namun, **AI bukan pengganti proses pengembangan**. Setiap solusi tetap saya pelajari, uji, verifikasi, dan sesuaikan dengan perilaku sebenarnya dari file, engine, client, server, atau sistem yang sedang dikerjakan.

> **AI membantu mempercepat pemecahan masalah. Saya tetap bertanggung jawab atas implementasi, pengujian, dan hasil akhirnya.**


--- The End #
