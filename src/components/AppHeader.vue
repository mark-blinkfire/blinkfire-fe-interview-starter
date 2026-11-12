<template>
  <header class="header">
    <div class="header__content">
      <img
        src="../assets/images/blinkfire-logo-huge.png"
        alt="Blinkfire Logo"
        class="header__logo"
      />
    </div>
  </header>
</template>

<script setup></script>

<style scoped>
.header {
  background-color: #fff;
  border-bottom: 1px solid #e0e0e0;
  padding: 16px 20px;
  width: 100%;
}

.header__content {
  display: flex;
  align-items: center;
  gap: 12px;
  margin: 0 auto;
}

.header__logo {
  height: 40px;
  width: auto;
}
</style>
