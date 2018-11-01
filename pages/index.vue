<template>
  <section class="container">
    <div>
      <h1 class="title">
        William Montagnon
      </h1>
      <h2 class="subtitle">
        UX Developer
      </h2>
    </div>
  </section>
</template>

<style>
.container {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;

  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#1e5799+0,429ee5+100 */
  background: #1e5799; /* Old browsers */
  background: -moz-linear-gradient(-45deg, #1e5799 0%, #429ee5 100%); /* FF3.6-15 */
  background: -webkit-linear-gradient(-45deg, #1e5799 0%,#429ee5 100%); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(135deg, #1e5799 0%,#429ee5 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#1e5799', endColorstr='#429ee5',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */
}

.container:before{
  content: '';
  position: absolute;
  top: 50px;
  left: 50px;
  width: calc(100vw - 100px);
  height: calc(100vh - 100px);
  border: 7px solid white;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: white;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #f0f0f0;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

