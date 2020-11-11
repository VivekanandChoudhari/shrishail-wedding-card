<template>
  <div class="people">
    <div class="n-elm n-ele-in-0">
      <h3 class="nm">With Best Compliments From</h3>
      <!-- <p>Yaladagi, Bhadrappagol & Rabakavi family</p> -->
      <p>Ramesh Choudhari</p>
      <p>Shanta Choudhari</p>
      <p>Halappa Choudhari</p>
      <p>Sonavva Choudhari</p>
      <p>Vivekanand Choudhari</p>
      <p>Chetan Choudhari</p>
    </div>
    <!-- <div class="n-elm n-ele-in-0">
      <h3 class="nm">स्वागतकांक्षी</h3>
      <p>Mr. & Mrs. Sonu Kumar Maurya</p>
      <p>Mr. & Mrs. Sumit Maurya</p>
      <p>Dheeraj, Sanidhya, Satvik</p>
    </div>
    <div class="n-elm n-ele-in-0">
      <h3 class="nm">विशेष आग्रह</h3>
      <p>Dheeraj, Sanidhya, Satvik</p>
    </div> -->
    <small>
        <b>
          Designed BY:
        </b>
        <span class="curve">Vivek C</span>
        <br>
        <small style="color: blue">choudharivivek555@gmail.com</small>
    </small>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.people {
  & > div {
    margin: 15px 5px;
    padding: 10px;
    border-radius: 4px;
  }
  padding: 10px;
  h3 {
    color: #507f52;
  }
  p {
    margin: 0px;
    padding: 5px 15px;
    color: #1a4487;
    // font-weight: bold;
  }
  small {
    float: right;
  }
}
</style>
