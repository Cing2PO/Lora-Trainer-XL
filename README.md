# 🚀 Pelatihan LoRA XL dan Auto Tagger
Repositori dengan notebook untuk melatih LoRA XL dan memproses dataset gambar dengan pemberian label otomatis (*auto-tagging*) menggunakan model Waifu Diffusion.

🏠 **Proyek Asli:** [![GitHub](https://img.shields.io/badge/GitHub-hollowstrawberry-blue?logo=github)](https://github.com/hollowstrawberry/kohya-colab)
🏠 **Modifikasi Oleh WhiteZ:** [![GitHub](https://img.shields.io/badge/GitHub-gwhitez-blue?logo=github)](https://github.com/gwhitez/Lora-Trainer-XL)

## ✨ Fitur Utama

Repositori ini berisi kumpulan notebook Google Colab yang dikhususkan untuk:
- **Pelatihan LoRA XL** dengan implementasi terbaru.
- **Pemrosesan dataset** dengan pemberian label otomatis menggunakan model Waifu Diffusion.
- Kompatibilitas dengan berbagai versi model XL (XL base, Animagine, Finetuning, Pony, Illustrious, NoobAI, Vpred, dll.).
- Terhubung ke Google Drive secara default.
- Penggunaan mudah dengan konfigurasi bawaan yang optimal untuk sebagian besar kasus.
- **Auto off**: Mematikan lingkungan secara otomatis setelah pelatihan selesai untuk menghindari pemborosan kuota GPU. Bersantailah dan nikmati kopi ☕ selagi LoRA Anda dilatih.

### Pelatihan LoRA XL
> [!WARNING]
> Kedua notebook memiliki fitur yang sama, namun hasil akhirnya mungkin berbeda tergantung pada notebook yang digunakan dan konfigurasinya.

* **WhiteZ LoRA Trainer SDXL** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/WhiteZ_Lora_Trainer_SDXL.ipynb)
* **WhiteZ LoRA Trainer SDXL v2** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/WhiteZ_Lora_Trainer_SDXL_v2.ipynb)
    * Skrip pelatihan terbaru & manajemen sumber daya Colab yang lebih efisien.
    * Dukungan untuk pelatihan Vpred & instalasi cepat (⚡).
    * Pelatihan dengan model `.safetensors` atau `.ckpt` di Colab gratis menggunakan full FP16.
    * Pelatihan dengan optimisator Prodigy dan CAME+REX (sangat baik untuk dataset kecil!).
    * Menggunakan `venv` untuk menghindari error akibat pembaruan sistem Google Colab.

### Auto-Tagging Dataset
* **Dataset_Maker_By_WhiteZ.ipynb** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/Dataset_Maker_By_WhiteZ.ipynb)
    * Pelabelan dengan model Waifu Diffusion V3.
    * Instalasi super cepat (~1 menit).
    * Berjalan di GPU maupun CPU (cocok jika kuota GPU habis).
    * Fitur editor label, visualisator, dan pembuatan caption BLIP.

* **Waifu_Diffusion_V3_Dataset_Maker.ipynb** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/Waifu_Diffusion_V3_Dataser_Maker.ipynb)
    * Pelabelan dengan model WD V3 Large.
    * Model khusus untuk konten Furry (Z3d) dan Danbooru (ML).

## 🛠 Persyaratan
- Akun Google Colab.
- Akses GPU (T4 untuk gratis, A100/L4 untuk Pro).
- Google Drive dengan minimal 1 GB ruang kosong.

# 🚀 LoRA XL Training and Auto Tagger
Repository featuring notebooks to train LoRA XL and process image datasets with auto-tagging using Waifu Diffusion models.

🏠 **Original Project:** [![GitHub](https://img.shields.io/badge/GitHub-hollowstrawberry-blue?logo=github)](https://github.com/hollowstrawberry/kohya-colab)
🏠 **Modified By WhiteZ:** [![GitHub](https://img.shields.io/badge/GitHub-gwhitez-blue?logo=github)](https://github.com/gwhitez/Lora-Trainer-XL)

## ✨ Main Features

This repository contains a suite of Google Colab notebooks specialized for:
- **LoRA XL Training** with updated implementations.
- **Dataset Processing** with auto-tagging via Waifu Diffusion models.
- Compatibility with various XL versions (XL base, Animagine, Pony, Illustrious, NoobAI, Vpred, etc.).
- Google Drive integration by default.
- User-friendly "out-of-the-box" configurations.
- **Auto off**: Automatically shuts down the environment after training to save GPU hours. Relax and grab a coffee ☕ while your LoRA trains.

### LoRA XL Training
> [!WARNING]
> Both notebooks share the same features, but final results may vary depending on the specific version and configuration used.

* **WhiteZ LoRA Trainer SDXL** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/WhiteZ_Lora_Trainer_SDXL.ipynb)
* **WhiteZ LoRA Trainer SDXL v2** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/WhiteZ_Lora_Trainer_SDXL_v2.ipynb)
    * Latest training scripts & improved resource management.
    * Vpred training support & ⚡ Fast installation.
    * Supports `.safetensors` or `.ckpt` on free Colab using full FP16.
    * Prodigy and CAME+REX Optimizer support (excellent for small datasets!).
    * Uses `venv` to prevent environment breakage from Colab system updates.

### Dataset Auto-Tagging
* **Dataset_Maker_By_WhiteZ.ipynb** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/Dataset_Maker_By_WhiteZ.ipynb)
    * Tagging with Waifu Diffusion V3 models.
    * ⚡ Fast setup (~1 minute).
    * GPU/CPU compatible (useful if you run out of GPU credits).
    * Includes tag editor, visualizer, and BLIP captioning.

* **Waifu_Diffusion_V3_Dataset_Maker.ipynb** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gwhitez/Lora-Trainer-XL/blob/main/Waifu_Diffusion_V3_Dataser_Maker.ipynb)
    * Utilizes WD V3 and Large models.
    * Specialized models for Furry (Z3d) and Danbooru (ML) content.

## 🛠 Requirements
- Google Colab account.
- GPU Access (T4 for Free tier, A100/L4 for Pro).
- Google Drive with at least 1 GB of free space.
