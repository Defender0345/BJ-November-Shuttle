<script></script>

<template>
  <div class="line"></div>
  <div id="gallery" class="row">
    <div class="column">
      <img src="../assets/Images/Grid-Pictures/pic1.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic6.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic3.jpg" alt="" />
      <img src="../assets/Images/Van-Pictures/van1.jpeg" alt="" />
    </div>
    <div class="column small">
      <img src="../assets/Images/Grid-Pictures/pic5.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic2.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic10.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic8.jpg" alt="" />
    </div>
    <div class="column">
      <img src="../assets/Images/Grid-Pictures/pic9.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic7.jpg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic11.jpg" alt="" />
      <img src="../assets/Images/Van-Pictures/van4.jpeg" alt="" />
    </div>
    <div class="column small">
      <img src="../assets/Images/Grid-Pictures/pic4.jpg" alt="" />
      <img src="../assets/Images/Van-Pictures/van2.jpeg" alt="" />
      <img src="../assets/Images/Van-Pictures/van3.jpeg" alt="" />
      <img src="../assets/Images/Grid-Pictures/pic12.jpg" alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
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
