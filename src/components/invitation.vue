<template>
  <div class="invitation">
    <div class="n-elm n-ele-in-0" style="padding: 15px; border-radius: 8px; position: relative">
      <div class="namste"></div>
      <div>
        <h1 class=" curve">Invitation</h1>
        <p class=" curve"><b>Sri. Ramesh H. Choudhari & Smt. Shanta R. Choudhari</b></p>
        <small>
          <p class="nm"><b>Add:</b> Shiragur, Raibag Talu, Belagavi Dist.</p>
          <p class="nm"><b>Cordially invites you to grace the wedding of their son</b></p>
        </small>
      </div>
    </div>
    <div class="n-elm n-ele-in-0" style="padding: 15px; border-radius: 8px;margin-top: 15px; position: relative">
      <div class="venue"></div>
      <div style="z-index: 10">
        <h1 class=" curve">Date & Venue</h1>
        <small>
          <p class="nm">
            Wednesday, 09-12-2020 on 10:30AM,
            Sri Shivashakti Kalyana manatapa new Sayyaji
            Rao Road, Near Bamboo Bazar, Mysore.
            <br>
          </p>
        </small>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.invitation {
  padding: 15px;
  text-align: center;
  color: #264653;
  .venue {
    position: absolute;
    top: 0px;
    left: 0px;
    bottom: 0px;
    right: 0px;
    z-index: 1;
    background-image: url('../assets/wedding-stage.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    opacity: 0.15;
    border-radius: 8px;
  }
  .namste {
    position: absolute;
    top: 0px;
    left: 0px;
    bottom: 0px;
    right: 0px;
    z-index: 1;
    background-image: url('../assets/Namaste.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    opacity: 0.15;
    border-radius: 8px;
  }
}
</style>
