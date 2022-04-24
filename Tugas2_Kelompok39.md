
# Cari status kasus di environment OpenAI yang bisa diselesaikan dengan Monte Carlo, pelajari programnya.
Kasus: Frozen Lake


## 1. Jelaskan yang anda pahami tentang mekanisme kerja dari program tersebut!
Frozen lake merupakan lingkungan berbentuk grid dan terdapat beragam petak dalam grid tersebut yang berlabel. S untuk titik mulai, F untuk petak beku (aman untuk dilewati), H untuk petak berlubang (tidak aman untuk dilewati) dan G sebagai petak tujuan. Hanya ada satu tujuan di lingkungan ini, yakni bergerak dari petak mulai hingga petak tujuan tanpa melangkah ke petak berlubang.

Di frozen lake, aksi yang dapat diambil berupa arah dari petak. Kanan, kiri, atas dan bawah. States dalam frozen lake berupa lokasi dalam setiap tile, di mana jika masuk ke lubang akan memberhentikan episode (sama halnya jika masuk ke petak tujuan). Dengan monte carlo, policy terbaik dicari dengan menjalankan berkali-kali episode. Setiap episode nilai policy berbeda supaya dapat results yang variatif. Total reward per episode kemudian dirata-rata untuk merepresentasikan value pada suatu state dimasa depan. Proses yang dilakukan berulang kali pada setiap state, dapat memberi perkiraan untuk value asli pada saat state tertentu yang asli.




## 2. Beda DP dan MC dalam menyelesaikan Frozen Lake Problem

MDP di setiap state akan memperkirakan probabilitas terbesar untuk selesai di awal dan bukan pada setiap state. Sedangkan MC mendapat value function dengan menjalankan banyak kali episode dan akan merata-rata return dari hasil uji coba sebelumnya. 


