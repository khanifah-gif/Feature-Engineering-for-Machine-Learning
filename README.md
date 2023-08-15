# Feature-Engineering-for-Machine-Learning
Repository ini mencoba menerapkan proses feature engineering dalam membangun model machine learning dan kemudian dibandingkan hasilnya dengan model yang dibangun menggunakan fitur tanpa feature engineering

# Feature Engineering?
Feature engineering adalah proses di mana Anda menciptakan fitur-fitur baru atau mengubah fitur-fitur yang ada dalam dataset Anda dengan tujuan untuk meningkatkan performa model machine learning. Tujuan utama dari feature engineering adalah untuk menghasilkan representasi yang lebih baik dari data yang dapat membantu model dalam mengidentifikasi pola dan membuat prediksi yang lebih akurat.

# What we need to prepare?
Data: data yang digunakan adalah dataset titanic yang diperoleh dari kaggle

# Data Preparation
1. Imputasi missing value
2. feature correlation

# Exploratory Data Analysis
![visualization Survival](https://github.com/khanifah-gif/Feature-Engineering-for-Machine-Learning/assets/100893371/01c98372-128c-4be4-adb8-77d6f2368f86)

![Fare](https://github.com/khanifah-gif/Feature-Engineering-for-Machine-Learning/assets/100893371/0fcbf43c-1262-49d0-9cd6-cb88df9f4c57)

![family_size_visualization](https://github.com/khanifah-gif/Feature-Engineering-for-Machine-Learning/assets/100893371/2c9eb8e6-1e48-44ad-9083-b65bf95a806e)

![Family size grouped](https://github.com/khanifah-gif/Feature-Engineering-for-Machine-Learning/assets/100893371/84b9bace-9b71-41e9-8697-dbf99cfa5362)

# Model
Model dibangun menggunakan algoritma Random Forest
![image](https://github.com/khanifah-gif/Feature-Engineering-for-Machine-Learning/assets/100893371/4eb29336-3ee0-49b2-8baf-6a55a5834923)

# Kesimpulan
Berdasarkan dua variasi model yang telah dibuat dengan model 1 adalah model yang dibangun menggunakan fitur hasil feature engineering dan model 3 adalah model yang dibangun menggunakan fitur asli, didapat nilai akurasi seperti pada tabel.

Akurasi train tanpa feature engineering lebih rendah sebesar 0.03 atau 3% dari akurasi model dengan feature engineering. Hal ini menunjukkan feature engineering dapat meningkatkan akurasi model pada kasus ini. Namun, setelah model diterapkan pada data test, akurasi dengan model tanpa feature engineering ternyata dapat lebih dipertahankan daripada dengan feature engineering. Tingkat overfitting pada model dengan feature engineering lebih besar yang ditunjukkan oleh selisih akurasi pada data train dan data test yang lebih tinggi. Oleh karena itu, setiap kali melakukan feature engineering perlu dilakukan evaluasi model agar dapat melihat performa model dan bisa memutuskan model mana yang akan digunakan.
