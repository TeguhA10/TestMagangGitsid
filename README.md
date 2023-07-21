# TestMagangGitsid

A000124 of Sloane’s OEIS

Kompleksitas kodingan pada jawaban No.3 adalah O(n), di mana n adalah nilai dari input `n` yang diberikan pada fungsi `calculateA000124(n)`.

Penjelasan detail kompleksitas:
1. Fungsi `calculateA000124(n)` memiliki satu loop `for`, yang melakukan iterasi dari 1 hingga `n`. Oleh karena itu, loop ini berjalan sebanyak `n` kali.
2. Di dalam loop, ada beberapa operasi konstan, seperti penambahan `i` ke variabel `current`, dan penggabungan nilai `current` ke dalam variabel `output`.
3. Operasi lainnya yang dilakukan di dalam loop adalah pengujian jika nilai `i` bukanlah `n`, untuk menambahkan tanda "-" pada output. Namun, operasi ini juga berjalan sebanyak `n-1` kali, karena hanya diterapkan untuk nilai `i` dari 1 hingga `n-1`.
4. Karena kompleksitas loop `for` adalah O(n), dan operasi lainnya dalam loop adalah konstan, maka kompleksitas keseluruhan dari fungsi `calculateA000124(n)` adalah O(n).
   
Anda dapat menambahkan penjelasan di README Repo dengan menggambarkan bagaimana kompleksitas kodingan dihitung dan mengapa kompleksitasnya adalah O(n). Ini akan membantu pembaca untuk memahami performa kodingan Anda dan bagaimana kompleksitasnya berkembang seiring dengan perubahan nilai input `n`.

# Output Hasil Program

1.  A000124 of Sloane’s OEIS

![alt text](https://github.com/TeguhA10/TestMagangGitsid/blob/main/output/Sloane's%20OEIS.PNG?raw=true)

2. Dense Ranking

![alt text](https://github.com/TeguhA10/TestMagangGitsid/blob/main/output/Dense%20Ranking.PNG?raw=true)

3. Balanced Bracket

![alt text](https://github.com/TeguhA10/TestMagangGitsid/blob/main/output/Balanced%20Brecket.PNG?raw=true)
