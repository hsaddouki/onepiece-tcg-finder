<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template fluid>
  <div class="container-fluid">
    <div class="op-sets">
      <div class="row">
        <div class="col-md-12 text-center">
          <h3 class="c-white">SETS</h3>
        </div>
      </div>
      <div class="row">
        <div class="row mt-4">
          <div class="col-md-4">
            <div class="card card-op card-op1">
              <img alt="OP01" class="w-100 center-block card-img-top" src="@/assets/OP01.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP01</b></p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card card-op card-op2">
              <img alt="OP02" class="w-100 center-block card-img-top" src="@/assets/OP02.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP02</b></p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card card-op card-op3">
              <img alt="OP03" class="w-100 center-block card-img-top" src="@/assets/OP03.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP03</b></p>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-4">
          <div class="col-md-4">
            <div class="card card-op card-op4">
              <img alt="OP04" class="w-100 center-block card-img-top" src="@/assets/OP04.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP04</b></p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card card-op card-op5">
              <img alt="OP05" class="w-100 center-block card-img-top" src="@/assets/OP05.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP05</b></p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card card-op card-op6">
              <img alt="OP06" class="w-100 center-block card-img-top" src="@/assets/OP06.jpg" />
              <div class="card-body">
                <p class="card-text text-center"><b>OP06</b></p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.c-white {
  color: white !important;
}
.op-sets {
  padding: 7rem;
}
.card-op {
  cursor: pointer;
  color: white !important;
}
.card-op1 {
  background-color: #a11818;
}
.card-op2 {
  background-color: #3f3f3f;
}
.card-op3 {
  background-color: #cf4fc5;
}
.card-op4 {
  background-color: #ff92a5;
}
.card-op5 {
  background-color: #d5e964;
}
.card-op6 {
  background-color: #5bbf4a;
}
</style>
