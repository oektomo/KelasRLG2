# Laporan Reinforcement Learning : Pertemuan 1
<div>
<img src="https://orbitfutureacademy.id/wp-content/uploads/2020/02/logo_dark.png"
     alt="Markdown Monster icon"
     style="float: left; width:20%"/>
     <br>
<img src="illustration.jpg"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;"/>
     </div>
<br>

## Anggota
| Nama | Kelas |
| ---- | ----- |
| Mochammad Dozen K | Better |
| Banda Subagja | Atlas |
| Mohd. Agus Fadillah Sani | Visioner |
| Muhammad Alfan Irsyadi Hutagalung | Persevere |
| ABD HAMID AFANDI | Alan Turing |

## Pengantar
Reinforcement Learning (RL) [in-rID: Pembelajaran Penguatan] adalah area pembelajaran mesin yang berkaitan dengan bagaimana agen cerdas harus mengambil tindakan di lingkungan untuk memaksimalkan gagasan penghargaan kumulatif. Pembelajaran penguatan adalah salah satu dari tiga paradigma pembelajaran mesin dasar, di samping pembelajaran terawasi dan pembelajaran tanpa pengawasan.

Pembelajaran penguatan berbeda dari pembelajaran terawasi dalam hal tidak perlunya pasangan input/output berlabel disajikan, dan dalam tidak membutuhkan tindakan sub-optimal untuk dikoreksi secara eksplisit. Sebaliknya fokusnya adalah menemukan keseimbangan antara eksplorasi (wilayah yang belum dipetakan) dan eksploitasi (pengetahuan saat ini). Algoritma RL yang diawasi sebagian dapat menggabungkan keunggulan algoritma yang diawasi dan RL.

Lingkungan biasanya dinyatakan dalam bentuk Markov Decision Process (MDP), karena banyak algoritma pembelajaran penguatan untuk konteks ini menggunakan teknik pemrograman dinamis. Perbedaan utama antara metode pemrograman dinamis klasik dan algoritma pembelajaran penguatan adalah bahwa yang terakhir tidak mengasumsikan pengetahuan tentang model matematika yang tepat dari MDP dan mereka menargetkan MDP besar di mana metode yang tepat menjadi tidak layak.

## Intruksi
Aktivitas Kelas RL Pertemuan pertama:
1. Cari dan tuliskan satu contoh aplikasi/implementasi RL dibidang anda!
2. Jelaskan secara singkat mengapa aplikasi tersebut merupakan aplikasi berbasis RL, jelaskan berdasarkan kesesuaian dengan karakteristik RL!
3. Dari aplikasi tersebut, tentukan: (a) Objective (b) State (c) Action (d) Reward (e) Termination.
4. Berdasarkan 3 nomor diatas, utarakan/jelaskan  pemahaman anda tentang RL, terkait karakteristik, derajat kemudahan/kesulitan untuk diaplikasikan menyelesaikan masalah riil dst.


## Jawaban
1.	AlphaZero yang dikembangkan untuk menguasai permainan catur.

2.	AI AlphaZero menggunakan algoritma Monte Carlo Tree Search untuk menentukan gerakan yang akan diambil berdasarkan kecerdasan yang didapat sebelumnya melalui proses machine learning, lebih detailnya melalui metode deep learning dan pelatihan yang berulang ulang.

3.	Pengaplikasian AlphaZero terhadap metode Markov Decision Process sebagai berikut:
a.	Objective: Periksa langkah dan skakmat untuk mengakhiri permainan di mana menang/seri.
b.	State: .Menunggu lawan bergerak (Giliran), Melindungi bidak kita , atau memakan bidak lawan, mendekati skakmat atau bertahan.
c.	Action: Pergerakan bidak.
d.	Reward: (+)Memakan bidak musuh ,(-) Membuat bidak dapat termakan
e.	Termination: Ketika keadaan pergerakan bidak raja mutlak mati/skakmat.


4. Mengembangkan suatu model program komputer yang mana dibuat untuk memecahkan masalah tertentu*.
RL membutuhkan daya komputasi yang besar jika digunakan untuk memecahkan masalah yang rumit, dikaitkan dengan konteks kita menghadapi masalah di  real life, mungkin masalah yang kita hadapi bisa sederhana, tetapi mungkin kita akan menggunakan RL untuk beberapa masalah yang tidak bisa dilakukan oleh daya manusia dengan metode manual, karena kita tidak bisa langsung menggunakan AI dan mengganti semua pekerja manusia.
 Selain itu AI meskipun sangat powerful, dan prospeknya sangat menjanjikan, tetapi membutuhkan pengembangan yang sangat lama agar bekerja dengan baik sampai bisa diandalkan untuk menangani suatu pekerjaan dengan baik. Metode RL membutuhkan banyak waktu untuk mengembangkannya sampai bisa diimplementasikan di real life, selain itu untuk implementasi real life mungkin membutuhkan fasilitas/ environment simulasi/training/ learning yang bisa me replika environment real life, dan mungkin itu mahal.
