<script></script>

<template>
  <footer class="footer gradient">
    <div class="social">
      <a href="#"><i class="fab fa-facebook fa-2x"></i></a>
      <a href="#"><i class="fab fa-twitter fa-2x"></i></a>
      <a href="#"><i class="fab fa-youtube fa-2x"></i></a>
      <a href="#"><i class="fab fa-linkedin fa-2x"></i></a>
    </div>
    <p>Copyright &copy; 2024 - B.J November Tours &amp; Airport Shuttle Services</p>
  </footer>
</template>

<style lang="scss" scoped>
@import '@/assets/_shared.scss';

.gradient {
  background-image: linear-gradient(90deg, #324488 10%, #43bbfe 90%);
}
.footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: center;
  height: 200px;
}

.footer a {
  color: white;
  &:hover {
    color: #025ec2;
  }
}

p {
  color: white;
}

.social {
  display: flex;
  flex-direction: row;
  align-items: center;
  text-align: center;
  a {
    padding: 0 8px;
  }
}
</style>
