# Practice-SMK-Gyokai
This website was created to test coding, the people who created this website were students studying at Gyo Vocational School

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  
  <h1><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMK Gyokai Indonesia</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            background: linear-gradient(270deg, #4facfe, #00f2fe, #000, #000);
            background-size: 800% 800%;
            animation: gradientBG 15s ease infinite;
            font-size: 0.50rem; /* font kecil & rapi */
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        header {
            text-align: center;
            padding: 20px;
            background: rgba(0,0,0,0.3);
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 1.8rem;
            font-weight: 700;
        }
        .marquee {
            background: rgba(0,0,0,0.5);
            overflow: hidden;
            white-space: nowrap;
        }
        .marquee span {
            display: inline-block;
            padding-left: 100%;
            animation: marquee 25s linear infinite;
            font-size: 0.8rem;
        }
        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-100%); }
        }
        main {
            max-width: 900px;
            margin: 30px auto;
            background: rgba(0,0,0,0.4);
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }
        h2 {
            border-bottom: 2px solid rgba(255,255,255,0.5);
            padding-bottom: 5px;
            margin-top: 25px;
            font-size: 1.2rem;
        }
        p {
            line-height: 1.6;
            text-align: justify;
        }
        ul {
            margin: 10px 0 20px 20px;
        }
        .timeline {
            list-style: none;
            padding: 0;
        }
        .timeline li {
            background: rgba(255,255,255,0.1);
            margin-bottom: 10px;
            padding: 10px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: rgba(0,0,0,0.5);
            font-size: 0.8rem;
        }
    </style>
</head>
<body>

<header>
    <h1>SMK Gyokai Indonesia</h1>
    <div class="marquee">
        <span>
            SMK Gyokai — Berlokasi di Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang. Jurusan unggulan: TKJ, DKV, Perhotelan, Manajemen Perkantoran & Layanan Bisnis, Teknik Mesin Industri, dan Bisnis Digital. Mengusung prinsip Integritas, Profesionalisme, Kedisiplinan, Kreativitas, Kerja Sama, dan Pengabdian untuk mencetak lulusan kompeten dan berkarakter.
        </span>
    </div>
</header>

