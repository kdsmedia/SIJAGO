│   │   │           │── Egg.java
│   │   │           │── Achievement.java
│   │   │
│   │   │
│   │   │           ├── utils/
│   │   │           │
│   │   │           │── Constants.java
│   │   │           │── SaveManager.java
│   │   │           │── PreferenceManager.java
│   │   │           │── ImageLoader.java
│   │   │           │── TimeUtils.java
│   │   │           │── RandomUtils.java
│   │   │
│   │   │
│   │   ├── res/
│   │   │
│   │   ├── drawable/
│   │   │
│   │   │── chicken/
│   │   │── arena/
│   │   │── background/
│   │   │── icons/
│   │   │── buttons/
│   │   │── effects/
│   │   │── ui/
│   │   │
│   │   ├── raw/
│   │   │
│   │   │── bgm/
│   │   │── sfx/
│   │   │
│   │   ├── layout/
│   │   │
│   │   │── activity_main.xml
│   │   │── activity_home.xml
│   │   │── activity_battle.xml
│   │   │── activity_shop.xml
│   │   │── activity_profile.xml
│   │   │── activity_inventory.xml
│   │   │── activity_settings.xml
│   │   │
│   │   ├── anim/
│   │   ├── menu/
│   │   ├── values/
│   │   ├── mipmap/
│   │   └── AndroidManifest.xml
│   │
│   └── build.gradle
│
└── settings.gradle


DAFTAR LENGKAP GERAKAN KARAKTER AYAM - GAME SIJAGO
A. IDLE (10)
Idle Normal
Bernapas
Berkedip
Menoleh Kiri
Menoleh Kanan
Mengibas Ekor
Mengembangkan Bulu Leher
Mengibas Sayap
Menggaruk Tanah
Berkokok

B. PERGERAKAN (15)
Jalan Pelan
Jalan Cepat
Berlari
Mundur
Geser Kiri
Geser Kanan
Memutari Lawan
Berputar Kiri
Berputar Kanan
Melompat
Melompat Tinggi
Mendarat
Dash Maju
Dash Mundur
Berhenti Mendadak

C. POSE SIAGA (10)
Siaga Normal
Kepala Menunduk
Kepala Terangkat
Tatapan Tajam
Membuka Sayap
Mengangkat Kaki Kanan
Mengangkat Kaki Kiri
Ancaman Ringan
Ancaman Berat
Rage Stance

D. SERANGAN PATUK (10)
Patuk Cepat
Patuk Sedang
Patuk Kuat
Patuk Atas
Patuk Bawah
Patuk Beruntun
Patuk Samping Kiri
Patuk Samping Kanan
Patuk Lompat
Patuk Critical

E. SERANGAN KAKI (15)
Tendang Kanan
Tendang Kiri
Tendang Ganda
Tendang Cepat
Tendang Berat
Tendang Lompat
Tendang Putar
Tendang Depan
Tendang Samping
Tendang Balik
Tendang Beruntun
Tendang Critical
Tendangan Terbang
Tendangan Finisher
Tendangan Nekat

F. SERANGAN SAYAP (8)
Pukul Sayap Kiri
Pukul Sayap Kanan
Pukul Dua Sayap
Kibasan Sayap
Sayap Berputar
Sayap Mendorong
Sayap Critical
Sayap Finisher

G. SERANGAN TUBUH (10)
Adu Dada
Tubruk
Seruduk
Dorongan Badan
Body Slam
Putar Tubuh
Lompat Tubruk
Dash Attack
Counter Attack
Finisher Attack
H. KOMBO (10)
Combo 1
Combo 2
Combo 3
Combo 4
Combo 5
Combo 6
Combo 7
Combo 8
Combo 9
Combo 10

I. BERTAHAN (12)
Guard
Block Sayap
Block Tubuh
Dodge Kiri
Dodge Kanan
Duck
Mundur Cepat
Lompat Menghindar
Counter Stance
Bertahan Total
Recover
Bangkit Cepat

