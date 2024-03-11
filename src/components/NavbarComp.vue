<script></script>

<template>
  <header class="hero">
    <div class="navbar top" id="navbar">
      <div class="logo">
        <img class="nav-logo" src="../assets/Images/Nav-Logo.png" alt="" />
      </div>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
    <div class="content">
      <h1>Benjamin J November Tours &amp; Airport Shuttle Services</h1>
      <p>Providing World Class Shuttle Services!</p>
      <a href="#contact" class="btn"><i class="fas fa-chevron-right"></i> Contact</a>
    </div>
  </header>
</template>

<style lang="scss">
@import '@/assets/_shared.scss';

.hero {
  background: url('../assets/Images/Hero.png') no-repeat center center/cover;
  height: 100vh;
  position: relative;
  color: white;
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    // flex-wrap: wrap;
    background: rgba(0.15, 0.15, 0.15, 0.4) !important;
    color: white;
    opacity: 0.8;
    width: 100%;
    height: 100px;
    position: fixed;
    top: 0px;
    // padding: 0 30px;
    transition: 0.5s;

    .logo {
      height: 100%;
      text-align: center;
      justify-content: center;
      align-items: center;
      .nav-logo {
        height: 100%;
        // width: 100%;
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
  background: rgba(0, 0, 0, 0.2);
}

.hero * {
  z-index: 10;
}

@media (max-width: 768px) {
  .hero {
    .navbar {
      flex-direction: column;
      justify-content: space-around;
      height: 130px;
      padding-bottom: 20px;
      .logo {
        height: 80%;
      }
      a {
        padding-left: 10px;
        padding-right: 10px;
        margin: 0 3px;
      }
    }
  }
}

@media (max-width: 526px) {
  .hero {
    .navbar {
      height: 150px;
      .logo {
        height: 60%;
      }
    }
  }
}

@media (max-width: 480px) {
  .hero {
    .navbar {
      height: 150px;
      .logo {
        height: 45%;
      }
      nav {
        ul {
          flex-wrap: wrap;
          justify-content: space-around;
          li {
            margin: 5px;
            a {
              font-size: 0.9rem;
            }
          }
        }
      }
    }
  }
}

@media (max-width: 390px) {
  .hero {
    .navbar {
      height: 200px;
    }
    .content {
      padding-top: 200px;
    }
  }
}
</style>
