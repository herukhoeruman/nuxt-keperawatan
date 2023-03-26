<template>
  <div>
    <div class="content__header content__boxed overlapping">
      <div class="content__wrap">
        <!-- Breadcrumb -->
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb mb-0">
            <li class="breadcrumb-item"><nuxt-link to="/">Home</nuxt-link></li>
            <li class="breadcrumb-item active" aria-current="page">
              Pengkajian individu yang sakit
            </li>
          </ol>
        </nav>
        <!-- END : Breadcrumb -->

        <h1 class="page-title mb-3 mt-2">Pengkajian Individu yang Sakit</h1>
      </div>
    </div>

    <div class="content__boxed">
      <div class="content__wrap">
        <div class="card">
          <!-- Custom style form wizard -->
          <div class="d-md-flex align-content-stretch">
            <div class="card-body flex-fill ms-md-4">
              <nav
                id="_dm-customWizardSteps"
                class="nav nav-callout justify-content-center flex-nowrap mt-3 mb-3"
              >
                <a
                  href="/individu-sakit/step1"
                  class="nav-link"
                  data-step="account"
                >
                  <span>Keadaan Umum</span>
                </a>

                <a
                  href="/individu-sakit/step2"
                  class="nav-link"
                  data-step="profile"
                >
                  <span>Sirkulasi/ Cairan</span>
                </a>

                <a
                  href="/individu-sakit/step3"
                  class="nav-link"
                  data-step="address"
                >
                  <span>Perkemihan</span>
                </a>

                <a
                  href="/individu-sakit/step4"
                  class="nav-link"
                  data-step="finish"
                >
                  <span>Pernafasan</span>
                </a>
                <a
                  href="/individu-sakit/step5"
                  class="nav-link active"
                  data-step="finish"
                >
                  <span>Pencernaan</span>
                </a>
                <a
                  href="/individu-sakit/step6"
                  class="nav-link"
                  data-step="finish"
                >
                  <span>Muskuloskeletal </span>
                </a>
                <a
                  href="/individu-sakit/step7"
                  class="nav-link"
                  data-step="finish"
                >
                  <span>Neurosensori</span>
                </a>
              </nav>

              <!-- Form sections -->
              <form id="_dm-customWizardForm" class="p-xl-3">
                <!-- Account section -->
                <section data-step="account">
                  <span class="fw-bold">Pencernaan</span>
                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Mual </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Muntah </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Kembung </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Nafsu makan
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label"
                              >Berkurang</label
                            >
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Sulit menelan
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Disphagia
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Bau Nafas
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Kerusakan
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Gigi</label>
                          </div>

                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Gusi</label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Lidah</label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Geraham</label
                            >
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Rahang</label
                            >
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="checkbox"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Palatum</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Distensi Abdomen
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Bising Usus
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Konstipasi
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Diare </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder="...x/hr"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Hemoroid
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder="grade"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Teraba Masa abdomen
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Stomatitis
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Warna </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Riwayat obat pencahar
                        </label>
                        <div class="col-sm-8">
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"> Maag </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Konsistensi
                        </label>
                        <div class="col-sm-8">
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Diet Khusus
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Kebiasaan makan-minum
                        </label>
                        <div class="form-check form-check-inline">
                          <input
                            id=""
                            class="form-check-input"
                            type="radio"
                            name="inlineRadioOptions"
                            value="option2"
                          />
                          <label for="" class="form-check-label"
                            >Mandiri
                          </label>
                        </div>

                        <div class="form-check form-check-inline">
                          <input
                            id=""
                            class="form-check-input"
                            type="radio"
                            name="inlineRadioOptions"
                            value="option3"
                          />
                          <label for="" class="form-check-label"
                            >Bantu sebagian
                          </label>
                        </div>
                        <div class="form-check form-check-inline">
                          <input
                            id=""
                            class="form-check-input"
                            type="radio"
                            name="inlineRadioOptions"
                            value="option3"
                          />
                          <label for="" class="form-check-label">
                            Tergantung</label
                          >
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Alergi makanan/minuman
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya</label>
                          </div>

                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label">Tidak</label>
                          </div>
                          <input
                            class="form-control"
                            type="text"
                            placeholder=" "
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Alat bantu
                        </label>
                        <div class="form-check form-check-inline">
                          <input
                            id=""
                            class="form-check-input"
                            type="radio"
                            name="inlineRadioOptions"
                            value="option2"
                          />
                          <label for="" class="form-check-label">Ya</label>
                        </div>

                        <div class="form-check form-check-inline">
                          <input
                            id=""
                            class="form-check-input"
                            type="radio"
                            name="inlineRadioOptions"
                            value="option3"
                          />
                          <label for="" class="form-check-label">Tidak</label>
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

                  <div class="pt-3 d-flex gap-2">
                    <nuxt-link
                      to="/individu-sakit/step4"
                      class="btn btn-light ms-auto"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link
                      to="/individu-sakit/step6"
                      class="btn btn-primary"
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
