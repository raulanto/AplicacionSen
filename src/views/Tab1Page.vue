<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Grid</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <b>Column 2 has <code>size</code> set to <code>"8"</code></b>
      <ion-grid>
        <ion-row>
          <ion-col>1</ion-col>
          <ion-col size="8">2</ion-col>
          <ion-col>3</ion-col>
        </ion-row>
      </ion-grid>
    
      <b>Columns 3 & 4 have <code>size</code> set to <code>"3"</code></b>
      <ion-grid>
        <ion-row>
          <ion-col>1</ion-col>
          <ion-col>2</ion-col>
          <ion-col size="3">3</ion-col>
          <ion-col size="3">4</ion-col>
          <ion-col>5</ion-col>
          <ion-col>6</ion-col>
        </ion-row>
      </ion-grid>
    
      <b>Columns 1 & 2 have <code>size</code> set to <code>"4"</code></b>
      <ion-grid>
        <ion-row>
          <ion-col size="4">1</ion-col>
          <ion-col size="4">2</ion-col>
          
        </ion-row>
      </ion-grid>

    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent,IonGrid,IonRow,IonCol } from '@ionic/vue';
// import ExploreContainer from '@/components/ExploreContainer.vue';

</script>

<style>
ion-col {
  background-color: #135d54;
  border: solid 1px #fff;
  color: #fff;
  text-align: center;
}
</style>