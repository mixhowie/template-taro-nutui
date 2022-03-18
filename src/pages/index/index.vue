<template>
  <div class="index">
    <Header />
    <NumberDisplay />
    <NumberSubmit />

    <nut-row>
      <nut-col :span="24">
        <div class="flex-content">span:24</div>
      </nut-col>
    </nut-row>
    <nut-row>
      <nut-col :span="12">
        <div class="flex-content">span:12</div>
      </nut-col>
      <nut-col :span="12">
        <div class="flex-content flex-content-light">span:12</div>
      </nut-col>
    </nut-row>
    <nut-row>
      <nut-col :span="8">
        <div class="flex-content">span:8</div>
      </nut-col>
      <nut-col :span="8">
        <div class="flex-content flex-content-light">span:8</div>
      </nut-col>
      <nut-col :span="8">
        <div class="flex-content">span:8</div>
      </nut-col>
    </nut-row>
    <nut-row>
      <nut-col :span="6">
        <div class="flex-content">span:6</div>
      </nut-col>
      <nut-col :span="6">
        <div class="flex-content flex-content-light">span:6</div>
      </nut-col>
      <nut-col :span="6">
        <div class="flex-content">span:6</div>
      </nut-col>
      <nut-col :span="6">
        <div class="flex-content">span:6</div>
      </nut-col>
    </nut-row>
  </div>
</template>

<script>
import Header from "../../components/Header.vue";
import NumberDisplay from "../../components/NumberDisplay.vue";
import NumberSubmit from "../../components/NumberSubmit.vue";

export default {
  name: "Index",
  components: {
    Header,
    NumberDisplay,
    NumberSubmit,
  },
};
</script>

<style>
.index {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
