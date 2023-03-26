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
              <!-- END : Step progress -->
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
                  class="nav-link"
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
                  class="nav-link active"
                  data-step="finish"
                >
                  <span>Neurosensori</span>
                </a>
              </nav>
              <!-- Form sections -->
              <form id="_dm-customWizardForm" class="p-xl-3">
                <!-- Account section -->
                <section data-step="account">
                  <span class="fw-bold">Neurosensori</span>
                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Fungsi Penglihatan
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
                            <label for="" class="form-check-label">Buram</label>
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
                              >Tak bisa melihat</label
                            >
                          </div>
                          <input
                            id=""
                            class="form-control mb-3"
                            type="text"
                            name="inlineRadioOptions"
                            placeholder="Alat bantu"
                          />
                          <input
                            id=""
                            class="form-control"
                            type="text"
                            name="inlineRadioOptions"
                            placeholder="Visus"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Fungsi pendengaran
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
                              >Kurang jelas
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
                            <label for="" class="form-check-label">Tuli </label>
                          </div>
                          <input
                            class="form-control mb-3"
                            type="text"
                            placeholder="Alat Bantu"
                          />
                          <input
                            class="form-control"
                            type="text"
                            placeholder="Tinniitus"
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Fungsi Perasa
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
                            <label for="" class="form-check-label">Mampu</label>
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
                              >Terganggu</label
                            >
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Fungsi Perabaan
                        </label>
                        <div class="col-sm-8">
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label"
                              >Disorientasi
                            </label>
                          </div>

                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Parese
                            </label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Halusinasi
                            </label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Disartria
                            </label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Amnesia
                            </label>
                          </div>
                          <div class="form-check">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option3"
                            />
                            <label for="" class="form-check-label"
                              >Paralisis
                            </label>
                          </div>
                          <input
                            class="form-control mb-3"
                            type="text"
                            placeholder="Kesemutan pada"
                          />
                          <input
                            class="form-control"
                            type="text"
                            placeholder="Kebas pada"
                          />
                        </div>
                      </div>
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
                      to="/individu-sakit/step6"
                      class="btn btn-light ms-auto"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link
                      to="/individu-sakit/step8"
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
