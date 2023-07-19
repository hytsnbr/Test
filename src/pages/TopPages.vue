<script setup lang="ts">
import FooterView from "@/components/FooterView.vue";
import HeaderView from "@/components/HeaderView.vue";

import CardItem from "@/components/CardItem.vue";

import { getRes } from "@/api";
import { Info, JsonData } from "@/api/types";

let data: Info[];
try {
  const jsonData: JsonData = await getRes();
  data = jsonData.info;
} catch (error) {
  console.error(error);
}
</script>

<template>
  <HeaderView></HeaderView>
  <main class="container mx-auto">
    <h1 class="text-xl font-extrabold">INDEX</h1>

    <section>
      <div class="grid grid-cols-2 gap-2">
        <template v-for="(value, index) in data" :key="index">
          <CardItem></CardItem>
        </template>
      </div>
    </section>
  </main>
  <FooterView></FooterView>
</template>
