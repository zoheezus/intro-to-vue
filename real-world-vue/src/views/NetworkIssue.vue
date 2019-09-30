<template>
  <div>
    <h>Uh-Oh!</h>
    <h3>
      It looks like you're experiencing some network issues. Please click the
      back button and try again
    </h3>
    <router-link :to="{ name: 'event-list' }"
      >Or go back to the homepage</router-link
    >
  </div>
</template>
