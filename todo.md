# AdaptiXLearn Website Development To-Do List

## I. General Website Elements & Setup

*   [ ] **Setup Project:** Initialize project structure (HTML, CSS, JS folders, etc.).
*   [ ] **Global Styling:**
    *   [ ] Define color palette, typography (fonts, sizes, weights).
    *   [ ] Implement responsive design breakpoints.
*   [ ] **Header:**
    *   [ ] Site Title/Logo: "AdaptiXLearn"
    *   [ ] Main Navigation Menu (links to Beranda, Tentang Sistem, Fitur Utama Sistem, Dataset & Publikasi, Simulasi Sistem, Evaluasi & Dokumentasi, Tim Pengembang, Kontak & Kolaborasi).
*   [ ] **Footer:**
    *   [ ] Copyright information (e.g., © [Year] AdaptiXLearn. All rights reserved.)
    *   [ ] Potentially quick links or contact info.
*   [ ] **Favicon:** Design and implement a favicon.
*   [ ] **SEO Basics:**
    *   [ ] Set up meta titles and descriptions for each page.
    *   [ ] Ensure proper heading structure (H1, H2, etc.).

## II. Page: / (Beranda - Homepage)

*   [ ] **Page Title:** AdaptiXLearn: Sistem Pembelajaran dengan Antarmuka Adaptif Berbasis Beban Kognitif
*   [ ] **Section 1: Ringkasan Sistem AUI dalam LMS**
    *   [ ] **Judul:** "AdaptiXLearn: Sistem Pembelajaran dengan Antarmuka Adaptif Berbasis Beban Kognitif"
    *   [ ] **Teks Paragraf:** "AdaptiXLearn adalah sebuah Learning Management System (LMS) adaptif yang dirancang untuk memberikan pengalaman belajar yang dipersonalisasi berdasarkan tingkat beban kognitif pengguna. Sistem ini menggunakan pendekatan multimodal cognitive load detection melalui data eye-gaze, perilaku interaksi pengguna, dan pelaporan subjektif. Dengan sistem AUI (Adaptive User Interface), tampilan dan struktur LMS akan beradaptasi secara dinamis untuk mendukung pembelajaran yang lebih nyaman."
*   [ ] **Section 2: Gambar/Fitur Unggulan**
    *   [ ] Implement a 3-column layout for features.
    *   [ ] **Fitur 1:**
        *   [ ] **[ICON PLACEHOLDER: Cognitive Load Icon]**
        *   [ ] **Judul Teks:** "Berbasis Cognitive Load"
        *   [ ] **Deskripsi Singkat:** "Deteksi beban kognitif dari data nyata pengguna"
    *   [ ] **Fitur 2:**
        *   [ ] **[ICON PLACEHOLDER: Adaptive/Responsive Icon]** (PDF shows a checkmark)
        *   [ ] **Judul Teks:** "Adaptif & Responsif"
        *   [ ] **Deskripsi Singkat:** "UI menyesuaikan berdasarkan kapasitas pengguna"
    *   [ ] **Fitur 3:**
        *   [ ] **[ICON PLACEHOLDER: Scientific Proof Icon]** (PDF shows a bar chart)
        *   [ ] **Judul Teks:** "Dibuktikan Secara Ilmiah"
        *   [ ] **Deskripsi Singkat:** "Evaluasi sistem menggunakan metode valid dan terpercaya"
*   [ ] **Section 3: CTA (Call to Action)**
    *   [ ] **Tombol/Link 1:** "Lihat Simulasi" (links to Simulasi Sistem page)
    *   [ ] **Tombol/Link 2:** "Unduh Publikasi" (links to Dataset & Publikasi page, or specific publication)

## III. Page: /tentang-sistem (Tentang Sistem)

*   [ ] **Page Title:** Tentang Sistem - AdaptiXLearn
*   [ ] **Section 1: Latar Belakang Pengembangan**
    *   [ ] **Teks Paragraf:** "Di era pembelajaran daring yang semakin kompleks, penggunaan Learning Management System (LMS) telah menjadi kebutuhan utama dalam menunjang proses pendidikan tinggi. Namun, kompleksitas antarmuka LMS justru seringkali meningkatkan beban kognitif pengguna—terutama ketika sistem tidak menyesuaikan dengan kapasitas belajar individu. Penelitian ini berangkat dari kebutuhan untuk mengembangkan LMS yang lebih cerdas dan adaptif, dengan mempertimbangkan kondisi psikologis dan kognitif pengguna selama proses belajar."
