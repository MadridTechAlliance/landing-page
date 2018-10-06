<template>
  <div id="app">
    <header>
      <span>Madrid Tech Alliance</span>
    </header>
    <main>
      <Hero />
      <Groups />
      <Calendar />
      <Talks />
    </main>
  </div>
</template>

<script>
import Hero from '@/components/Hero';
import Groups from '@/components/Groups';
import Calendar from '@/components/Calendar';
import Talks from '@/components/Talks';

export default {
  name: 'app',
  components: {
    Hero,
    Groups,
    Calendar,
    Talks,
  },
};
</script>

<style>

</style>
