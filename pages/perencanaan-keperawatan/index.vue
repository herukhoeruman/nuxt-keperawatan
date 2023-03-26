<template>
  <div>
    <div class="content__header content__boxed overlapping">
      <div class="content__wrap">
        <!-- Breadcrumb -->
        <nav aria-label="breadcrumb">
          <ol class="breadcrumb mb-0">
            <li class="breadcrumb-item"><nuxt-link to="/">Home</nuxt-link></li>
            <li class="breadcrumb-item active" aria-current="page">
              Perencanaan Keperawatan
            </li>
          </ol>
        </nav>
        <!-- END : Breadcrumb -->

        <h1 class="page-title mb-3 mt-2">Perencanaan Keperawatan</h1>
      </div>
    </div>

    <div class="content__boxed">
      <div class="content__wrap">
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">Search</h5>
            <!-- Inline Form -->
            <form class="row">
              <div class="col-6">
                <label for="_dm-staticEmail" class="visually-hidden"
                  >Cari data</label
                >
                <select class="form-select" aria-label="Default select example">
                  <option selected>Cari data</option>
                  <option value="1">Benjamin</option>
                  <option value="2">Lucas</option>
                  <option value="3">Olivia</option>
                  <option value="3">Emma</option>
                  <option value="3">Evelyn</option>
                  <option value="3">William</option>
                  <option value="3">Sophia</option>
                </select>
              </div>
              <div class="col-6">
                <button type="submit" class="btn btn-primary">Search</button>
              </div>
            </form>
            <!-- END : Inline Form -->
          </div>
        </div>
        <!-- Table with toolbar -->
        <div class="card">
          <div class="card-header -4 mb-3">
            <h5 class="card-title mb-3">Data Perencanaan Keperawatan</h5>
            <div class="row">
              <!-- Left toolbar -->
              <div class="col-md-6 d-flex gap-1 align-items-center mb-3">
                <nuxt-link
                  to="/perencanaan-keperawatan/step1"
                  class="btn btn-primary hstack gap-2 align-self-center"
                >
                  <i class="demo-psi-add fs-5"></i>
                  <span class="vr"></span>
                  Add New
                </nuxt-link>
                <button class="btn btn-icon btn-outline-light">
                  <i class="demo-pli-printer fs-5"></i>
                </button>
                <div class="btn-group">
                  <button class="btn btn-icon btn-outline-light">
                    <i class="demo-pli-exclamation fs-5"></i>
                  </button>
                  <button class="btn btn-icon btn-outline-light">
                    <i class="demo-pli-recycling fs-5"></i>
                  </button>
                </div>
              </div>
              <!-- END : Left toolbar -->

              <!-- Right Toolbar -->
              <div
                class="col-md-6 d-flex gap-1 align-items-center justify-content-md-end mb-3"
              >
                <div class="form-group">
                  <input
                    type="text"
                    placeholder="Search..."
                    class="form-control"
                    autocomplete="off"
                  />
                </div>
                <div class="btn-group">
                  <button class="btn btn-icon btn-outline-light">
                    <i class="demo-pli-download-from-cloud fs-5"></i>
                  </button>
                  <div class="btn-group dropdown">
                    <button
                      class="btn btn-icon btn-outline-light dropdown-toggle dropdown-toggle-split"
                      data-bs-toggle="dropdown"
                      aria-expanded="false"
                    >
                      <span class="visually-hidden">Toggle Dropdown</span>
                    </button>
                    <ul class="dropdown-menu dropdown-menu-end">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li>
                        <a class="dropdown-item" href="#">Another action</a>
                      </li>
                      <li>
                        <a class="dropdown-item" href="#"
                          >Something else here</a
                        >
                      </li>
                      <li>
                        <hr class="dropdown-divider" />
                      </li>
                      <li>
                        <a class="dropdown-item" href="#">Separated link</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
              <!-- END : Right Toolbar -->
            </div>
          </div>

          <div class="card-body">
            <div class="table-responsove">
              <table class="table table-striped">
                <thead>
                  <tr>
                    <th class="text-center">Invoice</th>
                    <th>User</th>
                    <th>Order date</th>
                    <th>Amount</th>
                    <th>Status</th>
                    <th>Tracking Number</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><a class="btn-link" href="#"> Order #53431</a></td>
                    <td>Steve N. Horton</td>
                    <td>
                      <span class="text-muted"
                        ><i class="demo-pli-clock"></i> Oct 22, 2021</span
                      >
                    </td>
                    <td>$45.00</td>
                    <td class="fs-5">
                      <div class="badge d-block bg-success">Paid</div>
                    </td>
                    <td>-</td>
                  </tr>
                  <tr>
                    <td><a class="btn-link" href="#"> Order #53432</a></td>
                    <td>Charles S Boyle</td>
                    <td>
                      <span class="text-muted"
                        ><i class="demo-pli-clock"></i> Oct 24, 2021</span
                      >
                    </td>
                    <td>$245.30</td>
                    <td class="fs-5">
                      <div class="badge d-block bg-danger">Refund</div>
                    </td>
                    <td><i class="demo-pli-mine"></i> CGX0089734531</td>
                  </tr>
                  <tr>
                    <td><a class="btn-link" href="#"> Order #53433</a></td>
                    <td>Lucy Doe</td>
                    <td>
                      <span class="text-muted"
                        ><i class="demo-pli-clock"></i> Oct 24, 2021</span
                      >
                    </td>
                    <td>$38.00</td>
                    <td class="fs-5">
                      <div class="badge d-block bg-info">Shipped</div>
                    </td>
                    <td><i class="demo-pli-mine"></i> CGX0089934571</td>
                  </tr>
                  <tr>
                    <td><a class="btn-link" href="#"> Order #53434</a></td>
                    <td>Teresa L. Doe</td>
                    <td>
                      <span class="text-muted"
                        ><i class="demo-pli-clock"></i> Oct 15, 2021</span
                      >
                    </td>
                    <td>$77.99</td>
                    <td class="fs-5">
                      <div class="badge d-block bg-info">Shipped</div>
                    </td>
                    <td><i class="demo-pli-mine"></i> CGX0089734574</td>
                  </tr>
                  <tr>
                    <td><a class="btn-link" href="#"> Order #53435</a></td>
                    <td>Teresa L. Doe</td>
                    <td>
                      <span class="text-muted"
                        ><i class="demo-pli-clock"></i> Oct 12, 2021</span
                      >
                    </td>
                    <td>$18.00</td>
                    <td class="fs-5">
                      <div class="badge d-block bg-success">Paid</div>
                    </td>
                    <td>-</td>
                  </tr>
                </tbody>
              </table>
            </div>

            <nav class="text-align-center mt-5" aria-label="Table navigation">
              <ul class="pagination justify-content-center">
                <li class="page-item disabled">
                  <a class="page-link">Previous</a>
                </li>
                <li class="page-item active" aria-current="page">
                  <span class="page-link">1</span>
                </li>
                <li class="page-item"><a class="page-link" href="#">2</a></li>
                <li class="page-item"><a class="page-link" href="#">3</a></li>
                <li class="page-item disabled">
                  <a class="page-link" href="#">...</a>
                </li>
                <li class="page-item"><a class="page-link" href="#">5</a></li>
                <li class="page-item">
                  <a class="page-link" href="#">Next</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <!-- END : Table with toolbar -->
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'keperawatan',
}
</script>
