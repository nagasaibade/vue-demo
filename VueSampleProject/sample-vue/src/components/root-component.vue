<template>
  <div>
      <div>
          <input type="text" name="" id="input-area">
      </div>
    <div>
      <button id="number-button" onclick="myFunction()" value="1">1</button>
      <button id="number-button" value="2">2</button>
      <button id="number-button" value="3">3</button>
      <button id="number-button" value="c" style="background-color: rgb(102, 149, 177)">c</button
      ><br>
    </div>
    <div>
      <button id="number-button" value="4">4</button>
      <button id="number-button" value="5">5</button>
      <button id="number-button" value="6">6</button>
      <button id="number-button" value="+" style="background-color: rgb(98, 219, 124);">+</button><br />
    </div>
    <div>
      <button id="number-button" value="7">7</button>
      <button id="number-button" value="8">8</button>
      <button id="number-button" value="9">9</button>
      <button id="number-button" value="-" style="background-color: red">-</button><br />
    </div>
    <div>
      <button id="number-button" value="0" type="submit" >0</button>
      <button id="number-button" value=".">.</button>
      <button id="number-button" value="/" style="background-color: orange">%</button>
      <button id="number-button" value="*" style="background-color: green">x</button>
    </div>
    <div>
        <button id="number-button" style="background-color: rgb(226, 230, 16);  padding: 15px 155px;">=</button>
    </div>
  </div>
</template>

<script>
export default {
  components: "root-component",
};
</script>

<style>
#number-button {
  padding: 15px 32px;
  margin-right: 8px;
  margin-bottom: 8px;
  background-color:rgb(180, 208, 216);
}
#input-area {
  padding: 15px 75px;
  margin-right: 8px;
  margin-bottom: 8px;
  background-color: rgb(223, 238, 247);
}
</style>