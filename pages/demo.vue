<template>
  <div class="container">
    <no-ssr>
      <span>この文字はSSRのとき表示されないはず。mountedされたら表示される</span>
    </no-ssr>
    <nuxt-link to="/">Go to Front Page</nuxt-link>
  </div>
</template>