*   [ ] **Section 2: Teori Dasar**
    *   [ ] **Sub-judul:** (Optional, or integrate into text)
    *   [ ] **Teks Paragraf 1:** "Adaptive User Interface (AUI) adalah pendekatan yang memungkinkan antarmuka sistem berubah secara dinamis berdasarkan karakteristik pengguna. Dalam konteks LMS, AUI dapat menyesuaikan tampilan, struktur navigasi, atau konten yang ditampilkan berdasarkan:"
    *   [ ] **List (bullet points):**
        *   [ ] Beban Kognitif (Cognitive Load)
        *   [ ] Pengetahuan Awal (Prior Knowledge)
        *   [ ] Kapasitas Memori Kerja (Working Memory Capacity)
        *   [ ] Gaya Belajar (VARK: Visual, Auditory, Reading, Kinesthetic)
    *   [ ] **Teks Paragraf 2:** "Dengan pendekatan ini, sistem tidak lagi bersifat one-size-fits-all, tetapi memberikan pengalaman belajar yang dipersonalisasi."
    *   [ ] **Teks Paragraf 3:** "Pengembangan sistem ini menggunakan pendekatan berbasis teori dan riset yang kuat, antara lain:"
    *   [ ] **List (bullet points):**
        *   [ ] Cognitive Load Theory (Sweller, 1988)
        *   [ ] Multimodal Learning Analytics
        *   [ ] Rule-based Personalization
        *   [ ] Machine Learning untuk Klasifikasi Beban Kognitif
    *   [ ] **Teks Paragraf 4:** "Sistem ini juga mengacu pada praktik pengembangan sistem interaktif berbasis participatory design, dengan melibatkan pengguna dalam tahap evaluasi."
*   [ ] **Section 3: Tujuan & Manfaat**
    *   [ ] **Teks Paragraf:** "Sistem ini dikembangkan dengan tiga tujuan utama:"
    *   [ ] **List (numbered):**
        *   [ ] 1. Mendeteksi beban kognitif pengguna secara real-time menggunakan data multimodal (eye gaze, perilaku interaksi, kuesioner).
        *   [ ] 2. Mengadaptasi tampilan antarmuka LMS sesuai profil dan kondisi belajar pengguna.
        *   [ ] 3. Meningkatkan kenyamanan pembelajaran daring untuk mendukung ketercapaian tujuan pembelajaran, terutama dalam konteks perguruan tinggi.
*   [ ] **Section 4: Pengguna Sistem**
    *   [ ] **Teks Paragraf:** "Sistem ini dirancang untuk digunakan oleh:"
    *   [ ] **List (bullet points):**
        *   [ ] Mahasiswa jenjang S1 (terutama dalam eksperimen awal)
        *   [ ] Dosen sebagai fasilitator pembelajaran daring
        *   [ ] Peneliti bidang HCI, edukasi digital, dan cognitive science

## IV. Page: /fitur-utama (Fitur Utama Sistem)

*   [ ] **Page Title:** Fitur Utama Sistem - AdaptiXLearn
*   [ ] **Section 1: Deteksi Beban Kognitif Multimodal**
    *   [ ] **Teks Paragraf 1:** "Sistem ini mampu mengenali tingkat beban kognitif pengguna secara real-time melalui kombinasi tiga sumber data utama:"
    *   [ ] **List (bullet points):**
        *   [ ] Eye-Gaze Tracking: Analisis fixation, saccade, dan gaze transition entropy.
        *   [ ] User Interaction Behavior: Klik, navigasi, scroll, type.
        *   [ ] Self-Report Subjective Rating: Skor NASA-TLX yang diinput oleh pengguna (pada awal penggunaan).
    *   [ ] **Teks Paragraf 2:** "Dengan pendekatan ini, sistem menghasilkan klasifikasi beban kognitif (rendah, sedang, tinggi) yang menjadi dasar adaptasi antarmuka."
*   [ ] **Section 2: Adaptasi Antarmuka Pengguna (AUI)**
    *   [ ] **Teks Paragraf:** "Berdasarkan hasil deteksi beban kognitif dan karakteristik awal pengguna (misalnya gaya belajar dan kapasitas memori kerja), sistem akan menyesuaikan:"
    *   [ ] **List (bullet points):**
        *   [ ] Jumlah elemen yang ditampilkan
        *   [ ] Struktur navigasi dan alur pembelajaran
        *   [ ] Pemberian highlight atau penekanan informasi penting
        *   [ ] Penyederhanaan atau perluasan konten
