# Hotel-Booking-Cancelation-
Hotel erat sekali dengan kegiatan pemesanan, hampir semua orang yang memiliki rencana untuk menginap atau menyewa suatu kamar hotel, akan melakukan pemesanan terlebih dahulu. 
Tujuan dari pemesanan tersebut sangat beragam, baik untuk mencegah kehabisan kamar hotel hingga mendapatkan harga terbaik.

Pada kesempatan ini, kita akan melakukan prediksi mengenai pemesanan hotel yang dilakukan konsumen. 
Tujuan dari prediksi ini kita dapat menentukan suatu konsumen yang telah memesan hotel, apakah akan melakukan pembatalan pemesanan atau tidak, 
karena dalam konteks bisnis perhotelan, apabila pengunjung diasumsikan tidak malukan pembatalan pemesanan maka pihak hotel akan menyiapkan beberapa hal untuk menyambut kedatangan mereka, 
di antaranya:

* Menghubungi pengunjung terkait kapan perkiraan datang ke hotel,
* Membersihkan, merapikan, dan menyiapkan kamar sesuai pesanan pengunjung,
* Menyiapkan makanan dan minuman untuk menyambut kedatangan pengunjung,
* Menolak pengunjung lain yang memesan kamar yang telah dipesan (booked room), dan
* Memberi layanan penjemputan di bandara/stasiun/terminal apabila diperlukan.

## **Dataset**

Dataset ini berasal dari paper Jurnal Ilmiah berjudul "Hotel booking demand datasets" yang ditulis oleh Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.
Penjelasan tiap feature/variabel dari Jurnal bisa Anda akses di  https://www.sciencedirect.com/science/article/pii/S2352340918315191

Apabila ingin mengetahui keterangan di setiap kolom, Anda bisa akses ke: https://www.kaggle.com/jessemostipak/hotel-booking-demand/data. 

## **Batasan Data**
* __Ukuran data__ yang digunakan adalah **5000 baris (_rows_) awal [:5000]**.
* __Variabel__ yang dipakai berjumlah 16 kolom, yaitu: 
['hotel', 'is_canceled', 'adults', 'children', 'babies', 'meal', 'country', 'market_segment', 'distribution_channel', 'reserved_room_type', 'booking_changes', 'deposit_type', 'days_in_waiting_list','customer_type', 'required_car_parking_spaces', 'total_of_special_requests']
