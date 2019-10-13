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
  width: 300px; 
  height: 173.21px;
  background-color: #27ae60;
  margin: 86.60px 0;
  border-left: solid 2px #333333;
  border-right: solid 2px #333333;
}

.hexagon:before,
.hexagon:after {
  content: "";
  position: absolute;
  z-index: 1;
  width: 212.13px;
  height: 212.13px;
  -webkit-transform: scaleY(0.5774) rotate(-45deg);
  -ms-transform: scaleY(0.5774) rotate(-45deg);
  transform: scaleY(0.5774) rotate(-45deg);
  background-color: inherit;
  left: 41.9340px;
}

.hexagon:before {
  top: -106.0660px;
  border-top: solid 2.8284px #333333;
  border-right: solid 2.8284px #333333;
}

.hexagon:after {
  bottom: -106.0660px;
  border-bottom: solid 2.8284px #333333;
  border-left: solid 2.8284px #333333;
}
</style>
