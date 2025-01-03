<template>
  <div class="container-fluid">
  <!-- Header -->
      <div class="row">
        <div class="col-lg-12">
          <h4 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Kompetensi Keahlian <b>SMKN 4 TASIKMALAYA</b>
          </h4>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-5 p-1 m-5 text-secondary">
            <NuxtLink to="/pages/kurikulum/kompetensi-keahlian" class="text-decoration-none">Kurikulum</NuxtLink> / Kompetensi Keahlian
          </p>
        </div>
      </div>

      <!-- Kartu Kompetensi Keahlian -->
      <div class="row d-flex justify-content-center">
        <!-- Kartu 1 -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="card shadow-sm text-center" style="width: 100%;">
            <div class="icon-container mx-auto mt-3">
              <img src="/assets/dkv.jpg" class="card-icon" alt="Icon Kompetensi 1" style="width: 100%;">
            </div>
            <div class="card-body">
              <h5 class="card-title text-center">DKV</h5>
              <p class="card-text">
                Jurusan Desain Komunikasi Visual atau DKV adalah bagian dari ilmu desain yang mempelajari tentang konsep komunikasi dan ungkapan kreatif, dengan memanfaatkan elemen visual untuk menyampaikan pesan dengan tujuan tertentu. Karena unsur pesan memiliki peran yang sangat penting, lulusan jurusan DKV diharapkan mampu mengeloah pesan tersebut menjadi sesuatu yang menarik, informatif, dan komunikatif, sehingga bisa disampaikan secara efektif.
              </p>
            </div>
          </div>
        </div>

        <!-- Kartu 2 -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="card shadow-sm text-center" style="width: 100%;">
            <div class="icon-container mx-auto mt-3">
              <img src="/assets/PPLG.jpg" class="card-icon" alt="Icon Kompetensi 2" style="width: 100%;">
            </div>
            <div class="card-body">
              <h5 class="card-title text-center">PPLG</h5>
              <p class="card-text">
                Rekayasa Perangkat Lunak (RPL, atau dalam bahasa Inggris: Software Engineering atau SE) adalah satu bidang profesi yang mendalami cara-cara pengembangan perangkat lunak termasuk pembuatan, pemeliharaan, manajemen organisasi pengembangan perangkat lunak dan manajemen kualitas.

IEEE Computer Society mendefinisikan rekayasa perangkat lunak sebagai penerapan suatu pendekatan yang sistematis, disiplin dan terkuantifikasi atas pengembangan, penggunaan dan pemeliharaan perangkat lunak, serta studi atas pendekatan-pendekatan ini, yaitu penerapan pendekatan engineering atas perangkat lunak.[1]

Rekayasa perangkat lunak adalah pengubahan perangkat lunak itu sendiri guna mengembangkan, memelihara, dan membangun kembali dengan menggunakan prinsip rekayasa untuk menghasilkan perangkat lunak yang dapat bekerja lebih efisien dan efektif untuk pengguna.
              </p>
            </div>
          </div>
        </div>

        <!-- Kartu 3 -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="card shadow-sm text-center" style="width: 100%;">
            <div class="icon-container mx-auto mt-3">
              <img src="/assets/TKJ.jpg" class="card-icon" alt="Icon Kompetensi 3" style="width: 100%;">
            </div>
            <div class="card-body">
              <h5 class="card-title text-center">TJKT</h5>
              <p class="card-text">
                Teknik Komputer dan Jaringan merupakan ilmu berbasis Teknologi Informasi dan Komunikasi terkait kemampuan algoritma, dan pemrograman komputer, perakitan komputer, perakitan jaringan komputer, dan pengoperasian perangkat lunak, dan internet. Teknik komputer, dan jaringan juga membutuhkan pemahaman di bidang teknik listrik, dan ilmu komputer sehingga mampu mengembangkan, dan mengintegrasikan perangkat lunak, dan perangkat keras.
              </p>
            </div>
          </div>
        </div>

        <!-- Kartu 4 -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="card shadow-sm text-center" style="width: 100%;">
            <div class="icon-container mx-auto mt-3">
              <img src="/assets/TOI.jpg" class="card-icon" alt="Icon Kompetensi 4" style="width: 100%;">
            </div>
            <div class="card-body">
              <h5 class="card-title text-center">TOI</h5>
              <p class="card-text">
                Teknik Otomasi Industri adalah sebuah bidang teknik yang mempelajari tentang perakitan sistem-sistem di dunia industri yang berbasis otomatis. Otomasi sendiri biasanya digunakan untuk mengendalikan mesin-mesin industri dan kontrol proses untuk menggantikan operator tenaga manusia.
              </p>
            </div>
          </div>
        </div>

        <!-- Kartu 5 -->
        <div class="col-lg-4 col-md-6 mb-4">
          <div class="card shadow-sm text-center" style="width: 100%;">
            <div class="icon-container mx-auto mt-3">
              <img src="/assets/TBSM.jpg" class="card-icon" alt="Icon Kompetensi 5" style="width: 100%;">
            </div>
            <div class="card-body">
              <h5 class="card-title text-center">TBSM</h5>
              <p class="card-text">
                Teknik dan Bisnis Sepeda Motor adalah kompetensi keahlian pada Bidang Studi Keahlian Teknologi dan Rekayasa Program Studi Keahlian Teknik Otomotif yang menekankan pada keterampilan pelayanan jasa mekanik kendaraan sepeda motor roda dua. Kompetensi Keahlian Teknik dan Bisnis Sepeda Motor menyiapkan peserta didik untuk bekerja pada bidang pekerjaan yang dikelola oleh badan, instansi atau perusahaan maupun pribadi (wirausaha).
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {};
</script>

<style>
/* Mengatur gaya untuk gambar agar terlihat seperti ikon */
.card-icon {
  width: 80px;
  height: 80px;
  border-radius: 50%; /* Membuat gambar berbentuk lingkaran */
  object-fit: cover;
  border: 2px solid #ddd; /* Menambahkan border untuk estetika */
}

.icon-container {
  width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f9f9f9; /* Warna latar belakang untuk ikon */
  border-radius: 50%;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}

.card {
  border-radius: 10px;
}

.card-body {
  text-align: justify;
}

.shadow-sm {
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
