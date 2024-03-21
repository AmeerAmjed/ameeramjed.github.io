<template>
  <aside class="sidebar" data-sidebar>
    <div class="sidebar-info">
      <figure class="avatar-box">
        <img
          class="avatar-box"
          src="https://media.licdn.com/dms/image/D4D35AQHk_umZglhm_g/profile-framedphoto-shrink_800_800/0/1698139477702?e=1711490400&v=beta&t=OqThR525dehwandBlBNzWMHDww0xlMFkVN_uN6QzObg"
          alt="Ameer Amjed"
          width="80"
        />
      </figure>

      <div class="info-content">
        <h1 class="name" title="Ameer Amjed">Ameer Amjed</h1>

        <p class="title">Mobile developer</p>
      </div>

      <button class="info_more-btn" data-sidebar-btn>
        <span>Show Contacts</span>
        <ion-icon name="menu-outline"></ion-icon>
      </button>
    </div>

    <div class="sidebar-info_more">
      <div class="separator"></div>

      <ul class="contacts-list">
        <li class="contact-item">
          <div class="icon-box">
            <ion-icon name="mail-outline"></ion-icon>
          </div>

          <div class="contact-info">
            <p class="contact-title">Email</p>

            <a href="mailto:ameer.amjed98@gmail.com" class="contact-link"
              >ameer.amjed98@gmail.com</a
            >
          </div>
        </li>

        <li class="contact-item">
          <div class="icon-box">
            <ion-icon name="phone-portrait-outline"></ion-icon>
          </div>

          <div class="contact-info">
            <p class="contact-title">Phone</p>

            <a href="tel:+9647723395997" class="contact-link">+964 772 339 5997</a>
          </div>
        </li>

        <!-- <li class="contact-item">

      <div class="icon-box">
        <ion-icon name="calendar-outline"></ion-icon>
      </div>

      <div class="contact-info">
        <p class="contact-title">Birthday</p>

        <time datetime="1982-06-23">June 23, 1982</time>
      </div>

    </li> -->

        <li class="contact-item">
          <div class="icon-box">
            <ion-icon name="location-outline"></ion-icon>
          </div>

          <div class="contact-info">
            <p class="contact-title">Location</p>

            <address>Wasit, Iraq</address>
          </div>
        </li>
      </ul>

      <div class="separator"></div>

      <ul class="social-list">
        <li class="social-item">
          <a href="#" class="social-link">
            <ion-icon class="socials-icons" name="logo-linkedin"></ion-icon>
          </a>
        </li>

        <li class="social-item">
          <a href="#" class="social-link">
            <ion-icon class="socials-icons" name="logo-github"></ion-icon>
          </a>
        </li>

        <li class="social-item">
          <a href="#" class="social-link">
            <ion-icon class="socials-icons" name="logo-behance"></ion-icon>
          </a>
        </li>
      </ul>
    </div>
  </aside>
</template>