*   [ ] **Section 3: Laporan & Umpan Balik Otomatis**
    *   [ ] **Teks Paragraf 1:** "Adaptasi dilakukan menggunakan pendekatan rule-based engine yang ditentukan dari user model. Setelah sesi belajar, sistem akan memberikan:"
    *   [ ] **List (bullet points):**
        *   [ ] Ringkasan kemajuan belajar
        *   [ ] Estimasi beban kognitif
        *   [ ] Rekomendasi untuk sesi berikutnya (misalnya waktu istirahat, materi pengayaan)
    *   [ ] **Teks Paragraf 2:** "Laporan ini tersedia untuk mahasiswa maupun dosen."

## V. Page: /dataset-publikasi (Dataset & Publikasi)

*   [ ] **Page Title:** Dataset & Publikasi - AdaptiXLearn
*   [ ] **Section 1: Publikasi Ilmiah**
    *   [ ] **Publikasi 1:**
        *   [ ] **Judul:** "Role, Methodology, and Measurement of Cognitive Load in Computer Science and Information Systems Research."
        *   [ ] **Penulis:** Mira Suryani, Harry Budi Santoso, Martin Schrepp, Rizal Fathoni Aji, Setiawan Hadi, Dana Indra Sensuse, Ryan Randy Suryono, Kautsarina.
        *   [ ] **Link Artikel:** [https://ieeexplore.ieee.org/document/10786995](https://ieeexplore.ieee.org/document/10786995)
    *   [ ] **Publikasi 2:**
        *   [ ] **Judul:** "An Initial User Model Design for Adaptive Interface Development in Learning Management System Based on Cognitive Load"
        *   [ ] **Penulis:** Mira Suryani, Dana Indra Sensuse, Harry Budi Santoso, Rizal Fathoni Aji, Setiawan Hadi, Ryan Randy Suryono, Kautsarina.
        *   [ ] **Link Artikel:** [https://link.springer.com/article/10.1007/s10111-024-00772-8](https://link.springer.com/article/10.1007/s10111-024-00772-8)
    *   [ ] **Publikasi 3:**
        *   [ ] **Judul:** "User Interaction Behavior Analysis for Cognitive Load Detection in Online Learning Processes."
        *   [ ] **Penulis:** Mira Suryani, Harry Budi Santoso, Rizal Fathoni Aji, Setiawan Hadi & Martin Schrepp
        *   [ ] **Link Artikel:** [https://link.springer.com/chapter/10.1007/978-3-031-93221-2_25](https://link.springer.com/chapter/10.1007/978-3-031-93221-2_25)
*   [ ] **Section 2: Dataset Penelitian**
    *   [ ] Implement a table or structured layout for dataset details.
    *   [ ] **Nama:** Dataset Beban Kognitif Multimodal
    *   [ ] **Bidang Penelitian:** Klasifikasi beban kognitif, analisis beban kognitif dalam pendidikan, analisis beban kognitif dalam interaksi manusia komputer
    *   [ ] **Format data:** Labeled data
    *   [ ] **Pengumpulan data:** "Dataset ini dikumpulkan melalui eksperimen pembelajaran daring menggunakan LMS yang telah dikembangkan secara khusus. Selama sesi pembelajaran (membaca, menonton, kuis, dan diskusi), data ditangkap secara real-time menggunakan teknologi eye-tracking berbasis webcam serta pencatatan perilaku interaksi pengguna. Setiap sesi diakhiri dengan pengisian kuesioner NASA-TLX untuk mengukur beban kognitif secara subjektif. Data kemudian diberi label ke dalam tiga tingkat beban kognitif: rendah, sedang, dan tinggi, berdasarkan hasil triangulasi antara data subjektif, perilaku, dan performa."
    *   [ ] **Klasifikasi Dataset:**
        *   [ ] **Teks:** "Dataset terbagi ke dalam 3 kategori: full set, eye gaze, dan interaction. Pada masing-masing kategori terdapat 4 file yang mengindikasikan aktivitas di LMS dengan struktur penamaan [kategori dataset]_[aktivitas]."
        *   [ ] **List (bullet points):**
            *   [ ] Full set: Full set_reading, Full set_watching, Full set_quiz, dan Full set_discussion.
            *   [ ] Eye Gaze: eye gaze_reading, eye gaze_watching, eye gaze_quiz, dan eye gaze_discussion
            *   [ ] Interaction: interaction_reading, interaction_watching, interaction_quiz, dan interaction _discussion.
    *   [ ] **Kolom:**
        *   [ ] **List (bullet points):**
            *   [ ] Full set (20-22 kolom): number_of_fixations, total_fixation_duration, number_of_saccades, mean_amplitude, median_amplitude, variance_amplitude, max_amplitude, mean_velocity, median_velocity, variance_velocity, max_velocity, gaze_transition_entropy, relative_gte, dynamic_gte, transition_diversity_index, total_transition, mouse clicks, scroll, key_presses, viewport_resize, input_choice_changes, cl_status.
            *   [ ] Eyegaze (17 kolom): number_of_fixations, total_fixation_duration, number_of_saccades, mean_amplitude, median_amplitude, variance_amplitude, max_amplitude, mean_velocity, median_velocity, variance_velocity, max_velocity, gaze_transition_entropy, relative_gte, dynamic_gte, transition_diversity_index, total_transition, cl_status.
            *   [ ] Interaction (4-6 kolom): mouse clicks, scroll, key_presses, viewport_resize, input_choice_changes, cl_status.
    *   [ ] **Jumlah Data:** Tiap subset mencakup 240 sampel, dengan total 720 baris di seluruh set data.
    *   [ ] **Lisensi:** CC BY-NC 4.0 (Creative Commons Attribution-NonCommercial 4.0)
    *   [ ] **Link Dataset:** [https://github.com/mirasuryani/cognitive_load_dataset](https://github.com/mirasuryani/cognitive_load_dataset) (This could be a button or a direct link)
*   [ ] **Section 3: Hak Cipta & Lisensi (Website/Sistem)**
    *   [ ] **Teks:** "Hak Cipta dari LMS AdaptiXLearn sedang dalam proses pendaftaran."

## VI. Page: /simulasi (Simulasi Sistem)

*   [ ] **Page Title:** Simulasi Sistem - AdaptiXLearn
*   [ ] **Section 1: Screenshot Antarmuka LMS dengan AUI**
    *   [ ] **Placeholder Teks:** "[Menyusul]" (Indicates content to be added later)
    *   [ ] **[IMAGE PLACEHOLDER: Screenshot of LMS with AUI]**
*   [ ] **Section 2: Link ke Sistem**
    *   [ ] **Teks:** "AdaptiXLearn dapat diakses pada: [https://edico.ibonk.id/](https://edico.ibonk.id/)" (Make this a clickable link)

## VII. Page: /evaluasi-dokumentasi (Evaluasi & Dokumentasi)

*   [ ] **Page Title:** Evaluasi & Dokumentasi - AdaptiXLearn
*   [ ] **Section 1: Metodologi Evaluasi**
    *   [ ] **Sub-judul:** (Independent T-test, SUS, dan UEQ+)
    *   [ ] **Teks Paragraf:** "Untuk menilai efektivitas sistem Adaptive User Interface (AUI) dalam LMS yang dikembangkan, penelitian ini menggunakan metode evaluasi kuantitatif yang mencakup pengujian statistik dan pengukuran persepsi pengguna. Evaluasi dilakukan dengan melibatkan dua kelompok: kelompok eksperimen (menggunakan LMS dengan AUI) dan kelompok kontrol (menggunakan LMS standar)."
*   [ ] **Section 2: Hasil Evaluasi**
    *   [ ] **Sub-judul:** (Grafik, Statistik Ringkas)
    *   [ ] **Placeholder Teks:** "[menyusul]"
    *   [ ] **[CONTENT PLACEHOLDER: Graphs and summary statistics of evaluation results]**
*   [ ] **Section 3: Dokumentasi Pengambilan Data**
    *   [ ] **[IMAGE GALLERY/CAROUSEL PLACEHOLDER: Multiple images showing data collection process]**
        *   [ ] [IMAGE PLACEHOLDER: data_collection_1.jpg]
        *   [ ] [IMAGE PLACEHOLDER: data_collection_2.jpg]
        *   [ ] [IMAGE PLACEHOLDER: data_collection_3.jpg]
        *   [ ] [IMAGE PLACEHOLDER: data_collection_4.jpg]
        *   [ ] [IMAGE PLACEHOLDER: data_collection_5.jpg]
*   [ ] **Section 4: Feedback / Testimoni Pengguna**
    *   [ ] **Placeholder Teks:** "[menyusul]"
    *   [ ] **[CONTENT PLACEHOLDER: User feedback and testimonials]**

## VIII. Page: /tim-pengembang (Tim Pengembang)

*   [ ] **Page Title:** Tim Pengembang - AdaptiXLearn
*   [ ] **Section 1: Profil Peneliti** (Create a card/section for each researcher)
    *   [ ] **Peneliti 1: Mira Suryani**
        *   [ ] **[IMAGE PLACEHOLDER: Photo of Mira Suryani]**
        *   [ ] **Nama:** Mira Suryani, S.Pd., M.Kom.
        *   [ ] **Email:** mira.suryani11@ui.ac.id / mira.suryani@unpad.ac.id
        *   [ ] **SCOPUS ID:** 56118930500
        *   [ ] **ORCID ID:** [https://orcid.org/0000-0002-3259-0282](https://orcid.org/0000-0002-3259-0282)
    *   [ ] **Peneliti 2: Prof. Harry Budi Santoso**
        *   [ ] **[IMAGE PLACEHOLDER: Photo of Prof. Harry Budi Santoso]**
        *   [ ] **Nama:** Prof. Harry Budi Santoso, S.Kom., M.Kom, Ph.D.
        *   [ ] **Email:** harrybs@cs.ui.ac.id
        *   [ ] **SCOPUS ID:** 55396730800
        *   [ ] **ORCID ID:** [https://orcid.org/0000-0003-0459-0493](https://orcid.org/0000-0003-0459-0493)
    *   [ ] **Peneliti 3: Dr. Rizal Fathoni Aji**
        *   [ ] **[IMAGE PLACEHOLDER: Photo of Dr. Rizal Fathoni Aji]**
        *   [ ] **Nama:** Dr. Rizal Fathoni Aji, S.Kom., M.Kom.
        *   [ ] **Email:** rizal@cs.ui.ac.id
        *   [ ] **SCOPUS ID:** 55089397700
    *   [ ] **Peneliti 4: Dr. Drs. Setiawan Hadi**
        *   [ ] **[IMAGE PLACEHOLDER: Photo of Dr. Drs. Setiawan Hadi]**
        *   [ ] **Nama:** Dr. Drs. Setiawan Hadi, M.Sc., CS.
        *   [ ] **Email:** setiawanhadi@unpad.ac.id
        *   [ ] **SCOPUS ID:** 7006070850
        *   [ ] **ORCID ID:** [https://orcid.org/0000-0002-2929-5979](https://orcid.org/0000-0002-2929-5979)
    *   [ ] **Peneliti 5: Dr. Martin Schrepp**
        *   [ ] **[IMAGE PLACEHOLDER: Photo of Dr. Martin Schrepp]**
        *   [ ] **Nama:** Dr. Martin Schrepp
        *   [ ] **SCOPUS ID:** 22434417500
*   [ ] **Section 2: Afiliasi Institusi / Lab**
    *   [ ] **Afiliasi 1:**
        *   [ ] **[LOGO PLACEHOLDER: Universitas Padjadjaran / HCI & Learning Tech Lab Logo]**
        *   [ ] **Nama Lab:** Human-Computer Interaction & Learning Technology Laboratory
        *   [ ] **Institusi:** Fakultas Matematika dan Ilmu Pengetahuan Alam, Universitas Padjadjaran
    *   [ ] **Afiliasi 2:**
        *   [ ] **[LOGO PLACEHOLDER: Universitas Indonesia / Digital Library & Distance Learning Lab Logo]**
        *   [ ] **Nama Lab:** Digital Library and Distance Learning Laboratory
        *   [ ] **Institusi:** Fakultas Ilmu Komputer, Universitas Indonesia

## IX. Page: /kontak (Kontak & Kolaborasi)

*   [ ] **Page Title:** Kontak & Kolaborasi - AdaptiXLearn
*   [ ] **Section 1: Formulir Kontak**
    *   [ ] **[FEATURE PLACEHOLDER: Implement a contact form (Name, Email, Subject, Message, Send Button)]**
*   [ ] **Section 2: Alamat Email & Sosial Media**
    *   [ ] **Email Peneliti Utama:** Mira Suryani (mira.suryani11@ui.ac.id)
    *   [ ] **LinkedIn:** [https://www.linkedin.com/in/mira-suryani/](https://www.linkedin.com/in/mira-suryani/)
    *   [ ] **[PLACEHOLDER: Add other relevant social media links if available]**