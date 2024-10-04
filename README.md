# Implementasi Otomasi Proses ML dengan Makefile
1.	Langkah awal membuat folder project yang nanti akan memuat kode source
2.	Membuat folder scripts yang berisikan data_prep.py, train_model.py, evaluate_model.py, dan deploy_model.py
3.	Membuat file Makefile di folder utama
![image](https://github.com/user-attachments/assets/458d6b63-d7be-49f5-9af9-65ea581c8f9b)

4.	Membuat struktur perintah di setiap file python
5.	Download Makefile menggunakan Windows Powershell Administrator dengan Chocolatey
 ![image](https://github.com/user-attachments/assets/850e52b4-d37c-484e-a673-90c2b93be253)

6.	Jalankan perintah make data di terminal
 Perintah tersebut akan menjalankan scripts data_prep.py yang mengunduh dataset iris dan di simpan dalam folder data.
7.	Jalankan perintah make train di terminal
 Perintah tersebut akan menjalankan scripts train_model.py yang melatih dataset iris dengan menggunakan decision tree lalu model tersebut disimpan dalam folder models.
8.	Jalankan perintah make evaluate di terminal
 Perintah tersebut akan menjalankan scripts evaluate_models.py yang akan memprediksi dataset testing dan di evaluasi hasil prediksi dengan evaluasi metrics accuracy, precision, recall, dan F1-Score.
9.	Jalankan perintah make deploy di terminal
 Perintah tersebut akan menjalankan scripts deploy_model.py yang akan menyimpan hasil model ke dalam serialisasi format.