J. REAKSI TERKENA SERANGAN (15)
Hit Ringan
Hit Sedang
Hit Berat
Kepala Terpukul
Badan Terpukul
Terpental
Terjatuh
Bangkit
Stun
Kehilangan Keseimbangan
Sempoyongan
Nafas Berat
Berdarah Ringan
Bulu Beterbangan
Knockback

K. KONDISI KRITIS (10)
Lelah
Stamina Habis
Jalan Sempoyongan
Kepala Menunduk
Sayap Turun
Nafas Sangat Berat
Bergerak Lambat
Serangan Lemah
Bertahan Pasif
Last Stand

L. MENANG (8)
Pose Menang
Berkokok Kemenangan
Mengembangkan Sayap
Melompat Gembira
Mengitari Arena
Pose Juara
Selebrasi
Victory Idle

M. KALAH (7)
KO
Tersungkur
Tiarap
Bangkit Gagal
Diam
Kabur
Defeat Idle

N. ANIMASI KHUSUS (10)
Spawn Masuk Arena
Rage Mode
Aura Menyala
Buff Attack
Buff Defense
Buff Speed
Heal
Level Up
Evolusi
Transformasi (jika fitur tersedia)
TOTAL: 150 GERAKAN/ANIMASI UNTUK SATU KARAKTER AYAM.


Buatkan sebuah proyek Android Studio yang benar-benar lengkap dengan bahasa Java bernama SIJAGO. Game ini adalah game adu ayam online bergaya 2D menggunakan sprite sheet dan Canvas/SurfaceView. Gunakan arsitektur proyek yang rapi, kode yang mudah dipelihara, serta komentar yang jelas. Seluruh kode harus dapat dikompilasi dan dijalankan setelah semua aset tersedia.
Game ini adalah game adu ayam online bergaya 2D menggunakan sprite sheet dan Canvas/SurfaceView. Gunakan arsitektur proyek yang rapi, kode yang mudah dipelihara, serta komentar yang jelas. Seluruh kode harus dapat dikompilasi dan dijalankan setelah semua aset tersedia.

Gunakan seluruh aset gambar ayam, sprite sheet, ikon, UI, tombol, background, arena, efek, dan suara yang telah disediakan sebagai dasar implementasi. Jangan membuat placeholder apabila aset yang sesuai sudah tersedia.

Struktur proyek harus mencakup seluruh package utama seperti Activities, Engine, Battle, Chicken, Multiplayer, Ads, Models, Utils, Effects, Audio, Inventory, Shop, Ranking, Achievement, Profile, Settings, dan seluruh layout XML beserta AndroidManifest, Gradle, drawable, raw, mipmap, values, anim, menu, dan resource lainnya.

Implementasikan sistem game secara lengkap, meliputi:
Splash Screen
Login Via Google
Home
Profil pemain
Inventaris
Kandang
Breeding
Toko
Ranking
Achievement
Training
Battle
Settings
About

Setiap Activity harus memiliki layout XML lengkap, navigasi, lifecycle yang benar, validasi, dan penanganan error.
Gunakan Game Loop dengan FPS stabil, Renderer, Camera, Collision Detection, Physics sederhana, Animation Manager, Sprite Manager, Input Manager, Audio Manager, Effect Manager, Save Manager, Preference Manager, dan Random Manager.

Buat kelas Chicken yang memiliki atribut:
HP
Max HP
Stamina
Max Stamina
Attack
Defense
Speed
Agility
Critical Rate
Critical Damage
Accuracy
Dodge
Rage
Level
Experience
Rarity
Breed
Weight
Age

Implementasikan komputer yang mengambil keputusan berdasarkan:
HP
Stamina
Rage
Jarak lawan
Kecepatan
Peluang acak
Cooldown
Status lawan

