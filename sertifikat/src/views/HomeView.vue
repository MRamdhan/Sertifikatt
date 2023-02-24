<template>
  <section class="vh-100">
    <div class="container-fluid h-custom">
      <div class="row d-flex justify-content-center align-items-center h-100">
        <div class="col-md-9 col-lg-6 col-xl-5">
        </div>
          <div class="col-md-8 col-lg-6 col-xl-4 offset-xl-1">
          <form>
            <div class="right">
              <!-- Email input -->
              <div class="form-outline mb-4">
                <input
                  type="username"
                  id="username"
                  class="form-control form-control-lg"
                  placeholder="Username"
                />
              </div>
              <!-- Password input -->
              <div class="form-outline mb-3">
                <input
                  type="password"
                  id="Password"
                  class="form-control form-control-lg"
                  placeholder="Enter password"
                />
              </div>
              <div class="text-center text-lg-start mt-4 pt-2">
                <router-link to="/kontak" class="btn btn-primary btn-lg" style="padding-left: 2.5rem; padding-right: 2.5rem"> Login </router-link>
                <!-- <p class="small fw-bold mt-2 pt-1 mb-0">
                  Forget
                </p> -->
                <p class="small fw-bold mt-2 pt-1 mb-0 text-primary fw-bold"> Forget 
                  <router-link to="/register" style="text-decoration: none;"> Password? </router-link>
                </p>
              </div>
            </div>
          </form>
        </div>
        </div>
      </div>
  </section>
</template>

<style scoped>
.divider:after,
.divider:before {
  content: "";
  flex: 1;
  height: 1px;
  background: #eee;
}
.h-custom {
  height: calc(100% - 73px);
}
@media (max-width: 450px) {
  .h-custom {
    height: 100%;
  }
}
</style>

