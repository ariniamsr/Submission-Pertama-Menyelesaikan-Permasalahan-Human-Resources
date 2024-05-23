# Proyek Akhir: Menyelesaikan Permasalahan Human Resources

## ***Business Understanding***

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut. Selain itu, ia juga meminta Anda untuk membuat business dashboard untuk membantunya memonitori berbagai faktor tersebut.

### Cakupan Proyek

kita akan menerapkan analisis klasifikasi untuk attrition dengan metode machine learning. Algoritma machine learning. Kita juga akan melakukan proses Exploratory Data Analysis (EDA) untuk memperoleh gambaran terkait dataset yang akan kita gunakan. 

Kita membutuhkan beberapa resource dan tool, yaitu

data karyawan di perusahaan (employee_data).
Tool yang digunakan untuk membuat bussiness dashboard adalah Looker Studio.
bahasa pemrograman Python sebagai tool utama kita dalam proyek ini.
berbagai library pendukung untuk pengolahan data dan pengembangan model machine learning.

### Persiapan
Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee
Proyek ini dibuat melalaui Google Colaboratory (Google Colab).
```
https://colab.research.google.com/drive/1qJlMYH4BZUhiKw97v2wlJGoOH8qJaBe7?usp=sharing
```

### Proses membuat business dashboard dalam proyek ini
Business dashboard menggunakan dataset yang telah melalui tahapan persiapan. Dataset tersebut di ekspor dalam format csv dari notebook.ipynb dan setelah itu di import ke dalam Looker Studio. Selain itu, pada looker studio ada penyesuaian dan modifikasi tipe data pada beberapa variabel. 
Link business dashboard:
```
https://lookerstudio.google.com/reporting/48e6364e-a3fb-42c4-bfd9-409f6cd34a49
```

### Conclusion
Berikut ini konklusi dari proyek ini:

- Jumlah karyawan yang keluar dari Perusahaan Jaya Jaya Maju adalah sebanyak 179 orang dari total 1058 karyawan atau apabila dipresentasekan sebanyak 16,9%.
Beberapa faktor yang mempengaruhi karyawan untuk keluar dari perusahaan antara lain:
    - Jarak tempat tinggal ke kantor: Karyawan yang memiliki jarak tempat tinggal ke kantor "Intermediete_distance" dominan untuk keluar dari perusahaan
    - Kebanyakan yang keluar dari perusahaan Generation Milenial, Karena rata-rata Milenial menginginkan peluang untuk berkembang dan belajar dalam pekerjaan mereka. Kurangnya kesempatan untuk promosi, pelatihan, atau pengembangan keterampilan dapat membuat mereka merasa terjebak dan tidak termotivasi, mendorong mereka untuk mencari peluang lain di mana mereka dapat berkembang.
    - Dengan lulusan sarjana: dengan back
    - Berstatus single:  Milenial lajang mungkin lebih fokus pada pengembangan diri, seperti pendidikan, perjalanan, atau membangun hubungan. Mereka mungkin menunda pekerjaan permanen untuk fokus pada prioritas pribadi ini.

Berikut ini beberapa rekomendasi action items yang harus dilakukan oleh perusahaan:

1. Membuat program pengembangan karir yang jelas dan terstruktur: Berikan program pelatihan dan mentoring yang membantu karyawan milenial mengembangkan keterampilan dan pengetahuan mereka. Berikan kesempatan untuk promosi dan rotasi pekerjaan untuk mendorong pertumbuhan dan pengembangan profesional.
2. Meningkatkan transparansi dan komunikasi terkait peluang karir: Berikan informasi yang jelas tentang jalur karir yang tersedia, persyaratan untuk promosi, dan proses evaluasi kinerja. Lakukan komunikasi terbuka dan transparan dengan karyawan tentang peluang pengembangan karir.
3. Menerapkan kebijakan kerja yang fleksibel: Memberikan pilihan jam kerja yang fleksibel, seperti jam kerja yang lebih pendek, telecommuting, atau compressed workweek. Hal ini memungkinkan karyawan milenial untuk menyeimbangkan pekerjaan dan kehidupan pribadi mereka dengan lebih mudah.
4. Menyediakan fasilitas dan program yang mendukung keseimbangan kehidupan kerja: Menyediakan fasilitas seperti ruang istirahat yang nyaman, gym, atau daycare. Menawarkan program seperti kelas yoga, meditasi, atau konseling kesehatan mental untuk membantu karyawan milenial mengelola stres dan menjaga kesehatan mental mereka.
5. Mengadakan acara dan kegiatan sosial: Mengadakan acara dan kegiatan sosial untuk membangun rasa kebersamaan dan komunitas antar karyawan. Hal ini dapat meningkatkan moral dan motivasi karyawan.
6. Menawarkan program bantuan untuk pengembangan diri: Menawarkan program bantuan untuk pengembangan diri, seperti kursus bahasa, pelatihan kepemimpinan, atau program mentoring. Hal ini dapat membantu karyawan milenial lajang mencapai tujuan pribadi dan profesional mereka.
