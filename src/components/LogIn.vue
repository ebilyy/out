<template>
  <div class="login">
    <div class="login__bg">
      <img class="login__image" src="@/assets/blur-bg.jpg" alt="login bg">
    </div>
    <div class="auth-block">
      <div class="firm-logo">
        <img src="@/assets/demo.png" alt="demo">
      </div>
        <h1 class="login__title">Sign in to DEMO OUTrainer</h1>

      <div >
        <a class="auth-link" href="/registration">Haven't got an account? Sign up!</a>
      </div>
      <div class="login__form">

        <div class="form__elems">
          <v-text-field class="form__input" variant="outlined" placeholder="Email"></v-text-field>
          <v-text-field class="form__input" variant="outlined" placeholder="Password" type="password"></v-text-field>
        </div>
        <div class="d-flex justify-space-between">
          <v-btn variant="outlined"> Sign in</v-btn>
          <a class="auth-link" href="/forgot">Forgoten password?</a>
        </div>
        <p>Check our services using DEMO accounts for different roles:</p>
        <ul>
          <li >
            <div>Firm owner</div>
            <a href="">Login: owner@outrainer.pl Password: demo</a>
          </li>
         <li>
         <div> Manager</div>
          <a href="">Login: manager@outrainer.pl Password: demo</a>
         </li>
         <li>
          <div>Trainer</div>
          <a href="">Login: trainer@outrainer.pl Password: demo</a>
         </li>
         <li>
          <div>Client</div>
          <a href="">Login: client@outrainer.pl Password: demo</a>
         </li>
        </ul>
        <div class="login__logo">
          <img src="@/assets/logo_500x300.png" alt="logo">
        </div>
      </div>
    </div>
    <div class="center-block">
      <img class="img-rounded" src="@/assets/ue.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.login {
  padding: 20px 0 0;
}
.login__bg {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1;
}
.login__image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.auth-block {
  width: 540px;
  margin: 0 auto;
  border-radius: 5px;
  background: rgba(0,0,0,.55);
  color: #fff;
  padding: 32px;
}
.firm-logo img{
  width: 100%;
  max-width: 308px;
}
.firm-logo {
  text-align: center;
  margin-bottom: 33px;
}
.form__title {
  font-weight: 300;
  margin-bottom: 28px;
  text-align: center;
}
.auth-block a {
  text-decoration: none;
  outline: 0;
  transition: all .2s ease;
  color: #209e91;
}
.auth-link {
  display: block;
  font-size: 16px;
  text-align: center;
  margin-bottom: 33px;
  padding-bottom: 2em;
}
.auth-link:hover {
  color: #1b867b;
}
.v-field input {
  font-size: 14px;
}
.auth-block p {
  font-size: 16px;
  margin-bottom: 12px;
}
.login__form {
  width: 67%;
  margin: 0 auto;
}
.login__logo {
  text-align: center;
  padding: 14px;
}
.login__logo img {
  max-width: 100%;
}
.center-block {
  max-width: 83.333333%;
  margin: 2em auto;
}
.center-block img {
  width: 100%;
  max-width: 100%;
}
.img-rounded {
 border-radius: 6px;
}
</style>