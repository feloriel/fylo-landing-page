<template>
  <footer class="footer">
    <div class="footer__logo">
      <img class="logo" src="@/assets/logo-alt.svg" alt="Fylo">
    </div>
    <div class="footer__subscription">
      <p>Receive updates from us, including tips and tricks on how to improve your workflow.</p>
      <input class="subscription__email" type="email">
      <div class="subscription__btn btn">Join</div>
    </div>
    <div class="footer__contacts">
      <div class="contacts__phone">
        <img src="@/assets/icon-phone.svg" alt="phone"> 
        <span>Phone: <a href="callto:+15431234567">+1-543-123-4567</a></span>
      </div>
      <div class="contacts__email">
        <img src="@/assets/icon-email.svg" alt="email">
        <a href="mailto:example@fylo.com">example@fylo.com</a>
      </div>
    </div>
    Fylo
    Desktop App
    Mobile App
    Pricing
    Feature
    Company
    About Us
    Jobs
    Press
    Blog
    Support
    Contact Us
    Terms
    Privacy
    <p class="attribution">
      This page started life as a challenge on
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a> 🎉
    </p>
  </footer>
</template>

<style lang="scss" scoped>
.attribution {
  font-size: 11px;
  text-align: center;
}

.attribution a {
  color: hsl(228, 45%, 44%);
}
.footer {
  background-color: $dark-blue;
  color: $white;
  padding: 6rem 1.6rem;
}

.footer p {
  font-size: 0.9rem;
  line-height: 1.5rem;
  font-weight: $fw400;
  margin: 0.75rem 0;
}

.footer__subscription {
  display: flex;
  flex-direction: column;
}

.footer__subscription .subscription__email {
  margin: 0.75rem 0;
  width: calc(100% - 1rem);
  border: 1px solid white;
  border-radius: 0.2rem;
  font-size: 1rem;
  padding: 0.4rem;
}

.footer__subscription .subscription__btn {
  margin: 0.75rem 0;
  width: 25%;
  padding: 0.4rem 1.8rem;
  font-size: 0.8rem;
  align-self: flex-end;
}

.footer__contacts {
  margin: 1.5rem 0;
  font-size: 0.9rem;
}

.footer a {
  color: $white;
}

.contacts__phone, .contacts__email {
  display: flex;
  align-items: center;
  margin: 0.75rem 0;
}

.contacts__phone img, .contacts__email img {
  padding-right: 1.5rem;
}
</style>
