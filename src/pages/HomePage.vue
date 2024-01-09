<template>
  <div class="container-fluid">
    <section class="row">
      <!-- SECTION Main body -->
      <div class="col-md-9 col-12">
        <div class="d-flex justify-content-center pt-5">
          <h3 class="funFont">Hey there, my name is Rhys Vickers</h3>
        </div>
        <div class="d-flex justify-content-center pt-5 mx-3">
          <p class="m-4">Coding is something still fairly new in my life. At an early age I always wanted to become a
            teacher, so I got my Associates degree in Education at College of Western Idaho. I then went on to Boise State
            as an Integrated Media Major and in my last semester at Boise State I decided to
            take a Web
            Design class. In that class I learned the basics of HTML and CSS and instantly fell in love with coding. I
            decided that after I got my BA I wanted to continue my education at Boise Codeworks. After an intense 13 week
            program I have learned so much about the life of a Software Developer and I am incredibly excited to continue
            my journey through code. </p>
        </div>

        <div>
          <h4 class="mx-4 pt-4">My Projects</h4>
        </div>
        <div class="col-6 d-flex">
          <p>Project</p>
          <p>Project</p>
          <p>Project</p>
          <p>Project</p>
        </div>
      </div>
      <!-- SECTION right side bar -->
      <div class="col-md-3 col-12 d-flex justify-content-center maroonBg">
        <section class="row">

          <div class="text-light">
            <img class="rounded-pill avatar p-4" src="../assets/img/Rhys-Vickers-4.jpg" alt="" title="Rhys Vickers">
            <h4 class="funFont">Rhys Vickers</h4>
            <p class="funFont">Software Developer</p>
            <div class="d-flex justify-content-evenly">
              <a href="https://github.com/rsvickers">
                <i class="mdi mdi-github fs-4 " role="button" title="Rhys' Github page!"></i>
              </a>
              <a href="https://www.linkedin.com/in/rhys-vickers-5040891ba/">
                <i class="mdi mdi-linkedin fs-4 " role="button" title="Rhys' LinkedIn"></i>
              </a>
              <a href="">
                <i class="mdi mdi-email fs-4 " role="button"
                  title="rs.vickers5@gmail.com Feel free to email anytime."></i>
              </a>
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
