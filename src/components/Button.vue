<script setup></script>

<template>
  <button>
    <slot name="icon"></slot>
    <slot></slot>
    </button>
</template>

<style scoped>
button {
  border: none;
  border-radius: 100px;
  background: var(--btn-bg-color);
  /* padding: 14px; */
  font-family: var(--font);
  font-size: 24px;
  font-weight: 400;
  color: var(--btn-text-color);
  cursor: pointer;
  width: 335px;
  height: 68px;
}
</style>
