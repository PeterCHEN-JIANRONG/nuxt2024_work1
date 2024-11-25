<script setup></script>
<template>
  <div>
    <ul>
      <li><NuxtLink to="/">首頁</NuxtLink></li>
      <li><NuxtLink to="/account/login">會員登入</NuxtLink></li>
      <li><NuxtLink to="/account/signup">會員註冊</NuxtLink></li>
      <li><NuxtLink to="/rooms">客房列表</NuxtLink></li>
      <li><NuxtLink to="/rooms/12345">客房詳細</NuxtLink></li>
      <li><NuxtLink to="/rooms/12345/booking">客房預約</NuxtLink></li>
      <li><NuxtLink to="/booking/confirmation/12345">預約成功/失敗</NuxtLink></li>
      <li><NuxtLink to="/user/25532/profile">會員 - 修改資料</NuxtLink></li>
      <li><NuxtLink to="/user/25532/order">會員 - 訂單</NuxtLink></li>
    </ul>
    <slot />
  </div>
</template>
<style scoped></style>
