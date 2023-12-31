<template>
  <div class="container-fluid">
    <section class="row">
      <!-- SECTION Main body -->
      <div class="col-md-9 col-12">
        <div class="d-flex justify-content-center pt-5">
          <h3 class="funFont">Hey there, my name is Rhys Vickers</h3>
        </div>
        <div class="d-flex justify-content-center pt-5 mx-3">
          <p>Coding is something still fairly new in my life. </p>
        </div>
      </div>
      <!-- SECTION right side bar -->
      <div class="col-md-3 col-12 d-flex justify-content-center maroonBg">
        <section class="row">

          <div class="text-light">
            <img class="rounded-pill avatar p-4" src="../assets/img/Rhys-Vickers-4.jpg" alt=""
              title="Click for a fun fact about Rhys!" role="button">
            <h4 class="funFont">Rhys Vickers</h4>
            <p class="funFont">Software Developer</p>
            <div class="d-flex justify-content-evenly">
              <i class="mdi mdi-github fs-4" role="button" title="Rhys' Github page!"></i>
              <i class="mdi mdi-linkedin fs-4" role="button" title="Rhys' LinkedIn"></i>
              <i class="mdi mdi-email fs-4" role="button" title="Rhys' Email. Feel Free to email me whenever!"></i>
            </div>
          </div>
        </section>
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
.funFont {
  font-family: 'Abril Fatface', serif;

}

.avatar {
  height: 24dvh;
  width: 24dvh;
}

.maroonBg {
  background-color: rgba(93, 0, 0, 0.923);
  // height: 400dvh;

}
</style>
