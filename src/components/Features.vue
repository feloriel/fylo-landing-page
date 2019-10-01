<template>
  <div class="features">
    <h2>Stay productive, wherever you are</h2>
    <p>
      Never let location be an issue when accessing your files. Fylo has you
      covered for all of your file storage needs.
    </p>
    <div class="features__blocks">
      <img src="@/assets/icon-devices.svg" alt="All devices">
      <h3>All platforms, all devices, all your files</h3>
    </div>
    <div class="features__blocks">
      <img src="@/assets/icon-security.svg" alt="Security">
      <h3>Security you can trust</h3>
    </div>
    <div class="features__blocks">
      <img src="@/assets/icon-collaboration.svg" alt="Collaboration">
      <h3>Real-time collaboration</h3>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.features {
  padding: 5rem 0;
  background-color: $light-gray;

  h2 {
    font-size: 1.4rem;
    padding: 0 1.6rem;
    text-align: center;
    margin: 1.5rem 0;
    line-height: 1.25;
    color: $dark-blue;
  }

  p {
    font-family: $open-sans;
    color: $gray;
    font-size: 1rem;
    padding: 0 1.6rem;
    text-align: center;
    margin: 1.5rem 0;
  }
}

.features__blocks {
  display: flex;
  flex-direction: column;
  align-items: center;
  & img {
    padding: 1.8rem;
  }
}

.features h3 {
  font-size: 1.1rem;
  padding: 0 1.6rem;
  text-align: center;
  margin: 1.5rem 0;
  line-height: 1.25;
  color: $dark-gray;
}
</style>
