
## **Sistem Manajemen Nilai Berbasis Outcome Based Education (OBE) menggunakan Moodle LMS**

### **Goals**

1. **Kemudahan Manajemen Nilai**:  
   Membantu pengguna (dosen dan administrator) mengelola gradebook dengan antarmuka yang intuitif dan proses yang efisien.  

2. **Penerapan OBE**:  
   Mengintegrasikan konsep Outcome Based Education ke dalam pengelolaan penilaian di LMS untuk memastikan keselarasan antara capaian pembelajaran dengan evaluasi.


### **Deliverables**

1. **Backend Service**:  
   Sistem backend yang memungkinkan integrasi dengan Moodle menggunakan external webservice.  

2. **Integrasi LMS-SIA**:  
   Sistem yang mendukung sinkronisasi data antara LMS berbasis Moodle dengan Sistem Informasi Akademik (SIA).  

3. **UI/UX LMS OBE Gradebook**:  
   Antarmuka pengguna untuk gradebook berbasis OBE yang ramah pengguna, responsif, dan sesuai kebutuhan spesifik pengguna.  


### **Roadmap**

#### **1. Analisis dan Pengembangan Backend**  
   - **Tujuan**: Mengembangkan layanan backend berbasis webservice untuk mendukung pengelolaan gradebook.  
   - **Aktivitas**:
     1. Analisis API dan ekstensi Moodle untuk manajemen gradebook.
     2. Pengembangan endpoint API untuk CRUD grade.
     3. Pengujian integrasi API dengan modul Moodle.  
   - **Output**: Backend service dengan dokumentasi API.  

#### **2. Pengembangan Sistem Cerdas untuk Konfigurasi Otomatis LMS berdasdarkan RPS (Rencana Pembelajaran Semester)**
   - **Tujuan**: Menembangkan sistem POC (Prove of Concept) memanfaatkan AI dan atau generative AI untuk mengkonversi dokumen RPS menjadi konfigurasi LSM berbasis Moodle.
   - **Aktivitas**:
     1. Melakukan riset penggunaan AI yang dapat mengambil informasi dari dokumen RPS untuk digunakan sebagai sumber data pengaturan LSM.
     2. Melakukan riset penggunaan Generative AI untuk memberikan rekomendasi pengembangan konten pembelajaran di LMS.
     3. Membangun sistem POC.

#### **3. Integrasi LMS dan SIA**  
   - **Tujuan**: Membuat arsitektur sistem yang memungkinkan sinkronisasi data nilai dan capaian pembelajaran antar sistem.  
   - **Aktivitas**:
     1. Analisis data model di LMS dan SIA.
     2. Rancangan protokol sinkronisasi (misalnya REST API atau middleware).
     3. Pengembangan modul sinkronisasi (transfer nilai, data mahasiswa, capaian pembelajaran).  
   - **Output**: Modul integrasi dengan dokumentasi teknis.  

#### **4. Desain dan Pengembangan UI/UX OBE Gradebook**  
   - **Tujuan**: Membuat antarmuka pengguna yang mendukung konsep OBE.  
   - **Aktivitas**:
     1. Riset kebutuhan pengguna melalui wawancara dan survei.
     2. Pembuatan wireframe dan prototipe awal antarmuka gradebook.
     3. Pengembangan desain final dan pengujian usability.  
   - **Output**: Desain UI/UX siap implementasi dan laporan hasil pengujian usability.  

### **Tim yang Dibutuhkan**

1. **Product Manager**: Koordinator proyek dan pengelolaan roadmap.  
2. **Backend Developer**: Mengembangkan webservice dan modul integrasi.  
3. **UI/UX Designer**: Mendesain antarmuka pengguna berbasis OBE.  
4. **System Analyst**: Menganalisis arsitektur sistem dan integrasi.  
5. **QA Engineer**: Pengujian fungsionalitas dan usability sistem.  
6. **Trainer**: Melatih pengguna dalam memanfaatkan sistem.  

### **Teknologi**

1. **Moodle**: Sebagai LMS utama.  
2. **PHP/MySQL**: Untuk pengembangan webservice Moodle.  
3. **REST API**: Untuk sinkronisasi LMS-SIA.  
4. **Figma/Adobe XD**: Untuk desain UI/UX.  
5. **Postman**: Untuk pengujian API.  

## **📄 Dokumentasi**  
Semua dokumentasi terkait perencanaan, desain, dan pengembangan perangkat lunak ini tersedia di halaman [Wiki](../../wiki). Dokumentasi ini mencakup:  
- **Kebutuhan Fungsional**  
- **Desain Sistem**  
- **Rencana Implementasi**  
- **Pengujian dan Validasi**  

Dokumentasi akan diperbarui secara berkala seiring dengan perkembangan proyek. Pastikan untuk memeriksa halaman Wiki untuk mendapatkan informasi terbaru.  

## **🤝 Kolaborasi**  
Proyek ini adalah proyek terbuka, dan kami mengundang Anda untuk bergabung dalam pengembangannya!  
Berikut beberapa cara Anda dapat berkontribusi:  
1. Membuka _Issues_ untuk melaporkan bug atau memberikan saran fitur baru.  
2. Membuat _Pull Request_ untuk menyumbangkan kode, memperbaiki bug, atau menambahkan fitur.  
3. Berpartisipasi dalam diskusi pengembangan untuk berbagi ide dan masukan.  

### **Cara Berkontribusi**  
1. _Fork_ repository ini.  
2. Lakukan perubahan di branch Anda.  
3. Ajukan _Pull Request_ ke branch utama proyek ini.  

Kami sangat menghargai setiap kontribusi yang Anda berikan untuk membuat BridgingApp lebih baik lagi. Jangan ragu untuk menghubungi kami melalui tab _Discussions_ atau _Issues_ jika Anda memiliki pertanyaan atau ide.  

