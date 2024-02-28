<script></script>

<template>
  <header class="hero">
    <div class="navbar top" id="navbar">
      <h1 class="logo">
        <span class="text-secondary"><img src="../assets/Images/Logo.png" alt="" />.J </span
        >November Shuttle Services
      </h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#cases">Cases</a></li>
          <li><a href="#blog">Blog</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
    <div class="content">
      <h1>Benjamin J November Tours &amp; Airport Shuttle Services</h1>
      <p>Providing world class shuttle services!</p>
      <a href="#contact" class="btn"><i class="fas fa-chevron-right"></i> Contact</a>
    </div>
  </header>
</template>

<style lang="scss">
@import '@/assets/_shared.scss';

.hero {
  background: url('../assets/Images/Van-Pictures/van1.jpeg') no-repeat center center/cover;
  height: 100vh;
  position: relative;
  color: white;
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #333 !important;
    color: white;
    opacity: 0.8;
    width: 100%;
    height: 70px;
    position: fixed;
    top: 0px;
    padding: 0 30px;
    transition: 0.5s;

    .logo {
      font-size: 2rem;
      font-weight: 300;
      .text-secondary {
        img {
          width: 3rem;
        }
      }
    }
    nav {
      ul {
        display: flex;
        a {
          color: white;
          padding: 10px 20px;
          margin: 0 5px;
        }
        a:hover {
          border-bottom: #43bbfe 2px solid;
        }
      }
    }
  }
  .top {
    background: transparent;
  }
  .content {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    height: 100%;
    padding: 0 20px;
    h1 {
      font-size: 35px;
    }
    p {
      font-size: 20px;
      max-width: 600px;
      margin: 20px 0 30px;
    }
  }
}

.hero::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.6);
}

.hero * {
  z-index: 10;
}

@media (max-width: 1080px) {
  .hero {
    .navbar {
      .logo {
        font-size: 1.5rem;
        font-weight: 200;
      }
    }
  }
}
@media (max-width: 768px) {
  .hero {
    .navbar {
      flex-direction: column;
      height: 120px;
      padding: 20px;
      .logo {
        font-size: 2rem;
        text-align: center;
      }
      a {
        padding: 10px 10px;
        margin: 0 3px;
      }
    }
  }
}

@media (max-width: 526px) {
  .hero {
    .navbar {
      height: 150px;
    }
  }
}
</style>
