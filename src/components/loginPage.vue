<template>
  <div>
    <div class="auth-wrapper">
      <div class="auth-content">
        <div class="auth-bg">
          <span class="r"></span>
          <span class="r s"></span>
          <span class="r s"></span>
          <span class="r"></span>
        </div>

        <div class="card">
          <div class="card-body text-center">
            <div class="mb-4">
              <i class="fas fa-unlock-alt lock"></i>
            </div>

            <h3 class="mb-4">Login</h3>
            <div class="input-group mb-3">
              <input type="email" class="form-control" placeholder="Email" required/>
            </div>

            <div class="input-group mb-4">
              <input type="password" class="form-control" placeholder="password" minlength="8" required/>
            </div>

            <div class="form-group text-left">
              <div class="form-group form-check">
                <input type="checkbox" class="form-check-input" id="exampleCheck1" />
                <label class="form-check-label" for="exampleCheck1">Save Credentials</label>
              </div>
            </div>

            <router-link to="./sideBar"><button class="btn btn-primary shadow-2 mb-4">Login</button></router-link>
            <p class="mb-2 text-muted">
              Forgot password?
              <a href="auth-reset-password.html">Reset</a>
            </p>
            <!-- <p class="mb-0 text-muted">
              Don’t have an account?
              <a href="auth-signup.html">Signup</a>
            </p> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.lock {
  font-size: 80px;
  color: aqua;
}
</style>
