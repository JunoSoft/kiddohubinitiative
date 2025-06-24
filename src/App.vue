<template>
  <div id="app">
    <header>
      <!-- Header Content -->
      Kiddo Hub Initiative.
    </header>

    <main>
      <!-- Image Lightbox -->
      <MDBContainer class="mt-5">
        <MDBLightbox>
          <MDBRow>
            <MDBCol lg="6">
              <MDBLightboxItem
                src="https://mdbootstrap.com/img/Photos/Thumbnails/Slides/1.webp"
                fullscreenSrc="https://mdbootstrap.com/img/Photos/Slides/1.webp"
                class="w-100 mb-2 mb-md-4"
              />
              <MDBLightboxItem
                src="https://mdbootstrap.com/img/Photos/Thumbnails/Square/1.webp"
                fullscreenSrc="https://mdbootstrap.com/img/Photos/Square/1.webp"
                class="w-100"
              />
            </MDBCol>
            <MDBCol lg="6">
              <MDBLightboxItem
                src="https://mdbootstrap.com/img/Photos/Thumbnails/Vertical/1.webp"
                fullscreenSrc="https://mdbootstrap.com/img/Photos/Vertical/1.webp"
                class="w-100"
              />
            </MDBCol>
          </MDBRow>
        </MDBLightbox>
      </MDBContainer>

      <!-- Existing router view -->
      <router-view></router-view>
    </main>

    <footer>
      <!-- Footer Content -->
    </footer>
  </div>
</template>


<script>
import {
  MDBContainer,
  MDBRow,
  MDBCol,
  MDBLightbox,
  MDBLightboxItem
} from "mdb-vue-ui-kit";

// If you're using other components like SendButton, import them too


export default {
  name: "App",
  components: {
    MDBContainer,
    MDBRow,
    MDBCol,
    MDBLightbox,
    MDBLightboxItem,
  },
};
</script>


<style>
#app {
  text-align: center;
}
</style>
