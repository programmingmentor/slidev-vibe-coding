<template>
  <div class="ssa-logo-global" v-if="$slidev.nav.currentLayout !== 'end'">
    <a href="https://career.softserveinc.com/uk-ua/softserve-academy">
      <img src="/ssa-logo-white.svg" alt="SoftServe Academy Logo" />
    </a>
  </div>
</template>

<style>
.ssa-logo-global {
  position: fixed;
  bottom: 10px;
  right: 20px;
  z-index: 100;
  pointer-events: auto;
}

.ssa-logo-global img {
  height: 13px;
  width: auto;
}

.ssa-logo-global a {
  text-decoration: none;
  border: 2.4px solid transparent;
  display: block;
}

.ssa-logo-global a:hover {
  border-color: var(--slidev-theme-primary);
}
</style>
