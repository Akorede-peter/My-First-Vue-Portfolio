<template>
  <footer class="site-footer">
    <div class="footer-content">
      <a class="footer-logo" href="#home">KRYPTO</a>

      <nav class="footer-column" aria-label="Page links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#buy-nfts">Buy NFTs</a>
        <a href="#sell-nfts">Sell NFTs</a>
      </nav>

      <nav class="footer-column" aria-label="Market links">
        <h2>Market</h2>
        <a href="#browse">Browse NFTs</a>
        <a href="#buy-nfts">Buy NFTs</a>
        <a href="#sell-nfts">Sell NFTs</a>
      </nav>

      <nav class="footer-column" aria-label="Contact links">
        <h2>Contact</h2>
        <a href="mailto:hello@example.com">Email</a>
        <a href="#linkedin">LinkedIn</a>
        <a href="#instagram">Instagram</a>
        <a href="#twitter">Twitter</a>
      </nav>

      <div class="newsletter">
        <h2>Join our newsletter</h2>
        <form class="newsletter-form" @submit.prevent>
          <label class="visually-hidden" for="newsletter-email">
            Email Address
          </label>
          <input
            id="newsletter-email"
            type="email"
            placeholder="Email Address"
          />
          <button type="submit">SUBMIT</button>
        </form>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.site-footer {
  padding: 3rem 0 4rem;
  color: #fff;
  background:
    radial-gradient(ellipse at 88% 55%, rgba(91, 82, 180, 0.28), transparent 38%),
    #05052e;
}

.footer-content {
  width: 80%;
  max-width: 1100px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 0.7fr 0.7fr 0.7fr 1.8fr;
  gap: 1.5rem;
}

.footer-logo {
  color: #fff;
  font-size: 0.9rem;
  font-weight: 700;
  text-decoration: none;
}

.footer-column {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 0.55rem;
}

.footer-column h2,
.newsletter h2 {
  margin: 0 0 0.35rem;
  color: #fff;
  font-size: 0.8rem;
  font-weight: 600;
}

.footer-column a {
  color: #deddf0;
  font-size: 0.7rem;
  text-decoration: none;
}

.footer-column a:hover {
  color: #fff;
}

.newsletter-form {
  display: flex;
  align-items: center;
  gap: 0.7rem;
  margin-top: 0.8rem;
}

.newsletter-form input {
  width: 190px;
  padding: 0.7rem 1rem;
  border: 0;
  border-radius: 999px;
  outline: none;
  color: #fff;
  background: rgba(255, 255, 255, 0.08);
  font-size: 0.65rem;
}

.newsletter-form input::placeholder {
  color: #c7c5dc;
}

.newsletter-form button {
  padding: 0.7rem 1.2rem;
  border: 0;
  border-radius: 999px;
  color: #fff;
  background: #9188e8;
  font-size: 0.6rem;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
@media (max-width: 850px) {
  .footer-content {
    width: 88%;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 2rem 1.25rem;
  }

  .newsletter {
    grid-column: span 2;
  }

  .newsletter-form {
    width: 100%;
  }

  .newsletter-form input {
    flex: 1;
    min-width: 0;
  }
}

@media (max-width: 600px) {
  .site-footer {
    padding: 2.5rem 0;
  }

  .footer-content {
    width: 88%;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 2rem 1rem;
  }

  .newsletter {
    grid-column: 1 / -1;
  }

  .newsletter-form {
    gap: 0.5rem;
  }

  .newsletter-form input {
    width: auto;
    flex: 1;
    min-width: 0;
  }

  .newsletter-form button {
    padding: 0.7rem 1rem;
  }
}

@media (max-width: 380px) {
  .footer-content {
    width: 90%;
    gap: 1.5rem 0.75rem;
  }

  .footer-column a {
    font-size: 0.68rem;
  }

  .newsletter-form {
    flex-wrap: wrap;
  }

  .newsletter-form input {
    flex-basis: 100%;
    box-sizing: border-box;
  }
}
</style>