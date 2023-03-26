<template>
  <div>
    <div class="content__header content__boxed overlapping">
      <div class="content__wrap">
        <!-- Breadcrumb -->
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb mb-0">
            <li class="breadcrumb-item"><a href="/">Home</a></li>
            <li class="breadcrumb-item">
              <a href="/keperawatan">Keperawatan</a>
            </li>
            <li class="breadcrumb-item active" aria-current="page">
              Form Input
            </li>
          </ol>
        </nav>
        <!-- END : Breadcrumb -->

        <h1 class="page-title mb-2 mt-2">Form Input</h1>
      </div>
    </div>

    <div class="content__boxed">
      <div class="content__wrap">
        <div class="card">
          <!-- Custom style form wizard -->
          <div class="d-md-flex align-content-stretch">
            <div class="card-body flex-fill ms-md-4">
              <!-- Step progress -->
              <nav
                id="_dm-customWizardSteps"
                class="nav nav-callout justify-content-center flex-nowrap mt-3 mb-3"
              >
                <a
                  href="/keperawatan/create"
                  class="nav-link active"
                  data-step="account"
                >
                  <i class="d-block demo-pli-information fs-2 mb-2"></i>
                  <span>Data Keluarga</span>
                </a>

                <a
                  href="/keperawatan/step2"
                  class="nav-link"
                  data-step="profile"
                >
                  <i class="d-block demo-pli-male fs-2 mb-2"></i>
                  <span>Data Penjunjang</span>
                </a>

                <a
                  href="/keperawatan/step3"
                  class="nav-link"
                  data-step="address"
                >
                  <i class="d-block demo-pli-home fs-2 mb-2"></i>
                  <span>Pemeliharaan Kesehatan</span>
                </a>

                <a
                  href="/keperawatan/step4"
                  class="nav-link"
                  data-step="finish"
                >
                  <i class="d-block demo-pli-medal-2 fs-2 mb-2"></i>
                  <span>Hasil Pembinaan</span>
                </a>

                <!-- <a
                  href="/keperawatan/step5"
                  class="nav-link"
                  data-step="finish"
                >
                  <i class="d-block demo-pli-medal-2 fs-2 mb-2"></i>
                  <span>Individu yang Sakit</span>
                </a> -->
              </nav>
              <!-- END : Step progress -->

              <!-- Form sections -->
              <form id="_dm-customWizardForm" class="p-xl-3">
                <!-- Account section -->
                <section data-step="step-1">
                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Nama Kepala Keluarga</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Alamat Rumah</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Nomor Telepon</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Bahasa sehari-hari</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Agama</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Suku</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Jarak yankes terdekat</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Alat Transpostrasi</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <hr class="hr" />
                  <span class="fw-bold">Data Anggota Keluarga</span>
                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Nama</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Hubungan Dengan KK</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Umur</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >jenis Kelamin</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Suku</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Pendidikan Terakhir</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Pekerjaan Saat ini</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Status Gizi (TB, BB, BMI)</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >TTV (TD, N, S, P)</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >tatus Imunisasi Dasar
                        </label>
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Alat Bantu/ Protesa</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <hr class="hr" />
                  <span class="fw-bold">Lanjutan</span>
                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Nama</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Penampilan Umum</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Status Kesehatan Saat ini</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="alatTransportasi"
                          class="col-sm-4 p-xl-0 text-xl-end col-form-label"
                          >Riwayat Penyakit/ Alergi</label
                        >
                        <div class="col-sm-8">
                          <input
                            id="alatTransportasi"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label for="jarakYankes" class="col-sm-4 col-form-label"
                          >Analisis Masalah Kesehatan INDIVIDU
                        </label>
                        <div class="col-sm-8">
                          <input
                            id="jarakYankes"
                            class="form-control"
                            type="text"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>
                  <button
                    class="btn btn-info ms-auto d-flex justify-content-end mb-5"
                    type="button"
                  >
                    Simpan
                  </button>

                  <div class="pt-3 d-flex">
                    <nuxt-link
                      to="/keperawatan/step2"
                      data-next
                      class="btn btn-primary ms-auto"
                    >
                      Next
                    </nuxt-link>
                  </div>
                </section>
                <!-- END : Account section -->
              </form>
              <!-- END : Form sections -->
            </div>
          </div>
          <!-- END : Custom style form wizard -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'keperawatan-create',
}
</script>