<main>
    <h2>Tentang SMK Gyokai</h2>
    <p>
        SMK Gyokai adalah sekolah kejuruan yang berlokasi di <strong>Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang</strong>. 
        Sekolah ini hadir untuk menjawab kebutuhan dunia kerja dengan pembelajaran berbasis praktik yang terintegrasi dengan teori. 
        Didukung fasilitas modern dan pendidik berpengalaman, SMK Gyokai berfokus menyiapkan siswa yang kompeten, berkarakter, dan adaptif terhadap perkembangan teknologi.
    </p>
    <p>
        Dengan kepemimpinan kepala sekolah yang visioner serta dukungan yayasan dan mitra industri, SMK Gyokai aktif membangun ekosistem vokasi yang kuat: 
        kurikulum berbasis proyek, sertifikasi kompetensi, dan program PKL di perusahaan sekitar Tangerang dan Banten, sehingga lulusan memiliki portofolio nyata dan jejaring profesional sejak dini.
    </p>

    <h2>Sejarah Singkat</h2>
    <ul class="timeline">
        <li><strong>Pendirian di Cisoka, Jeungjing</strong> — SMK Gyokai berdiri dan mulai beroperasi di Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang, dengan fokus pada pendidikan vokasi yang dekat dengan kebutuhan industri lokal.</li>
        <li><strong>Pengembangan Program Keahlian</strong> — Penambahan dan penyesuaian jurusan sesuai potensi daerah: Desain Komunikasi Visual (DKV), Manajemen Perkantoran & Layanan Bisnis, Teknik Mesin Industri, serta Bisnis Digital di samping TKJ dan Perhotelan.</li>
        <li><strong>Kemitraan DU/DI Tangerang & Banten</strong> — Penguatan kerja sama dengan dunia usaha dan industri (DU/DI) wilayah Tangerang Raya dan Banten untuk PKL, proyek bersama, hingga rekrutmen lulusan.</li>
        <li><strong>Modernisasi Fasilitas</strong> — Peningkatan laboratorium TKJ, studio DKV, bengkel Teknik Mesin Industri, dan ruang praktik perhotelan untuk menunjang pembelajaran berbasis praktik.</li>
        <li><strong>Kurikulum Berbasis Proyek</strong> — Implementasi pembelajaran kolaboratif dan proyek lintas mata pelajaran, serta fasilitasi sertifikasi kompetensi yang diakui industri.</li>
        <li><strong>Prestasi Berkelanjutan</strong> — Pencapaian akademik dan non-akademik tingkat kabupaten/kota hingga provinsi, serta partisipasi aktif dalam lomba dan pelatihan vokasi.</li>
    </ul>

    <h2>Visi</h2>
    <p>
        Menjadi sekolah kejuruan unggul di Kabupaten Tangerang yang menghasilkan lulusan kompeten, berkarakter, dan berdaya saing global, berbasis integritas, profesionalisme, dan kemitraan industri.
    </p>

    <h2>Misi</h2>
    <ul>
        <li>Menyelenggarakan pendidikan vokasi yang relevan dengan kebutuhan industri Tangerang, Banten, dan nasional.</li>
        <li>Membentuk lulusan siap kerja, kreatif, serta adaptif terhadap perubahan teknologi.</li>
        <li>Meningkatkan kolaborasi berkelanjutan dengan DU/DI untuk PKL, magang, dan rekrutmen.</li>
        <li>Mengembangkan karakter: integritas, disiplin, tanggung jawab, dan etos kerja tinggi.</li>
        <li>Mendorong kewirausahaan melalui proyek bisnis dan inkubasi produk/jasa siswa.</li>
    </ul>

    <h2>Jurusan Unggulan</h2>
    <ul>
        <li><strong>Teknik Komputer dan Jaringan (TKJ)</strong> — Jaringan, perangkat keras, administrasi sistem, dasar keamanan siber.</li>
        <li><strong>Desain Komunikasi Visual (DKV)</strong> — Desain grafis, ilustrasi, branding, konten media digital.</li>
        <li><strong>Perhotelan</strong> — Front office, tata boga dasar, layanan kamar, dan hospitality.</li>
        <li><strong>Manajemen Perkantoran dan Layanan Bisnis</strong> — Administrasi, layanan pelanggan, pengelolaan dokumen & perkantoran modern.</li>
        <li><strong>Teknik Mesin Industri</strong> — Dasar perancangan, perakitan, perawatan, dan pengoperasian mesin industri.</li>
        <li><strong>Bisnis Digital</strong> — Pemasaran digital, e-commerce, analitik dasar, dan strategi konten.</li>
    </ul>

    <h2>Prinsip SMK Gyokai</h2>
    <ul>
        <li><strong>Integritas</strong> — Kejujuran dan etika dalam setiap proses.</li>
        <li><strong>Profesionalisme</strong> — Kualitas kerja, ketepatan waktu, dan tanggung jawab.</li>
        <li><strong>Kedisiplinan</strong> — Tertib aturan dan manajemen waktu.</li>
        <li><strong>Kreativitas</strong> — Inovasi dan pemecahan masalah.</li>
        <li><strong>Kerja Sama</strong> — Kolaborasi lintas jurusan & industri.</li>
        <li><strong>Pengabdian</strong> — Kontribusi nyata bagi masyarakat sekitar.</li>
    </ul>

    <h2>Tujuan SMK Gyokai</h2>
    <ul>
        <li>Menyiapkan siswa kompeten sesuai standar industri.</li>
        <li>Menumbuhkan jiwa wirausaha dan kemandirian.</li>
        <li>Meningkatkan literasi teknologi dan digital.</li>
        <li>Membentuk karakter positif dan etos kerja tinggi.</li>
        <li>Memberikan pengalaman kerja nyata (PKL & proyek industri).</li>
        <li>Membangun kemitraan strategis dengan DU/DI wilayah Tangerang dan sekitarnya.</li>
    </ul>

    <h2>Prestasi & Kerja Sama</h2>
    <p>
        SMK Gyokai aktif mengikuti kompetisi vokasi, kegiatan pengembangan keahlian, dan pelatihan bersama mitra. 
        Jaringan kerja sama yang luas di wilayah Tangerang dan Banten membuka akses magang, sertifikasi, serta peluang kerja bagi lulusan.
    </p>
</main>

<footer>
    &copy; 2025 SMK Gyokai | Dibuat oleh <strong>Rofi Althof</strong> — Jurusan Bisnis Digital
</footer>

</body>
</html></h1>

<h2><!DOCTYPE html>
<html>
<head>
 
