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
                class="nav nav-callout justify-content-center flex-nowrap mt-3 mb-1"
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
                  <span class="fw-bold">Mental</span>
                  <div class="row mb-1 mt-3">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Cemas </label>
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
                    <div class="col-xl-6"></div>
                  </div>

                  <div class="row mb-1 mt-3">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Denial </label>
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
                    <div class="col-xl-6"></div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Marah </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6"></div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Takut </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6"></div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Putus asa
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
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Depresi </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Rendah diri
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
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Menarik diri
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
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Agresif </label>
                        <div class="col-sm-8">
                          <div class="form-check form-check-inline">
                            <input
                              id=""
                              class="form-check-input"
                              type="radio"
                              name="inlineRadioOptions"
                              value="option2"
                            />
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Perilaku kekerasan
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
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Tidak mau melihat bagian tubuh yang rusak
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
                            <label for="" class="form-check-label">Ya </label>
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
                              >Tidak
                            </label>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Respon pasca trauma
                        </label>
                        <div class="col-sm-8">
                          <input
                            type="text"
                            name=""
                            id=""
                            class="form-control"
                            placeholder=""
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <hr />
                  <span class="fw-bold">Komunikasi dan Budaya</span>
                  <div class="row mb-1 mt-3">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Interaksi dengan Keluarga
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
                            <label for="" class="form-check-label">Baik</label>
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
                              >Terhambat</label
                            >
                          </div>
                          <input
                            type="text"
                            name=""
                            id=""
                            class="form-control"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center"></div>
                    </div>
                  </div>

                  <div class="row mb-1 mt-3">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">
                          Berkomunikasi
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
                              >Lancar
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
                              >Terhambat
                            </label>
                          </div>
                          <input
                            type="text"
                            name=""
                            id=""
                            class="form-control"
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6"></div>
                  </div>

                  <div class="row mb-1 mt-3">
                    <div class="col-xl-6 mb-1">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label"
                          >Kegiatan sosial sehari-har
                        </label>
                        <div class="col-sm-8">
                          <input
                            type="text"
                            name=""
                            id=" "
                            class="form-control"
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

                  <div class="pt-3 d-flex gap-2">
                    <nuxt-link
                      to="/individu-sakit/step7"
                      class="btn btn-light ms-auto"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link
                      to="/individu-sakit/step10"
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
