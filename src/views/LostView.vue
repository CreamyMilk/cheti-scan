<template>
  <div class="frame">
    <nav>
      <img alt="Cheti logo" src="../assets/logo.svg" />
    </nav>
    <main>
      <Transition name="fade" appear>
      <div id="lost">
        <div>
          <h4>404</h4>
          <p>Couldn't fetch this page</p>
        </div>
      </div>
      </Transition>
    </main>
    <footer>
      <Transition name="slide-up" appear>
      <div>
        <a href="/">Home</a>
      </div>
      </Transition>
    </footer>
  </div>
</template>

<style scoped>
  #lost {
    padding: 24px 36px;
    text-align: center;
  }
</style>