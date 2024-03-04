<script></script>

<template>
  <section id="about" class="solutions flex-columns">
    <div class="row">
      <div class="column">
        <div class="column-1">
          <img src="../assets/Images/Grid-Pictures/pic5.jpg" alt="" />
        </div>
      </div>
      <div class="column">
        <div class="column-2 bg-primary">
          <h3>World Class, Luxurious in-vehicle Charter Service at Affordable Rates!</h3>
          <div class="line"></div>
          <p class="desc">
            Embark on unforgettable wine tours, exhilarating whale watching adventures, and elegant
            weddings and functions with our specialized transportation services. We provide reliable
            shuttle solutions tailored to enhance your experience and ensure seamless travel from
            start to finish.
          </p>
          <p class="desc">
            Whether you're embarking on a wine tasting adventure, seeking close encounters with
            marine life, celebrating a special occasion, or attending a glamorous function, our
            transportation services are designed to elevate your experience and make every moment
            memorable. Contact us today to book your shuttle service and embark on your next
            unforgettable journey.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import '@/assets/_shared.scss';

.desc {
  margin: 10px 0 !important;
}

.line {
  width: 100%;
  height: 10px;
  background-image: linear-gradient(90deg, #2d8fc4 0%, #2d459e 100%);
}

@media (max-width: 768px) {
  .solutions {
    .row {
      flex-direction: column;
    }
  }
}
</style>
