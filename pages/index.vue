<template>
  <div>
    <div class="content__header content__boxed overlapping">
      <div class="content__wrap">
        <!-- Page title and information -->
        <h1 class="page-title mb-2">Dashboard</h1>
        <h2 class="h5">Welcome back to the Dashboard.</h2>
        <p>
          Scroll down to see quick links and overviews of your Server, To do
          list<br />
          Order status or get some Help using Nifty.
        </p>
        <!-- END : Page title and information -->
      </div>
    </div>

    <div class="content__boxed">
      <div class="content__wrap">
        <div class="row">
          <div class="col-xl-7 mb-3 mb-xl-0">
            <div class="card h-100">
              <div class="card-header d-flex align-items-center border-0">
                <div class="me-auto">
                  <h3 class="h4 m-0">Network</h3>
                </div>
                <div class="toolbar-end">
                  <button
                    type="button"
                    class="btn btn-icon btn-sm btn-hover btn-light"
                    aria-label="Refresh Network Chart"
                  >
                    <i class="demo-pli-repeat-2 fs-5"></i>
                  </button>
                  <div class="dropdown">
                    <button
                      class="btn btn-icon btn-sm btn-hover btn-light"
                      data-bs-toggle="dropdown"
                      aria-expanded="false"
                      aria-label="Network dropdown"
                    >
                      <i class="demo-pli-dot-horizontal fs-4"></i>
                      <span class="visually-hidden">Toggle Dropdown</span>
                    </button>
                    <ul class="dropdown-menu dropdown-menu-end">
                      <li>
                        <a href="#" class="dropdown-item">
                          <i class="demo-pli-pen-5 fs-5 me-2"></i> Edit Date
                        </a>
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">
                          <i class="demo-pli-refresh fs-5 me-2"></i> Refresh
                        </a>
                      </li>
                      <li>
                        <hr class="dropdown-divider" />
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">
                          <i class="demo-pli-file-csv fs-5 me-2"></i> Save as
                          CSV
                        </a>
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">
                          <i class="demo-pli-calendar-4 fs-5 me-2"></i> View
                          Details
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>

              <!-- Network - Area Chart -->
              <div
                class="card-body py-0"
                style="height: 250px; max-height: 275px"
              >
                <canvas id="_dm-networkChart"></canvas>
              </div>
              <!-- END : Network - Area Chart -->

              <div class="card-body mt-4">
                <div class="row">
                  <div class="col-md-8">
                    <!-- CPU Temperature -->
                    <h4 class="h5 mb-3">CPU Temperature</h4>
                    <div class="row">
                      <div class="col-5">
                        <div class="h5 display-6 fw-normal">
                          43.7 <span class="fw-bold fs-5 align-top">°C</span>
                        </div>
                      </div>
                      <div class="col-7 text-sm">
                        <div
                          class="d-flex justify-content-between align-items-start px-3 mb-3"
                        >
                          Min Values
                          <span class="d-block badge bg-success ms-auto"
                            >27°</span
                          >
                        </div>
                        <div
                          class="d-flex justify-content-between align-items-start px-3"
                        >
                          Max Values
                          <span class="d-block badge bg-danger ms-auto"
                            >89°</span
                          >
                        </div>
                      </div>
                    </div>
                    <!-- END : CPU Temperature -->

                    <!-- Today Tips -->
                    <div class="mt-4">
                      <h5>Today Tips</h5>
                      <p>
                        Lorem ipsum dolor sit amet, consectetuer adipiscing
                        elit, sed diam nonummy nibh euismod tincidunt.
                      </p>
                    </div>
                    <!-- END : Today Tips -->
                  </div>
                  <div class="col-md-4">
                    <!-- Bandwidth usage and progress bars -->
                    <h4 class="h5 mb-3">Bandwidth Usage</h4>
                    <div class="h2 fw-normal">
                      754.9<span class="ms-2 fs-6 align-top">Mbps</span>
                    </div>

                    <div class="mt-4 mb-2 d-flex justify-content-between">
                      <span class="">Income</span>
                      <span class="">70%</span>
                    </div>
                    <div class="progress progress-md">
                      <div
                        class="progress-bar bg-success"
                        role="progressbar"
                        style="width: 70%"
                        aria-label="Incoming Progress"
                        aria-valuenow="70"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>

                    <div class="mt-4 mb-2 d-flex justify-content-between">
                      <span class="">Outcome</span>
                      <span class="">10%</span>
                    </div>
                    <div class="progress progress-md">
                      <div
                        class="progress-bar bg-info"
                        role="progressbar"
                        style="width: 10%"
                        aria-label="Outcome Progress"
                        aria-valuenow="10"
                        aria-valuemin="0"
                        aria-valuemax="100"
                      ></div>
                    </div>
                    <!-- END : Bandwidth usage and progress bars -->
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-xl-5">
            <div class="row">
              <div class="col-sm-6">
                <!-- Tile - HDD Usage -->
                <div class="card bg-success text-white overflow-hidden mb-3">
                  <div class="p-3 pb-2">
                    <h5 class="mb-3">
                      <i
                        class="demo-psi-data-storage text-reset text-opacity-75 fs-3 me-2"
                      ></i>
                      HDD Usage
                    </h5>
                    <ul class="list-group list-group-borderless">
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Free Space</div>
                        <span class="fw-bold">132Gb</span>
                      </li>
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Used space</div>
                        <span class="fw-bold">1,45Gb</span>
                      </li>
                    </ul>
                  </div>

                  <!-- Area Chart -->
                  <div class="py-0" style="height: 70px; margin: 0 -5px -5px">
                    <canvas id="_dm-hddChart"></canvas>
                  </div>
                  <!-- END : Area Chart -->
                </div>
                <!-- END : Tile - HDD Usage -->
              </div>
              <div class="col-sm-6">
                <!-- Tile - Earnings -->
                <div class="card bg-info text-white overflow-hidden mb-3">
                  <div class="p-3 pb-2">
                    <h5 class="mb-3">
                      <i
                        class="demo-psi-coin text-reset text-opacity-75 fs-2 me-2"
                      ></i>
                      Earning
                    </h5>
                    <ul class="list-group list-group-borderless">
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Today</div>
                        <span class="fw-bold">$764</span>
                      </li>
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Last 7 Day</div>
                        <span class="fw-bold">$1,332</span>
                      </li>
                    </ul>
                  </div>

                  <!-- Line Chart -->
                  <div class="py-0" style="height: 70px; margin: 0 -5px -5px">
                    <canvas id="_dm-earningChart"></canvas>
                  </div>
                  <!-- END : Line Chart -->
                </div>
                <!-- END : Tile - Earnings -->
              </div>
            </div>
            <div class="row">
              <div class="col-sm-6">
                <!-- Tile - Sales -->
                <div class="card bg-purple text-white overflow-hidden mb-3">
                  <div class="p-3 pb-2">
                    <h5 class="mb-3">
                      <i
                        class="demo-psi-basket-coins text-reset text-opacity-75 fs-2 me-2"
                      ></i>
                      Sales
                    </h5>
                    <ul class="list-group list-group-borderless">
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Today</div>
                        <span class="fw-bold">$764</span>
                      </li>
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Last 7 Day</div>
                        <span class="fw-bold">$1,332</span>
                      </li>
                    </ul>
                  </div>

                  <!-- Bar Chart -->
                  <div class="py-0" style="height: 70px">
                    <canvas id="_dm-salesChart"></canvas>
                  </div>
                  <!-- END : Bar Chart -->
                </div>
                <!-- END : Tile - Sales -->
              </div>
              <div class="col-sm-6">
                <!-- Tile - Task Progress -->
                <div class="card bg-warning text-white overflow-hidden mb-3">
                  <div class="p-3 pb-2">
                    <h5 class="mb-3">
                      <i
                        class="demo-psi-basket-coins text-reset text-opacity-75 fs-2 me-2"
                      ></i>
                      Task Progress
                    </h5>
                    <ul class="list-group list-group-borderless">
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Completed</div>
                        <span class="fw-bold">34</span>
                      </li>
                      <li
                        class="list-group-item p-0 text-reset d-flex justify-content-between align-items-start"
                      >
                        <div class="me-auto">Total</div>
                        <span class="fw-bold">79</span>
                      </li>
                    </ul>
                  </div>

                  <!-- Horizontal Bar Chart -->
                  <div class="py-0 pb-2" style="height: 70px">
                    <canvas id="_dm-taskChart"></canvas>
                  </div>
                  <!-- END : Horizontal Bar Chart -->
                </div>
                <!-- END : Tile - Task Progress -->
              </div>
            </div>

            <!-- Simple state widget -->
            <div class="card">
              <div class="card-body text-center">
                <div class="d-flex align-items-center">
                  <div class="flex-shrink-0 p-3">
                    <div class="h3 display-3">95</div>
                    <span class="h6">New Friends</span>
                  </div>
                  <div class="flex-grow-1 text-center ms-3">
                    <p class="text-muted">
                      Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
                    </p>
                    <button class="btn btn-sm btn-danger">View Details</button>

                    <!-- Social media statistics -->
                    <div
                      class="mt-4 pt-3 d-flex justify-content-around border-top"
                    >
                      <div class="text-center">
                        <h4 class="mb-1">1,345</h4>
                        <small class="text-muted">Following</small>
                      </div>
                      <div class="text-center">
                        <h4 class="mb-1">23k</h4>
                        <small class="text-muted">Followers</small>
                      </div>
                      <div class="text-center">
                        <h4 class="mb-1">278</h4>
                        <small class="text-muted">Posts</small>
                      </div>
                    </div>
                    <!-- END : Social media statistics -->
                  </div>
                </div>
              </div>
            </div>
            <!-- END : Simple state widget -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
