<template>
  <div class="offer">
    <img :src="offer.image" alt="Imagen de la empresa contratista" />
    <section>
      <h1 class="offer-title">{{ offer.title }}</h1>
      <p class="offer-description">{{ offer.description }}</p>
      <p class="offer-requirements">{{ offer.requirements }}</p>
      <span class="offer-salary">{{ offer.salary }}</span>
      <span class="offer-location">{{ offer.location }}</span>
      <span class="offer-date">{{ offer.date }}</span>
    </section>
  </div>
</template>

<script>
export default {
  name: "Offertemplate",
  props: ["offer"],
};
</script>
