<template>
    <div>
        <div class="hexagon"></div>
    </div>
</template>

<script>
export default {
  data () {
    return {
      hexagon: function () {
      }
    }
  }

}
</script>

<style>
.hexagon {
  position: relative;
  width: 25px; 
  height: 14.43px;
  background-color: #27ae60;
  margin: 7.22px 0;
  border-left: solid 1px #333333;
  border-right: solid 1px #333333;
}

.hexagon:before,
.hexagon:after {
  content: "";
  position: absolute;
  z-index: 1;
  width: 17.68px;
  height: 17.68px;
  -webkit-transform: scaleY(0.5774) rotate(-45deg);
  -ms-transform: scaleY(0.5774) rotate(-45deg);
  transform: scaleY(0.5774) rotate(-45deg);
  background-color: inherit;
  left: 2.6612px;
}

.hexagon:before {
  top: -8.8388px;
  border-top: solid 1.4142px #333333;
  border-right: solid 1.4142px #333333;
}

.hexagon:after {
  bottom: -8.8388px;
  border-bottom: solid 1.4142px #333333;
  border-left: solid 1.4142px #333333;
}

</style>
