<script setup></script>

<template>
  <header class="p-3 bg-white fixed-top">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center">
        <RouterLink to="/" class="d-flex align-items-center mb-2 mb-lg-0">
          <img
            src="@/assets/images/ic_logo_anima_t.svg"
            height="23"
            alt="Anima-T"
          />
        </RouterLink>
      </div>
    </div>
  </header>
</template>

<style scoped>
/* HEADER SECTION */

header .navbar-nav .nav-item a.nav-link {
  color: var(--accent-color);
  font-size: 0.9rem;
  transition: color 250ms ease-out;
}

header .navbar-nav .nav-item a.nav-link:hover {
  color: var(--primary-color);
}

header .navbar-nav .nav-item a.nav-link.active {
  color: var(--accent-color);
  font-weight: bold;
}

/* NAVBAR SECTION */

.navbar {
  transition: background-color 250ms ease-out;
  padding-top: 1em;
}

/* .navbar-brand {
  position: absolute;
  left: 50%;
  top: 0;
  transform: translateX(-50%) translateY(25%);
} */

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba(106, 42, 131, 0.9)' stroke-linecap='round' stroke-miterlimit='10' stroke-width='3.5' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
}

.navbar-light .navbar-toggler {
  border: none;
}

.navbar-toggler:focus {
  box-shadow: 0 0 0 0;
}
</style>
