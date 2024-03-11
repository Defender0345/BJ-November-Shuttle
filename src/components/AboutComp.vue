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
          <h2>World Class, Luxurious in-vehicle Charter Service at Affordable Rates!</h2>
          <div class="line"></div>

          <p class="desc">
            Indulge in the ultimate wine tasting experience with our specialized wine tour shuttle
            services. Sit back, relax, and let our expert drivers chauffeur you to the finest
            wineries in the Cape Town region, where you can savor exquisite wines and breathtaking
            views.
          </p>
          <p class="desc">
            Get up close and personal with majestic marine life on our thrilling whale watching
            excursions. Our comfortable shuttles provide convenient transportation to and from the
            harbor, where you can embark on an unforgettable adventure at sea.
          </p>
          <p class="desc">
            Create lasting memories on your special day with our elegant wedding transportation
            services. From transporting guests between venues to providing luxurious getaway cars
            for the newlyweds, we ensure every detail is taken care of with professionalism and
            style.
          </p>
          <p class="desc">
            Make a grand entrance at your next function or event with our premium shuttle services.
            Whether it's a corporate gala, milestone celebration, or intimate gathering, our fleet
            of modern vehicles is equipped to accommodate groups of all sizes, ensuring a seamless
            and stylish arrival for you and your guests.
          </p>
          <p class="desc">
          Additionally, we offer optional extras such as:
          <ul>
            <li>- Trailer rental</li>
            <li>- Cross-country trips</li>
            <li>- Any additional services that may be required by for your trip.</li>
          </ul>
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
  text-shadow: 1px 1px 2px rgba(0.1, 0.1, 0.1, 0.4);
  
}

ul{
    text-shadow: 1px 1px 2px rgba(0.1, 0.1, 0.1, 0.4);
  }

h2 {
  font-size: 2.3rem !important;
  text-shadow: 1px 1px 2px rgba(0.15, 0.15, 0.15, 0.4);
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
