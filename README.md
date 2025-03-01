Berikut adalah teks README.md yang keren dan jelas untuk proyek ParamHunterv2:


---

ParamHunterv2

Next-level Deep Crawling & Advanced WAF Bypass Tool 🚀🔥


(Opsional: Ganti dengan banner project kamu jika ada)


---

Overview

ParamHunterv2 adalah alat deep crawling yang dirancang untuk mencari parameter pada setiap sudut website – dari halaman utama hingga ke akar-akar sistem! Dilengkapi dengan UI keren berbasis Rich dan teknik bypass WAF yang canggih, script ini memungkinkan kamu untuk:

Melakukan scanning mendalam dengan multi-threading 🧵

Mengumpulkan URL berdasarkan filter kustom dari input user 🎯

Mengaktifkan mode bypass WAF dengan header dinamis yang jenius 🛡️

Menyimpan hasil scanning ke file dengan format rapi 📂



---

Features

Deep Crawling: Menyusuri website secara menyeluruh hingga ke setiap sudutnya.

Custom Filtering: Filter parameter bebas sesuai request user (misal: .php, ?id=) ✨

Advanced WAF Bypass: Teknik bypass yang powerful dengan payload header dinamis dan IP acak 🤖

Modern UI: Tampilan interaktif dan stylish menggunakan modul Rich 🎨

Graceful Exit: Handling Ctrl+C yang memastikan semua thread berhenti dengan baik dan hasil disimpan rapi 🚦



---

Installation on Termux & Kali Linux 🗿🗿🗿

ParamHunterv2 dirancang agar bisa dijalankan di berbagai platform, termasuk Kali Linux dan Termux (Android). Berikut adalah langkah-langkah instalasi untuk masing-masing platform:

🔥 On Kali Linux

1. Update Sistem & Install Python 3 dan pip:
Pastikan sistem kamu dalam keadaan up-to-date dan sudah terpasang Python 3 serta pip.

sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip -y


2. Clone Repository:
Clone proyek ParamHunterv2 dari GitHub:

git clone https://github.com/THEOYS123/ParamHunterv2.git
cd ParamHunterv2


3. Install Dependencies:
Install semua dependency yang dibutuhkan dengan perintah:

pip3 install -r requirements.txt

Catatan: Script akan menginstall modul yang diperlukan secara otomatis jika belum terpasang.


4. Jalankan Script:
Contoh menjalankan script dengan filter kustom:

python3 ParamHunterv2.py https://targetwebsite.com -f .php ?id=




---

🔥 On Termux (Android)

1. Install Termux:
Download Termux dari Play Store atau F-Droid.


2. Update Paket & Install Python serta Git:
Buka Termux dan jalankan:

pkg update && pkg upgrade -y
```pkg install python git -y```


3. Setup Storage (Opsional):
Jika ingin menyimpan file output ke penyimpanan perangkat, jalankan:

```termux-setup-storage```


4. Clone Repository:
Clone proyek ParamHunterv2:

```
git clone https://github.com/THEOYS123/ParamHunterv2.git
cd ParamHunterv2
```

5. Install Dependencies:
Install semua dependency yang diperlukan:

```pip install -r requirements.txt```


6. Jalankan Script:
Contoh menjalankan script:

```python ParamHunterv2.py https://smktjp.sch.id -full```




---

Usage

`Jalankan script dengan perintah berikut:`

python ParamHunterv2.py https://example.com](https://smktjp.sch.id -f .php .html ?id= -pr --threads 10

Opsi:

-f, --filter  : Filter kustom (misal: .php, ?id=)

-random       : Kumpulkan URL dengan parameter ke ALL_PARAMS

-pr           : Simpan hanya URL yang memiliki query

-full         : Kumpulkan seluruh URL di situs

--threads     : Jumlah thread (default: 10)

-h, --help    : Tampilkan pesan bantuan



---

Demo


`Scrinshoot`

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Display Image</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #f0f0f0;
      min-height: 100vh;
      margin: 0;
    }
    .image-container {
      border: 5px solid #3498db;
      padding: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
    }
  </style>
</head>
<body>
  <div class="image-container">
    <img src="https://f.top4top.io/p_3329uuu3s1.jpg" alt="Displayed Image">
  </div>
</body>
</html>

---

Contributing

Contributions sangat diterima! Jangan ragu untuk membuat issue atau pull request jika ada saran perbaikan atau fitur baru.
Let's make this tool even more powerful together! 💪


---

License

Proyek ini dilisensikan di bawah MIT License.


---

Connect

Tekegram: https://t.me/REN_XPLOIT

Tiktok: https://www.tiktok.com/@sistem9999

Website: https://theoys123.github.io/RenXploit-web
