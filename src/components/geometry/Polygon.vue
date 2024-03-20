<template>
 <div id="container">

  <svg width="500" height="500"></svg>
 </div>
</template>

<script setup lang="ts">
import * as d3 from "d3";

var svg = d3.select("svg");

  // create a rectangle
  svg.append("rect")
    .attr("x", 50) // position the left side of the rectangle at x = 50
    .attr("y", 50) // position the top side of the rectangle at y = 50
    .attr("width", 200) // set the width of the rectangle to 200
    .attr("height", 100) // set the height of the rectangle to 100
    .attr("fill", "blue"); // set the fill color of the rectangle to blue
// container.append(svg.node())
</script>

<style lang="scss" scoped>

</style>