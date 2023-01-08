<template>
  <q-page class="flex justify-center bg-body">
    <div class="full-width" style="max-width: 400px">
      <q-card style="margin-top: 230px">
        <q-card-section>
          <div class="col text-h6 ellipsis flex justify-center">
            <img class="insideout" src="~assets/images/insideout-logo.png" />
          </div>
          <q-form class="q-gutter-md">
            <q-input label="Full Name" color="black"></q-input>
          </q-form>
          <q-form class="q-gutter-md">
            <q-input label="Email Address" color="black"></q-input>
          </q-form>
          <q-form class="q-gutter-md">
            <q-input label="Password" color="black"></q-input>
          </q-form>
          <q-form class="q-gutter-md">
            <q-input label="Confirm Password" color="black"></q-input>
          </q-form>
          <q-btn to="/home" class="loginbtn">Sign Up</q-btn>
        </q-card-section>
        <q-card-section>
          <center>
            <p class="signup">
              Already have an account?
              <router-link class="register" to="/">Sign In</router-link>
            </p>
          </center>
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<style scoped>
.bg-body {
  height: 100vh;
  width: 100vw;
  background-image: url("assets/images/fashion-store.jpg");
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.loginbtn {
  margin-top: 30px;
  color: white;
  background-color: black;
  width: 100%;
}
.signup {
  color: grey;
}
.register {
  text-decoration: none;
  color: black;
}
.insideout {
  width: 40%;
}
</style>
