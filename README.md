*ParamHunterv2*

`Awal Puasa nih gw udah update script ParamHunter nya tinggal di pake kaga usah nge bac** lagi dah su, oke deh silahkan di baca kalo mau kalo kaga ydh.🥰🗿`

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
```
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip -y
```

2. Clone Repository:
Clone proyek ParamHunterv2 dari GitHub:
```
git clone https://github.com/THEOYS123/ParamHunterv2.git
cd ParamHunterv2
```

3. Install Dependencies:
Install semua dependency yang dibutuhkan dengan perintah:

```
pip3 install -r requirements.txt
```

Catatan: Script akan menginstall modul yang diperlukan secara otomatis jika belum terpasang.

4. Install module terakhir (ini untuk module hasil encrypt saja ya jadi aman lah)

```
pip install Crypto --break-system-packages
```

` udah di install tapi masih error? kalau masih error coba gunakan dengan ini`

```
pip uninstall Crypto -y
pip install pycryptodome --break-system-packages
```
5. Jalankan Script:
Contoh menjalankan script dengan filter kustom:

```
python3 ParamHunterv2.py https://smktjp.sch.id -f .php ?id=
```

---

🔥 On Termux (Android)

1. Install Termux:
Download Termux dari Play Store atau F-Droid.


2. Update Paket & Install Python serta Git:
Buka Termux dan jalankan:
```
pkg update && pkg upgrade -y
pkg install python git -y
```


3. Setup Storage (Opsional):
Jika ingin menyimpan file output ke penyimpanan perangkat, jalankan:

```
termux-setup-storage
```


4. Clone Repository:
Clone proyek ParamHunterv2:

```
git clone https://github.com/THEOYS123/ParamHunterv2.git
cd ParamHunterv2
```

5. Install Dependencies:
Install semua dependency yang diperlukan:

```
pip install -r requirements.txt
```


6. Jalankan Script:
Contoh menjalankan script:

```
python param.py https://smktjp.sch.id -full
```


---

Usage

`Jalankan script dengan perintah berikut:`

```
python ParamHunterv2.py https://smktjp.sch.id -f .php .html ?id= -pr --threads 10
```

Opsi:

-f, --filter  : Filter kustom (misal: .php, ?id=)

-random       : Kumpulkan URL dengan parameter ke ALL_PARAMS

-pr           : Simpan hanya URL yang memiliki query

-full         : Kumpulkan seluruh URL di situs

--threads     : Jumlah thread (default: 10)

-h, --help    : Tampilkan pesan bantuan



---


`ScrinsHoot Termux`


  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <div class="image-container">
    <img src="https://i.top4top.io/p_33478h1vp1.jpg" alt="Displayed Image">
  </div>
</body>
</html>
---

`Scrinshoot Kali linux(nethunter)`


  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <div class="image-container">
    <img src="https://d.top4top.io/p_3347ydk6d1.jpg" alt="Displayed Image">
  </div>
</body>
</html>

---

Contributing

Contributions sangat diterima! Jangan ragu untuk membuat issue atau pull request jika ada saran perbaikan atau fitur baru.
Let's make this tool even more powerful together! 🗿💪


---

License

Proyek ini dilisensikan di bawah MIT License.


---

Connect

Tekegram: https://t.me/REN_XPLOIT

Tiktok: https://www.tiktok.com/@sistem9999

Website: https://theoys123.github.io/RenXploit-web
