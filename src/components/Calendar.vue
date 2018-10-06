<template>
  <div>
    <h2>Calendar</h2>
    <full-calendar :config="config" :events="events"></full-calendar>
  </div>
</template>

<script>
import 'fullcalendar/dist/fullcalendar.css';
import 'fullcalendar/dist/locale/es';
import 'fullcalendar/dist/gcal';

export default {
  name: 'calendar',

  data: () => ({
    config: {
      locale: 'es',
      googleCalendarApiKey: 'AIzaSyCfbXIvFdvtYLLFi8vtvxjZSSWuQc7GQpA',
      events: {
        googleCalendarId: 'tqrt63ftjinu72qtv4elb00lcs@group.calendar.google.com',
      },
      defaultView: 'month',
    },
    events: [],
  }),
};
</script>
