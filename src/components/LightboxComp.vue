<script></script>

<template>
  <div class="line"></div>
  <div id="gallery" class="row">
    <div class="column">
      <img src="../assets/Images/Grid-Pictures/pic1.jpg" alt="Picture of horses in nature" />
      <img src="../assets/Images/Grid-Pictures/pic6.jpg" alt="Picture of Cape Town city center" />
      <img
        src="../assets/Images/Grid-Pictures/pic3.jpg"
        alt="Picture of old dutch style wine farm"
      />
      <img
        src="../assets/Images/Grid-Pictures/pic14.jpg"
        alt="Picture of the Waterfront in Cape Town"
      />
    </div>
    <div class="column">
      <img
        src="../assets/Images/Grid-Pictures/pic13.jpg"
        alt="Picture of an art installation in a mall"
      />
      <img src="../assets/Images/Grid-Pictures/pic10.jpg" alt="Picture of Table Mountain" />
      <img
        src="../assets/Images/Grid-Pictures/pic8.jpg"
        alt="Picture of clients next to the shuttle"
      />
      <img src="../assets/Images/Grid-Pictures/pic7.jpg" alt="Picture of Strand beach" />
    </div>
    <div class="column">
      <img src="../assets/Images/Grid-Pictures/pic2.jpg" alt="Picture of nature" />
      <img
        src="../assets/Images/Grid-Pictures/pic9.jpg"
        alt="Picture of a kite surfer getting ready"
      />
      <img
        src="../assets/Images/Grid-Pictures/pic11.jpg"
        alt="Picture of District 6 in Cape Town"
      />
      <img
        src="../assets/Images/Van-Pictures/van4.jpeg"
        alt="Picture of the inside of the shuttle"
      />
    </div>
    <div class="column">
      <img src="../assets/Images/Grid-Pictures/pic4.jpg" alt="Picture of snowy capped mountains" />
      <img
        src="../assets/Images/Grid-Pictures/pic15.jpg"
        alt="Picture of clients and the shuttle"
      />
      <img
        src="../assets/Images/Van-Pictures/van3.jpeg"
        alt="Picture of the driver section of the shuttle"
      />
      <img
        src="../assets/Images/Grid-Pictures/pic12.jpg"
        alt="Picture of Cape Town from Table Mountain"
      />
    </div>
  </div>
</template>

<style lang="scss" scoped>
#gallery {
  background: linear-gradient(90deg, #43bbfe 0%, #324488 60%);
}
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

.column {
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

@media screen and (max-width: 800px) {
  .column {
    flex: 50% !important;
    max-width: 50% !important;
  }
}

@media screen and (max-width: 600px) {
  .column {
    flex: 100% !important;
    max-width: 100% !important;
  }

  .small {
    display: none;
  }
}
</style>
