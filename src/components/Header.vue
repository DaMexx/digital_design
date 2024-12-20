<template>
  <header class="header">
    <a class="header__logo" href="#">
      <img class="logo__image" src="@/assets/images/icon-logo.svg" alt="logo" />
      <p v-if="false" class="logo__title">
        <span class="title__content"><b>Dianne</b> STUDIO</span>
        <img
          class="title__icon"
          src="@/assets/images/icon-copyright.svg"
          alt="copyright"
        />
      </p>
    </a>
    <section class="header__menu">Menu</section>
  </header>
</template>

<style scoped>
.header,
.header__logo {
  display: flex;
  gap: 10px;
  align-items: center;
}

.header {
  justify-content: space-between;
}

.header__logo {
  text-decoration: none;
  color: var(--app-color-text);
}

.title__icon {
  --size: 20px;
  width: var(--size);
  height: var(--size);
}

.title__content {
  font: 500 35px/40px "Gilroy", sans-serif;
}

.header__menu {
  font: 800 20px/24px "Gilroy-medium", sans-serif;
}
</style>
