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
                  class="nav-link"
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
                  <span>Data Penunjang</span>
                </a>

                <a
                  href="/keperawatan/step3"
                  class="nav-link active"
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
              </nav>
              <!-- END : Step progress -->

              <!-- Form sections -->
              <form id="_dm-customWizardForm" class="p-xl-3">
                <!-- Account section -->
                <section data-step="account">
                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Adakah perhatian keluarga kepada anggotanya yang
                          menderita sakit
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Alasan"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                        >
                          Apakah keluarga mengetahui masalah kesehatan yang
                          dialami anggota dalam keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mengetahui penyebab masalah kesehatan
                          yang dialami anggota dalam keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mengetahui tanda dan gejala masalah
                          kesehatan yang dialami anggota dalam keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mengetahui akibat masalah kesehatan
                          yang dialami anggota dalam keluarganya bila tidak
                          diobati/dirawat
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Pada siapa keluarga biasa menggali informasi tentang
                          masalah kesehatan yang dialami anggota keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Keluarga</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tetangga</label
                            >
                          </div>
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Kader</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tenaga Kesehatan</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Yaitu ..."
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Keyakinan keluarga tentang masalah kesehatan yang
                          dialami anggota keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Tidak perlu ditangani karena akan sembuh sendiri
                              biasanya</label
                            >
                          </div>

                          <div class="form-check">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Perlu berobat ke fasilitas yankes</label
                            >
                          </div>
                          <div class="form-check">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak terpikir
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga melakukan upaya peningkatan kesehatan
                          yang dialami anggota keluarganya secara aktif
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mengetahui kebutuhan pengobatan
                          masalah kesehatan yang dialami yang dialami anggota
                          keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga dapat melakukan cara merawat anggota
                          keluarga dengan masalah kesehatan yang dialaminya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                        >
                          Apakah keluarga dapat melakukan pencegahan masalah
                          kesehatan yang dialami anggota keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mampu memelihara atau memodifikasi
                          lingkungan yang mendukung kesehatan anggota keluarga
                          yang mengalami masalah kesehatan
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Apakah keluarga mampu menggali dan memanfaatkan
                          sumber di masyarakat untuk mengatasi masalah kesehatan
                          anggota keluarganya
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio2"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label
                              for="_dm-inlineRadio2"
                              class="form-check-label"
                              >Ya</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id="_dm-inlineRadio3"
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label
                              for="_dm-inlineRadio3"
                              class="form-check-label"
                              >Tidak</label
                            >
                          </div>
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder="Jelaskan"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="pt-3 d-flex gap-2">
                    <nuxt-link
                      to="/keperawatan/step2"
                      class="btn btn-light ms-auto"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link to="/keperawatan/step4" class="btn btn-primary"
                      >Next</nuxt-link
                    >
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
