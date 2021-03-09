<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Pyronix Demo App</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Pyronix Demo App</ion-title>
        </ion-toolbar>
      </ion-header>
      <p> Hello, this is a paragraph written by Tom Hosker on 09 Mar 2021. </p>
      <p> And this is an unordered list written on the same date: </p>
      <ul>
        <li> First item, </li>
        <li> Second item, etc. </li>
      </ul>
      <ExploreContainer name="Boo!" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  {
  name: 'Tab1',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>
