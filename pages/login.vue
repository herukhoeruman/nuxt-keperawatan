<template>
  <section id="content" class="content">
    <div
      class="content__boxed w-100 min-vh-100 d-flex flex-column align-items-center justify-content-center"
    >
      <div class="content__wrap">
        <!-- Login card -->
        <div class="card shadow-lg">
          <div class="card-body">
            <div class="text-center">
              <h1 class="h3">Login</h1>
              <p>Sign In to your account</p>
            </div>

            <form class="mt-4" action=" ">
              <div class="mb-3">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Username"
                  autofocus
                />
              </div>

              <div class="mb-3">
                <input
                  type="password"
                  class="form-control"
                  placeholder="Password"
                />
              </div>

              <div class="d-grid mt-5">
                <nuxt-link to="/" class="btn btn-primary btn-lg">
                  Sign In
                </nuxt-link>
              </div>
            </form>
          </div>
        </div>
        <!-- END : Login card -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: 'auth',
}
</script>
