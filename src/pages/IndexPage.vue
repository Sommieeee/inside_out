<template>
  <q-page class="flex justify-center bg-body">
    <div class="full-width" style="max-width: 400px">
      <q-card style="margin-top: 250px">
        <q-card-section>
          <div class="col text-h6 ellipsis flex justify-center">
            <img class="insideout" src="~assets/images/insideout-logo.png" />
          </div>
          <q-form class="q-gutter-md">
            <q-input
              :rules="[
                (val, rules) =>
                  rules.email(val) || 'Please enter a valid email address',
              ]"
              label="Username"
              color="black"
            ></q-input>
          </q-form>
          <q-form class="q-gutter-md">
            <q-input label="Password" color="black"></q-input>
          </q-form>
          <q-btn to="/home" class="loginbtn">Login</q-btn>
        </q-card-section>
        <q-card-section>
          <p>Forgot Password?</p>
        </q-card-section>
        <q-card-section>
          <center>
            <p class="sign">
              Don't have an account?
              <router-link class="register" to="/sign">Sign Up</router-link>
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
  background-image: url("assets/images/clothes.jpeg");
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.loginbtn {
  margin-top: 30px;
  color: white;
  background-color: black;
  width: 100%;
}
.sign {
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
