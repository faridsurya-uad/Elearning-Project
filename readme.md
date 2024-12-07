
## **Proyek: Sistem Manajemen Nilai Berbasis Outcome Based Education (OBE)**

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

#### **2. Integrasi LMS dan SIA**  
   - **Tujuan**: Membuat arsitektur sistem yang memungkinkan sinkronisasi data nilai dan capaian pembelajaran antar sistem.  
   - **Aktivitas**:
     1. Analisis data model di LMS dan SIA.
     2. Rancangan protokol sinkronisasi (misalnya REST API atau middleware).
     3. Pengembangan modul sinkronisasi (transfer nilai, data mahasiswa, capaian pembelajaran).  
   - **Output**: Modul integrasi dengan dokumentasi teknis.  

#### **3. Desain dan Pengembangan UI/UX OBE Gradebook**  
   - **Tujuan**: Membuat antarmuka pengguna yang mendukung konsep OBE.  
   - **Aktivitas**:
     1. Riset kebutuhan pengguna melalui wawancara dan survei.
     2. Pembuatan wireframe dan prototipe awal antarmuka gradebook.
     3. Pengembangan desain final dan pengujian usability.  
   - **Output**: Desain UI/UX siap implementasi dan laporan hasil pengujian usability.  

### **Milestones**

1. **Bulan 1-2**: Penyelesaian analisis kebutuhan dan desain sistem (Backend, Integrasi, UI/UX).  
2. **Bulan 3-4**: Pengembangan backend service dan modul integrasi LMS-SIA.  
3. **Bulan 5-6**: Penyelesaian desain UI/UX dan pengujian usability.  
4. **Bulan 7**: Finalisasi dan integrasi semua komponen ke LMS.  
5. **Bulan 8**: Deployment dan pelatihan pengguna.  


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

