<template>
  <div class="container-fluid">
    <section class="row">
      <div class="col-md-9 col-12">
        Hi
      </div>
      <div class="col-md-3 col-12 d-flex justify-content-center maroonBg">
        <div class="text-light">
          <img class="rounded-pill avatar p-4" src="../assets/img/Rhys-Vickers-4.jpg" alt=""
            title="Click for a fun fact about Rhys!" role="button">
          <h3>Rhys Vickers</h3>
          <h5>Software Developer</h5>

        </div>
      </div>

    </section>
  </div>
</template>
<script>
export default {
  setup() {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
.avatar {
  height: 24dvh;
  width: 24dvh;
}

.maroonBg {
  background-color: rgba(93, 0, 0, 0.923);
  height: 400dvh;

}
</style>
