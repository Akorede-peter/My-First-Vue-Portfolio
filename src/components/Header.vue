<script setup>
import {ref} from 'vue'
</script>

<template>
  <header class="site-header">
    <nav class="header-nav" aria-label="Main navigation">
      <h1 class="logo">KRYPTO</h1>

        <div class="header-rightside">
            <ul class="nav-links">
                <li><a href="#about">ABOUT</a></li>
                <li><a href="#pricing">PRICING</a></li>
                <li><a href="#contact">CONTACT</a></li>
            </ul>

            <button class="buy-button" type="button">
            <span class="button-dot" aria-hidden="true"></span>
            BUY NFTS
            </button>     
        </div>
    </nav>
  </header>
</template>

<style scoped>
.site-header {
  width: 80%;
  margin: 0 auto;
  padding: 1.5rem 0;
}

.header-nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 2rem;
}

.logo {
  margin: 0;
  color: #fff;
  font-size: 1.2rem;
}

.header-rightside {
  display: flex;
  align-items: center;
  gap: 2rem;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 1.5rem;
  margin: 0;
  padding: 0;
  list-style: none;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
}

.nav-links a:hover {
  opacity: 0.75;
}

.buy-button {
  padding: 0.65rem 1rem;
  border: 0;
  border-radius: 0.5rem;
  background-color: #2d2879;
  color: #fff;
  cursor: pointer;
}
.buy-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.65rem 1rem;
  border: 0;
  border-radius: 0.5rem;
  background-color: #2d2879;
  color: #fff;
  cursor: pointer;
}

.button-dot {
  width: 0.65rem;
  height: 0.65rem;
  border-radius: 50%;
  background-color: #9091DC;
}

@media (max-width: 650px) {
  .site-header {
    width: 90%;
    padding: 1.25rem 0;
  }

  .header-nav {
    flex-wrap: wrap;
    gap: 1rem;
  }

  .logo {
    font-size: 1.1rem;
  }

  .header-rightside {
    display: contents;
  }

  .buy-button {
    margin-left: auto;
    padding: 0.6rem 0.85rem;
    font-size: 0.75rem;
  }

  .nav-links {
    order: 3;
    width: 100%;
    justify-content: space-between;
    gap: 0.5rem;
  }

  .nav-links a {
    font-size: 0.75rem;
  }
}

@media (max-width: 360px) {
  .site-header {
    width: 94%;
  }

  .nav-links a {
    font-size: 0.68rem;
  }

  .buy-button {
    padding: 0.55rem 0.7rem;
    font-size: 0.68rem;
  }
}
</style>