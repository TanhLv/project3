<template>
  <div>
    <footer id="footer" style="background-color: black; height: 250px; margin-top: 5%;">
      <div>
        đây là footer
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "AppFooter",
  components: {

  },
  data() {

  }

}
</script>

<style>
/* .footer {
  background-color: #000;
  color: #fff;
} */
.footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.767);
  height: auto;
  color: aliceblue;
  display: flex;
  margin-top: 5%;
  height: 250px;
}
</style>