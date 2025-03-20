<template>
  <div class="ssa-logo">
    <a href="https://career.softserveinc.com/uk-ua/softserve-academy">
      <img src="/ssa-logo-white.svg" alt="SoftServe Academy Logo" />
    </a>
  </div>
</template>

<style scoped>
.ssa-logo {
  position: fixed;
  bottom: 10px;
  right: 60px;
  z-index: 10;
}

.ssa-logo img {
  height: 40px;
  width: auto;
}

.ssa-logo a {
  text-decoration: none;
  border: 2.4px solid transparent;
  display: block;
}

.ssa-logo a:hover {
  border-color: var(--slidev-theme-primary);
}
</style>
