# Nangor Blast

**Tugas Besar IF2010** 
**Pemrograman Berorientasi Objek**  
**Kelompok K1-D**  

## Deskripsi Program

**Nangor Blast** merupakan proyek permainan berbasis **Java** dengan konsep permainan berbasis grid yang terinspirasi dari Bomberman. Pemain menjelajahi map, menghindari dan mengalahkan musuh, memasang berbagai jenis bom, mengumpulkan power-up, serta mencapai pintu keluar sesuai ketentuan permainan.

Kelompok K1-D mengimplementasikan **Map Type B (Blue Resort)**, dengan mekanisme lingkungan khusus berupa **Water Tile**, **Switch**, dan **Gate**. Water Tile memengaruhi kecepatan gerak pemain, sedangkan Switch mengubah kondisi Gate yang membuka atau menutup jalur.

## Pembagian Tugas Milestone 1

| Anggota | Tanggung jawab |
| --- | --- |
| **Olsen Danilson Sitohang** | Menyiapkan struktur awal pembagian tuga, scaffold repository (Gradle/Maven, Makefile, README awal), diagram **GameWorld, GameState, MainMenu, GameLoop, Score, InputHandler**, dan **Renderer**. |
| **Davindra Rasya Nugroho** | Membuat repository GitHub, class diagram **Map** dan **Tile**, diagram mekanisme **Water Tile, Switch, Gate**, class diagram **Block** (3 jenis), diagram **MapValidator**. |
| **Willhelmina Rachel Silalahi** | Membuat drive terpusat dan dokumen pembagian tugas, class diagram **Player**, abstract class **Bomb** dan turunannya (**NormalBomb, PumpedBomb, RemoteBomb**) serta **Explosion**, menentukan atribut, method, inheritance, dan relasi. |
| **Muhammad Dhafin Faidhulhaq** | Class diagram **Normal Enemy** (patrol/chase), **Boss Leviathan** dan **Power-Up**, menentukan atribut, method, dan relasi antarkelas. |

Hasil rancangan tiap modul akan digabung menjadi class diagram keseluruhan sistem untuk dokumentasi Milestone 1.

## Daftar Fitur dan Status Pengerjaan

| Fitur / Modul | Cakupan | Status implementasi |
| --- | --- | --- |
| **F00 — Inisialisasi** | Pemuatan kondisi awal permainan dan restart | Direncanakan (M2) |
| **F01 — Player** | Pergerakan, nyawa, dan kemampuan pemain | Direncanakan (M2) |
| **F02 — Bomb** | Normal Bomb, Pumped Bomb, Remote Bomb | Direncanakan (M2) |
| **F03 — Explosion** | Penyebaran ledakan, damage, dan chain reaction | Direncanakan (M2) |
| **F04 — Block** | Indestructible, Destructible, Reinforced Block | Direncanakan (M2) |
| **F05 — Enemy** | Normal Enemy (patrol/chase) dan Boss Leviathan | Direncanakan (M2) |
| **F06 — Power-Up** | Peningkatan kemampuan pemain dan item | Direncanakan (M2) |
| **F07 — Map** | Blue Resort, Water Tile, Switch, Gate, dan validasi map | Direncanakan (M2) |
| **F08 — Score** | Pengelolaan skor permainan | Direncanakan (M2) |
| **F09 — Game Flow** | Menu, GameState, GameLoop, pause, WIN/LOSE | Direncanakan (M2) |
| **Antarmuka** | Tampilan menu, permainan, HUD, input, dan renderer | Direncanakan (M2) |