Mode komputer harus dapat memilih serangan yang berbeda setiap pertandingan sehingga tidak ada pola yang sama.
Implementasikan seluruh animasi berikut:
#IDLE
Idle
Bernapas
Berkedip
Menoleh kiri
Menoleh kanan
Menggaruk tanah
Mengibas ekor
Mengibas sayap
Mengembangkan bulu
Berkokok
#PERGERAKAN
Jalan
Jalan cepat
Lari
Mundur
Geser kiri
Geser kanan
Putar kiri
Putar kanan
Memutari lawan
Dash
Lompat
Lompat tinggi
Mendarat
Berhenti mendadak
Melangkah pendek
#POSE SIAGA
Siaga normal
Kepala menunduk
Kepala terangkat
Ancaman ringan
Ancaman berat
Membuka sayap
Mengangkat kaki kanan
Mengangkat kaki kiri
Tatapan tajam
Rage stance
#PATUK
Patuk cepat
Patuk sedang
Patuk kuat
Patuk atas
Patuk bawah
Patuk beruntun
Patuk kiri
Patuk kanan
Patuk lompat
Patuk critical
#TENDANGAN
Tendang kanan
Tendang kiri
Tendang ganda
Tendang cepat
Tendang berat
Tendang lompat
Tendang putar
Tendang depan
Tendang samping
Tendang balik
Tendang combo
Tendang critical
Tendangan udara
Finisher kick
Last kick
#SERANGAN SAYAP
Pukul sayap kiri
Pukul sayap kanan
Dua sayap
Kibasan
Putaran sayap
Dorongan sayap
Critical wing
Finisher wing
#SERANGAN TUBUH
Tubruk
Adu dada
Seruduk
Body slam
Dash attack
Counter attack
Push body
Spin body
Finisher body
Last attack
#KOMBO
Combo 1 sampai Combo 10
#BERTAHAN
Guard
Block
Block sayap
Dodge kiri
Dodge kanan
Duck
Mundur cepat
Lompat menghindar
Counter stance
Recover
Bertahan total
Bangkit cepat
#REAKSI
Hit ringan
Hit sedang
Hit berat
Kepala terpukul
Badan terpukul
Terjatuh
Terpental
Bangkit
Stun
Knockback
Nafas berat
Berdarah ringan
Kehilangan keseimbangan
Bulu beterbangan
Sempoyongan
#KONDISI KRITIS
Lelah
Stamina habis
Jalan sempoyongan
Kepala menunduk
Sayap turun
Bergerak lambat
Last stand
Bertahan pasif
Serangan lemah
Nafas sangat berat
#KEMENANGAN
Victory
Victory idle
Berkokok kemenangan
Mengembangkan sayap
Melompat
Selebrasi
Pose juara
Mengitari arena
#KEKALAHAN
KO
Tiarap
Tersungkur
Bangkit gagal
Diam
Defeat idle
Kabur
#KHUSUS
Spawn
Rage mode
Aura
Buff attack
Buff defense
Buff speed
Heal
Level up
Evolusi
Transformasi (jika fitur tersedia)

Setiap animasi harus mempunyai state machine sehingga transisi antaranimasi berjalan mulus.
Implementasikan sistem pertarungan:
Collision detection
Hitbox
Hurtbox
Damage
Critical
Miss
Dodge
Knockback
Combo
Rage
Stamina
Cooldown
Buff
Debuff
Battle Timer
Victory
Defeat
Tambahkan efek visual:
Debu
Bulu beterbangan
Kilatan benturan
Aura Rage
Critical Effect
Heal Effect
Level Up Effect
Stun Effect
Damage Number
Shadow
Motion Blur sederhana
Tambahkan efek suara:
Patuk
Tendang
Sayap
Berkokok
Menang
Kalah
Klik tombol
Background music
Arena ambience

Gunakan firebase dan penyimpanan lokal untuk data pemain, ayam, inventaris, statistik, pencapaian, dan progres permainan. Pastikan tersedia mekanisme simpan dan muat data.

