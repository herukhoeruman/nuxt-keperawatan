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
              <!-- Step progress -->
              <nav
                id="_dm-customWizardSteps"
                class="nav nav-callout justify-content-center flex-nowrap mt-3 mb-3"
              >
                <a
                  href="/individu-sakit/step1"
                  class="nav-link active"
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
                  class="nav-link"
                  data-step="finish"
                >
                  <span>Neurosensori</span>
                </a>
              </nav>
              <!-- END : Step progress -->

              <!-- Form sections -->
              <form id="_dm-customWizardForm" class="p-xl-3">
                <!-- Account section -->
                <section data-step="account">
                  <span class="fw-bold">Keadaan Umum</span>
                  <div class="row mb-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label class="col-sm-4 col-form-label">Kesadaran</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder=""
                          />
                        </div>
                        <label class="col-sm-4 col-form-label">GCS</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder=""
                          />
                        </div>
                        <label class="col-sm-4 col-form-label">TD</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder="mm/Hg"
                          />
                        </div>
                        <label class="col-sm-4 col-form-label">P</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder="x/menit"
                          />
                        </div>
                        <label class="col-sm-4 col-form-label">S</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder="°C"
                          />
                        </div>
                        <label class="col-sm-4 col-form-label">N</label>
                        <div class="col-sm-8 mb-3">
                          <input
                            class="form-control"
                            type="text"
                            placeholder="x/menit"
                          />
                        </div>

                        <div class="col-sm-4"></div>
                        <div class="col-sm-8">
                          <div class="form-check mb-2">
                            <input
                              id="_dm-blockCheckboxes"
                              class="form-check-input"
                              type="checkbox"
                              checked
                            />
                            <label
                              for="_dm-blockCheckboxes"
                              class="form-check-label"
                            >
                              Takikardia
                            </label>
                          </div>
                          <div class="form-check mb-2">
                            <input
                              id="_dm-blockCheckboxes"
                              class="form-check-input"
                              type="checkbox"
                            />
                            <label
                              for="_dm-blockCheckboxes"
                              class="form-check-label"
                            >
                              Bradikardia
                            </label>
                          </div>
                          <div class="form-check mb-2">
                            <input
                              id="_dm-blockCheckboxes"
                              class="form-check-input"
                              type="checkbox"
                            />
                            <label
                              for="_dm-blockCheckboxes"
                              class="form-check-label"
                            >
                              Tubuh teraba hangat
                            </label>
                          </div>
                          <div class="form-check mb-2">
                            <input
                              id="_dm-blockCheckboxes"
                              class="form-check-input"
                              type="checkbox"
                            />
                            <label
                              for="_dm-blockCheckboxes"
                              class="form-check-label"
                            >
                              Menggigil
                            </label>
                          </div>
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
                      to="/individu-sakit/step"
                      class="btn btn-light ms-auto disabled"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link
                      to="/individu-sakit/step2"
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

<script>
export default {
  name: 'keperawatan-create',
}
</script>
