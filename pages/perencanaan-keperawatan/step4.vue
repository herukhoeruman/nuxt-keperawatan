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
                  class="nav-link"
                  data-step="address"
                >
                  <i class="d-block demo-pli-home fs-2 mb-2"></i>
                  <span>Pemeliharaan Kesehatan</span>
                </a>

                <a
                  href="/keperawatan/step4"
                  class="nav-link active"
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
                          >Kunjungan Pertama (K-1)
                        </label>
                        <div class="col-sm-8 mb-3">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Perawat
                        </label>
                        <div class="col-sm-8">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Kunjungan Pertama (K-2)
                        </label>
                        <div class="col-sm-8 mb-3">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Perawat
                        </label>
                        <div class="col-sm-8">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="row mb-3 mt-3">
                    <div class="col-xl-6 mb-3">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Kunjungan Pertama (K-3)
                        </label>
                        <div class="col-sm-8 mb-3">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Perawat
                        </label>
                        <div class="col-sm-8">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                      </div>
                    </div>
                    <div class="col-xl-6">
                      <div class="row align-items-center">
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Kunjungan Pertama (K-4)
                        </label>
                        <div class="col-sm-8 mb-3">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                        <label
                          for="_dm-wRegPassword"
                          class="col-sm-4 col-form-label"
                          >Perawat
                        </label>
                        <div class="col-sm-8">
                          <textarea
                            id="_dm-wRegPassword"
                            class="form-control"
                            type="password"
                            placeholder=""
                          />
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="pt-3 d-flex gap-2">
                    <nuxt-link
                      to="/keperawatan/create"
                      class="btn btn-light ms-auto"
                    >
                      Previous
                    </nuxt-link>
                    <nuxt-link to="/keperawatan/step3" class="btn btn-primary"
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
