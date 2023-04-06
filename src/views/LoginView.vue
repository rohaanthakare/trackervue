<script setup lang="ts">
import Card from 'primevue/card';
</script>

<template>
  <div class="grid m-0 justify-content-center t-outer-form">
    <div class="col-12 md:col-8 lg:col-6 xl:col-4">
      <Card class="shadow-8">
        <template #title>
          <div class="flex justify-content-center pt-2 pb-2">
            <img src="../assets/logos/tracker-light.png" style="width: 250px" />
          </div>
        </template>
        <template #content>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore sed consequuntur error repudiandae numquam
            deserunt quisquam repellat libero asperiores earum nam nobis, culpa ratione quam perferendis esse, cupiditate
            neque
            quas!
          </p>
        </template>
      </Card>
    </div>
  </div>
</template>
