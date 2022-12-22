# JOB-1
DASAR PEMROGRAMAN ESP32 UNTUK PEMROSESAN DATA INPUT/OUTPUT ANALOG DAN DIGITAL


ALAT & BAHAN
1) ESP32
2) Breadboard
3) Kabel jumper
4) Potensiometer 10k Ohm (1)
5) Sensor Capacitive Soil Moisture
6) LED (5) dan Push Button (3)
7) Multimeter
8) Resistor 330,1K, 10K Ohm (@ 3)


A. GPIO
1. Pada program ini diharapkan bisa mengndalikan satu LED dengan push button yang mana led bisa nyala apabila push button ditekan dan akan mati jika dilepaskan


https://user-images.githubusercontent.com/121172074/209062784-9f96decf-ed87-42d3-bd2c-4867b52705eb.mp4


2. Selanjtunya pada program GPIO yang kedua ini menambahkan 1 LED dengan estimasi waktu 5 detik yang mana LED akan mati selama 5 setik dan nyala selama 5 detik, jadi apabila tetap ditekan push buttonnya namun waktu sudah habis LED akan tetap mati


https://user-images.githubusercontent.com/121172074/209063304-6791ca81-854a-452d-a14d-6ad36a9a8094.mp4


3. Pada percobaan GPIO yang ketiga ini menggunakan 3 LED yang dikendalikan oleh satu push button, Program ini dijalankan bisa membuat saat push button ditekan maka lampu akan nyala secara berurutan 


https://user-images.githubusercontent.com/121172074/209064986-9cb8c0b3-2421-48bf-b092-3b5cb46f4042.mp4


B. PWM
1. Percobaan ini menggunakan metode Pulse Width Modulation yaitu pendekatan pelebaran pulsa dengan menghasilkan nilai tegangan analog dengan maksimal tegangan HIGH 3,3 V dan LOW 0 V. Pin pada PWM ini mengeluarkan sinyal digital yang dihasilkan dari dutty cycle (perbandingan HIGH dan LOW dalam 1 periode). Pada percobaan PWM 1 dengan 1 LED. Dari program ya LED akan menyala 5x lebih terang. Karena terdapat delay 0,015 maka LED akan redup dengan kecepatan 0,015 sekon, lalu kemudian akan terang kembali.



https://user-images.githubusercontent.com/121172074/209066498-01275e63-3359-40e3-821c-4cff233d1df6.mp4


2. Percobaan yang kedua ini pada PWM ini hampir sama dengan PWM yang pertama diatas hanya saja menggunakan 3 LED


https://user-images.githubusercontent.com/121172074/209067060-24155b49-0197-4393-a30e-c5ecc0b2ef29.mp4



C. ADC dan DAC
1. 
