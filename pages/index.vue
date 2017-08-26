<template>
  <section class="container">
    <div>
      <h2 class="subtitle">
        Steps to reproduce the issue
      </h2>
      <ol class="list">
        <li>Go to <nuxt-link to="/contacts">/#/contacts</nuxt-link>, see that page is working.</li>
        <li>Refresh the page, see the error message <code>Cannot read property 'layout' of undefined</code>.</li>
      </ol>
    </div>
  </section>
</template>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.list {
  text-align: left;
}
</style>
