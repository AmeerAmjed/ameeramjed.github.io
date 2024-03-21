<script setup lang="ts">
import Navbar from './TopNavBar.vue'
</script>
<template>
  <div class="main-content">
    <Navbar />

    <article class="about active" data-page="about">
      <header>
        <h2 class="h2 article-title">About me</h2>
      </header>

      <section class="about-text">
        <p>
          Hi 👋🏾, I'm happy you stopped by! I am an experience mobile app developer (Native Android,
          Flutter Multi-platform) with 3+ years of experience. I am an enthusiastic, self-motivated,
          reliable, responsible, and hard-working person. Can work alone or as part of a team.
        </p>
      </section>

      <!--
  - service
-->

      <section class="service">
        <h3 class="h3 service-title">What i'm doing</h3>

        <ul class="service-list">
          <li class="service-item">
            <div class="service-icon-box">
              <img
                src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_flutter_icon_130599.png
        "
                alt="design icon"
                width="40"
              />
            </div>

            <div class="service-content-box">
              <p class="h4 service-item-title">Flutter developer</p>

              <p class="service-item-text">Cross-Platform App using Dart lang</p>
            </div>
          </li>

          <li class="service-item">
            <div class="service-icon-box">
              <img
                src="https://cdn.freelogovectors.net/wp-content/uploads/2023/09/android_logo_2023-freelogovectors.net_.png"
                alt="Web development icon"
                width="40"
              />
            </div>

            <div class="service-content-box">
              <h4 class="h4 service-item-title">Android developer</h4>

              <p class="service-item-text">Native android app using Koltin lang</p>
            </div>
          </li>

          <li class="service-item">
            <div class="service-icon-box">
              <img
                src="https://seeklogo.com/images/K/kotlin-logo-6A9E0484CA-seeklogo.com.png"
                alt="mobile app icon"
                width="40"
              />
            </div>

            <div class="service-content-box">
              <h4 class="h4 service-item-title">KMM developer</h4>

              <p class="service-item-text">Cross-Platform App using Kotlin lang</p>
            </div>
          </li>
        </ul>
      </section>

      <div class="modal-container" data-modal-container>
        <div class="overlay" data-overlay></div>

        <section class="testimonials-modal">
          <button class="modal-close-btn" data-modal-close-btn>
            <ion-icon name="close-outline"></ion-icon>
          </button>

          <div class="modal-img-wrapper">
            <figure class="modal-avatar-box">
              <img
                src="./assets/images/avatar-1.png"
                alt="Daniel lewis"
                width="80"
                data-modal-img
              />
            </figure>

            <img src="./assets/images/icon-quote.svg" alt="quote icon" />
          </div>

          <div class="modal-content">
            <h4 class="h3 modal-title" data-modal-title>Daniel lewis</h4>

            <time datetime="2021-06-14">14 June, 2021</time>

            <div data-modal-text>
              <p>
                Richard was hired to create a corporate identity. We were very pleased with the work
                done. She has a lot of experience and is very concerned about the needs of client.
                Lorem ipsum dolor sit amet, ullamcous cididt consectetur adipiscing elit, seds do et
                eiusmod tempor incididunt ut laborels dolore magnarels alia.
              </p>
            </div>
          </div>
        </section>
      </div>

      <!--
  - clients
-->

      <section class="clients">
        <h3 class="h3 clients-title">Languages and Tools</h3>

        <ul class="clients-list has-scrollbar">
          <li class="clients-item">
            <a href="#">
              <img
                src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Git_icon.svg/1024px-Git_icon.svg.png"
                alt="client logo"
              />
            </a>
          </li>
        </ul>
      </section>
    </article>
  </div>
</template>
<style scoped>
.clients a img {
  height: 80px;
  width: 80px;
}
</style>
