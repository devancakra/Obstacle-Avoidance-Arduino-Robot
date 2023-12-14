[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Project](https://img.shields.io/badge/Project-Obstacle%20Avoidance%20Robot-light.svg?style=flat&logo=arduino&logoColor=white&color=25A18E)
![Arduino](https://img.shields.io/badge/Arduino-light.svg?&style=flat&logo=arduino&logoColor=white&color=2db83d)

# Obstacle-Avoidance-Arduino-Robot
Robot ini bergerak menggunakan roda dan ketika robot bergerak, sensor ultrasonik akan mendeteksi apakah area yang akan dilewati robot aman atau tidak. Jika ada rintangan yang menghalangi, maka robot akan menghindarinya dan mencari jalan lain.

<br><br>

## Fitur / Kerangka Kerja / Alat
| Media | Deskripsi |
| --- | --- |
| Papan Pengembangan | Arduino Uno R3 |
| Perangkat Lunak (Alat) | Arduino IDE |
| Pustaka Arduino | Adafruit Motor Shield, Servo |
| Aktuator | Motor Servo SG90 180°, Motor Gear / Motor DC |
| Sensor | Sensor Ultrasonik (HC-SR04) |
| Komponen Lainnya | Kabel Jumper, Kabel USB tipe A/B, Baterai Li-ion (x2), Tempat baterai, Roda robot (x4), Motor driver shield L293D |

<br><br>

## Unduh & Instal Arduino IDE
   ```
   https://www.arduino.cc/en/software
   ```

<br><br>

## Persyaratan Proyek
<table>
<tr>
<th width="420">Diagram Blok</th>
<th width="420">Diagram Ilustrasi</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Obstacle-Avoidance-Arduino-Robot/assets/54527592/168fadce-b7fe-482e-8f20-cc923b72a8aa" alt="Block-Diagram"></td>
<td><img src="https://github.com/devancakra/Obstacle-Avoidance-Arduino-Robot/assets/54527592/8106ab05-8aaf-46c7-bf56-a49b3eda044a" alt="Pictorial-Diagram"></td>
</tr>
</table>

<br><br>

## Memulai
1. Pastikan anda memiliki komponen elektronik yang diperlukan.<br><br>
   
2. Pastikan komponen anda telah dirancang sesuai dengan diagram.<br><br>
   
3. Buka ``` Arduino IDE ``` terlebih dahulu, kemudian buka proyek Obstacle Avoidance Arduino Robot dengan cara klik: ``` File ``` -> ``` Open ``` -> ``` obstacle_avoidance_robot.ino ```.<br><br>
   
4. ``` Pengaturan Board ``` di Arduino IDE<br><br>
   Cara: klik ``` Tools ``` -> ``` Board ``` -> ``` Arduino AVR Boards ``` -> ``` Arduino Uno ```.
   <br><br>
   
5. ``` Instal Pustaka ``` di Arduino IDE<br><br>
   • Cara: Unduh semua file zip pustaka. Kemudian tempelkan di: ``` C:\Users\Computer_Username\Documents\Arduino\libraries ```.
   <br><br>

6. ``` Pengaturan Port ``` di Arduino IDE<br><br>
   • Cara: klik ``` Port ``` -> Pilih sesuai dengan port perangkat Anda ``` (Anda dapat melihatnya di Device Manager) ```.
   <br><br>

7. Sebelum mengunggah program, silakan klik: ``` Verify ```.<br><br>

8. Jika tidak ada kesalahan dalam kode program, silakan klik: ``` Upload ```.<br><br>
   
9. Selamat menikmati [Selesai].

<br><br>

## Sorotan
<table>
<tr>
<th width="840">Tampilan Perangkat Keras</th>
</tr>
<tr>
<td><img src="" alt="IMG"></td>
</tr>
</table>

<br><br>

## Penafian
Aplikasi ini dibuat dengan menyertakan sumber-sumber dari pihak ketiga. Pihak ketiga di sini adalah penyedia layanan, yang layanannya berupa pustaka, kerangka kerja, dan lain-lain. Saya ucapkan terima kasih banyak atas layanannya. Telah terbukti sangat membantu dan dapat diimplementasikan.

<br><br>

## LISENSI
LISENSI MIT - Hak Cipta (c) 2023 - Devan C. M. Wijaya, S.Kom

Dengan ini diberikan izin tanpa biaya kepada siapa pun yang mendapatkan salinan perangkat lunak ini dan file dokumentasi terkait perangkat lunak untuk menggunakannya tanpa batasan, termasuk namun tidak terbatas pada hak untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual salinan Perangkat Lunak ini, dan mengizinkan orang yang menerima Perangkat Lunak ini untuk dilengkapi dengan persyaratan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus menyertai semua salinan atau bagian penting dari Perangkat Lunak.

DALAM HAL APAPUN, PENULIS ATAU PEMEGANG HAK CIPTA DI SINI TETAP MEMILIKI HAK KEPEMILIKAN PENUH. PERANGKAT LUNAK INI DISEDIAKAN SEBAGAIMANA ADANYA, TANPA JAMINAN APAPUN, BAIK TERSURAT MAUPUN TERSIRAT, OLEH KARENA ITU JIKA TERJADI KERUSAKAN, KEHILANGAN, ATAU LAINNYA YANG TIMBUL DARI PENGGUNAAN ATAU URUSAN LAIN DALAM PERANGKAT LUNAK INI, PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB, KARENA PENGGUNAAN PERANGKAT LUNAK INI TIDAK DIPAKSAKAN SAMA SEKALI, SEHINGGA RISIKO ADALAH MILIK ANDA SENDIRI.