</html></h2>
  
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  
  <h1><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMK Gyokai Indonesia</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            background: linear-gradient(270deg, #4facfe, #00f2fe, #000, #000);
            background-size: 800% 800%;
            animation: gradientBG 15s ease infinite;
            font-size: 0.50rem; /* font kecil & rapi */
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        header {
            text-align: center;
            padding: 20px;
            background: rgba(0,0,0,0.3);
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }
        header h1 {
            margin: 0;
            font-size: 1.8rem;
            font-weight: 700;
        }
        .marquee {
            background: rgba(0,0,0,0.5);
            overflow: hidden;
            white-space: nowrap;
        }
        .marquee span {
            display: inline-block;
            padding-left: 100%;
            animation: marquee 25s linear infinite;
            font-size: 0.8rem;
        }
        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-100%); }
        }
        main {
            max-width: 900px;
            margin: 30px auto;
            background: rgba(0,0,0,0.4);
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }
        h2 {
            border-bottom: 2px solid rgba(255,255,255,0.5);
            padding-bottom: 5px;
            margin-top: 25px;
            font-size: 1.2rem;
        }
        p {
            line-height: 1.6;
            text-align: justify;
        }
        ul {
            margin: 10px 0 20px 20px;
        }
        .timeline {
            list-style: none;
            padding: 0;
        }
        .timeline li {
            background: rgba(255,255,255,0.1);
            margin-bottom: 10px;
            padding: 10px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: rgba(0,0,0,0.5);
            font-size: 0.8rem;
        }
    </style>
</head>
<body>

<header>
    <h1>SMK Gyokai Indonesia</h1>
    <div class="marquee">
        <span>
            SMK Gyokai — Berlokasi di Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang. Jurusan unggulan: TKJ, DKV, Perhotelan, Manajemen Perkantoran & Layanan Bisnis, Teknik Mesin Industri, dan Bisnis Digital. Mengusung prinsip Integritas, Profesionalisme, Kedisiplinan, Kreativitas, Kerja Sama, dan Pengabdian untuk mencetak lulusan kompeten dan berkarakter.
        </span>
    </div>
</header>

