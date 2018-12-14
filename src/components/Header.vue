<template>
  <header id="header" class="header">
    <nav class="header__nav">
      <div class="nav__logo">
        <img class="logo" src="@/assets/logo.svg" alt="Fylo">
      </div>
      <div class="nav__menu">
        <a class="menu__link" href>Sign In</a>
        <a class="menu__btn btn" href>Sign Up</a>
      </div>
    </nav>
    <div class="header__bg">
      <img class="bg__intro-mobile" src="@/assets/bg-intro-mobile.svg" alt>
      <img class="bg__illustration" src="@/assets/illustration-main.svg" alt>
    </div>
    <h1>All your files in one secure location, accessible anywhere.</h1>
    <p>
      Fylo stores all your most important files in one secure location.
      Access them wherever you need, share and collaborate with friends,
      family and co-workers.
    </p>
    <div class="header__btn btn">Get Started</div>
  </header>
</template>

<style lang="scss" scoped>
.header__bg {
  display: flex;
  justify-content: center;
  min-height: 260px;
}

.bg__intro-mobile {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 1;
}

.bg__illustration {
  position: absolute;
  top: 90px;
  z-index: 2;
  width: 220px;
}

.header__nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.6rem;
}

.nav__logo {
  z-index: 3;
  display: flex;
  align-items: center;
}

.nav__menu {
  z-index: 3;
}

.nav__logo .logo {
  width: 85%;
}

.nav__menu a {
  color: white;
  display: inline-block;
  font-size: 0.9rem;
}

.menu__link {
  padding: 0 1.2rem;
}

.header h1 {
  font-size: 1.8rem;
  padding: 0 1.6rem;
  text-align: center;
  margin: 1.5rem 0;
  line-height: 1.25;
}

.header p {
  font-family: $open-sans;
  color: $gray;
  font-size: 1rem;
  padding: 0 1.6rem;
  text-align: center;
  margin: 1.5rem 0;
}

.header__btn {
  margin: 1.5rem 5rem;
  font-weight: $fw700;
  padding: 1rem 1.5rem;
}
</style>
