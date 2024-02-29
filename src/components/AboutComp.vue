<script></script>

<template>
  <section class="solutions flex-columns">
    <div class="row">
      <div class="column">
        <div class="column-1">
          <img src="../assets/Images/Grid-Pictures/pic5.jpg" alt="" />
        </div>
      </div>
      <div class="column">
        <div class="column-2 bg-primary">
          <h4>What you are looking for!</h4>
          <h2>We provide World Class Shuttle Services</h2>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita aspernatur non qui
            at, soluta voluptatem quibusdam nobis animi harum possimus nemo, modi ad placeat iure,
            libero doloribus velit temporibus nam!
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import '@/assets/_shared.scss';

@media (max-width: 768px) {
  .solutions {
    .row {
      flex-direction: column;
    }
  }
}
</style>