<main>
    <h2>Tentang SMK Gyokai</h2>
    <p>
        SMK Gyokai adalah sekolah kejuruan yang berlokasi di <strong>Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang</strong>. 
        Sekolah ini hadir untuk menjawab kebutuhan dunia kerja dengan pembelajaran berbasis praktik yang terintegrasi dengan teori. 
        Didukung fasilitas modern dan pendidik berpengalaman, SMK Gyokai berfokus menyiapkan siswa yang kompeten, berkarakter, dan adaptif terhadap perkembangan teknologi.
    </p>
    <p>
        Dengan kepemimpinan kepala sekolah yang visioner serta dukungan yayasan dan mitra industri, SMK Gyokai aktif membangun ekosistem vokasi yang kuat: 
        kurikulum berbasis proyek, sertifikasi kompetensi, dan program PKL di perusahaan sekitar Tangerang dan Banten, sehingga lulusan memiliki portofolio nyata dan jejaring profesional sejak dini.
    </p>

    <h2>Sejarah Singkat</h2>
    <ul class="timeline">
        <li><strong>Pendirian di Cisoka, Jeungjing</strong> — SMK Gyokai berdiri dan mulai beroperasi di Kecamatan Cisoka, Desa Jeungjing, Kabupaten Tangerang, dengan fokus pada pendidikan vokasi yang dekat dengan kebutuhan industri lokal.</li>
        <li><strong>Pengembangan Program Keahlian</strong> — Penambahan dan penyesuaian jurusan sesuai potensi daerah: Desain Komunikasi Visual (DKV), Manajemen Perkantoran & Layanan Bisnis, Teknik Mesin Industri, serta Bisnis Digital di samping TKJ dan Perhotelan.</li>
        <li><strong>Kemitraan DU/DI Tangerang & Banten</strong> — Penguatan kerja sama dengan dunia usaha dan industri (DU/DI) wilayah Tangerang Raya dan Banten untuk PKL, proyek bersama, hingga rekrutmen lulusan.</li>
        <li><strong>Modernisasi Fasilitas</strong> — Peningkatan laboratorium TKJ, studio DKV, bengkel Teknik Mesin Industri, dan ruang praktik perhotelan untuk menunjang pembelajaran berbasis praktik.</li>
        <li><strong>Kurikulum Berbasis Proyek</strong> — Implementasi pembelajaran kolaboratif dan proyek lintas mata pelajaran, serta fasilitasi sertifikasi kompetensi yang diakui industri.</li>
        <li><strong>Prestasi Berkelanjutan</strong> — Pencapaian akademik dan non-akademik tingkat kabupaten/kota hingga provinsi, serta partisipasi aktif dalam lomba dan pelatihan vokasi.</li>
    </ul>

    <h2>Visi</h2>
    <p>
        Menjadi sekolah kejuruan unggul di Kabupaten Tangerang yang menghasilkan lulusan kompeten, berkarakter, dan berdaya saing global, berbasis integritas, profesionalisme, dan kemitraan industri.
    </p>

    <h2>Misi</h2>
    <ul>
        <li>Menyelenggarakan pendidikan vokasi yang relevan dengan kebutuhan industri Tangerang, Banten, dan nasional.</li>
        <li>Membentuk lulusan siap kerja, kreatif, serta adaptif terhadap perubahan teknologi.</li>
        <li>Meningkatkan kolaborasi berkelanjutan dengan DU/DI untuk PKL, magang, dan rekrutmen.</li>
        <li>Mengembangkan karakter: integritas, disiplin, tanggung jawab, dan etos kerja tinggi.</li>
        <li>Mendorong kewirausahaan melalui proyek bisnis dan inkubasi produk/jasa siswa.</li>
    </ul>

    <h2>Jurusan Unggulan</h2>
    <ul>
        <li><strong>Teknik Komputer dan Jaringan (TKJ)</strong> — Jaringan, perangkat keras, administrasi sistem, dasar keamanan siber.</li>
        <li><strong>Desain Komunikasi Visual (DKV)</strong> — Desain grafis, ilustrasi, branding, konten media digital.</li>
        <li><strong>Perhotelan</strong> — Front office, tata boga dasar, layanan kamar, dan hospitality.</li>
        <li><strong>Manajemen Perkantoran dan Layanan Bisnis</strong> — Administrasi, layanan pelanggan, pengelolaan dokumen & perkantoran modern.</li>
        <li><strong>Teknik Mesin Industri</strong> — Dasar perancangan, perakitan, perawatan, dan pengoperasian mesin industri.</li>
        <li><strong>Bisnis Digital</strong> — Pemasaran digital, e-commerce, analitik dasar, dan strategi konten.</li>
    </ul>

    <h2>Prinsip SMK Gyokai</h2>
    <ul>
        <li><strong>Integritas</strong> — Kejujuran dan etika dalam setiap proses.</li>
        <li><strong>Profesionalisme</strong> — Kualitas kerja, ketepatan waktu, dan tanggung jawab.</li>
        <li><strong>Kedisiplinan</strong> — Tertib aturan dan manajemen waktu.</li>
        <li><strong>Kreativitas</strong> — Inovasi dan pemecahan masalah.</li>
        <li><strong>Kerja Sama</strong> — Kolaborasi lintas jurusan & industri.</li>
        <li><strong>Pengabdian</strong> — Kontribusi nyata bagi masyarakat sekitar.</li>
    </ul>

    <h2>Tujuan SMK Gyokai</h2>
    <ul>
        <li>Menyiapkan siswa kompeten sesuai standar industri.</li>
        <li>Menumbuhkan jiwa wirausaha dan kemandirian.</li>
        <li>Meningkatkan literasi teknologi dan digital.</li>
        <li>Membentuk karakter positif dan etos kerja tinggi.</li>
        <li>Memberikan pengalaman kerja nyata (PKL & proyek industri).</li>
        <li>Membangun kemitraan strategis dengan DU/DI wilayah Tangerang dan sekitarnya.</li>
    </ul>

    <h2>Prestasi & Kerja Sama</h2>
    <p>
        SMK Gyokai aktif mengikuti kompetisi vokasi, kegiatan pengembangan keahlian, dan pelatihan bersama mitra. 
        Jaringan kerja sama yang luas di wilayah Tangerang dan Banten membuka akses magang, sertifikasi, serta peluang kerja bagi lulusan.
    </p>
</main>

<footer>
    &copy; 2025 SMK Gyokai | Dibuat oleh <strong>Rofi Althof</strong> — Jurusan Bisnis Digital
</footer>

</body>
</html></h1>

<h2><!DOCTYPE html>
<html>
<head>
 
</html></h2>
  
</body>
</html>