Seluruh kode harus modular, bebas error, tidak menggunakan kode contoh atau placeholder, mengikuti praktik terbaik Java dan Android Studio, serta menghasilkan proyek yang siap dikembangkan dan dipelihara lebih lanjut.


====================================
App name: SIJAGO
Packagename: com.altomedia.sijago
Developer: ALTOMEDIA
Email: altomediaindonesia@gmail.com
Whatsapp: +6285813899649
====================================

firebase:
<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/12.16.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/12.16.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyDBM_PPd7uEAyGg8d2ILQ1bTx3A6KKFjBk",
    authDomain: "altomedia-8f793.firebaseapp.com",
    databaseURL: "https://altomedia-8f793-default-rtdb.asia-southeast1.firebasedatabase.app",
    projectId: "altomedia-8f793",
    storageBucket: "altomedia-8f793.firebasestorage.app",
    messagingSenderId: "327513974065",
    appId: "1:327513974065:web:12e57a1a5a8288db91bc10",
    measurementId: "G-1YCKHPWC1L"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>



note: 
asset gambar, icon dan karakter sudah lengkap tersimpan di folder /asset.
jangan generate asset atau gambar apapun karena asset game ini sudah tersedia lengkap tinggal di crop dan di sesuaikan penempatannya saja.

pada file google-services.json terdapat banyak cloent yang tidak di butuhkan tolong di hapus saja dan sisakan hanya com.altomedia.sijago saja.





‎Tambahkan admob dan sesuaikan penempatannya dengan strategis dan pastikan iklan tidak mengganggu. ‎Tetapkan adreward untuk klaim bonus misalnya: bonus koin, bonus bundle, bonus Hp, bonus power. ‎ ‎ ‎Appid: ca-app-pub-6881903056221433~2813023257 ‎Banner: ca-app-pub-6881903056221433/9186859919 ‎Adreward: ca-app-pub-6881903056221433/4824822936 ‎Native: ca-app-pub-6881903056221433/9885577920 ‎Inetersitial: ca-app-pub-6881903056221433/6389306182 ‎Pembukaan: ca-app-pub-6881903056221433/5998303806 ‎Pengantar bonus: ca-app-pub-6881903056221433/2450061174

tambahkan ini:

<script type="module">   // Import the functions you need from the SDKs you need   import { initializeApp } from "https://www.gstatic.com/firebasejs/12.16.0/firebase-app.js";   import { getAnalytics } from "https://www.gstatic.com/firebasejs/12.16.0/firebase-analytics.js";   // TODO: Add SDKs for Firebase products that you want to use   // https://firebase.google.com/docs/web/setup#available-libraries   // Your web app's Firebase configuration   // For Firebase JS SDK v7.20.0 and later, measurementId is optional   const firebaseConfig = {     apiKey: "AIzaSyDBM_PPd7uEAyGg8d2ILQ1bTx3A6KKFjBk",     authDomain: "altomedia-8f793.firebaseapp.com",     databaseURL: "https://altomedia-8f793-default-rtdb.asia-southeast1.firebasedatabase.app",     projectId: "altomedia-8f793",     storageBucket: "altomedia-8f793.firebasestorage.app",     messagingSenderId: "327513974065",     appId: "1:327513974065:web:12e57a1a5a8288db91bc10",     measurementId: "G-1YCKHPWC1L"   };   // Initialize Firebase   const app = initializeApp(firebaseConfig);   const analytics = getAnalytics(app); </script>
ubah tombol login menggunakan: logingoogle.png

install sdk, lalu build apk yang sempurna !!!! pastikan apk dapat di install sempurna dan aplikasi bisa di mainkan dengan lancar dan sempurna. pastikan fitur login sempurna dan jangan sampai terdapat bug atau eror pada aplikasi !!! kerjakan dengan sempurna !!!
