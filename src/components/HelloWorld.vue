<script setup>
import { ref } from 'vue'
import titleIronMaiden from '../assets/iron maiden title.webp'
import theTrooper from '../assets/shows/the trooper show.webp'
import somewhereInTime from '../assets/shows/somewhere in time show.webp'
import peaceOfMind from '../assets/shows/peace of mind show.webp'
import powerslave from '../assets/shows/powerslave show.webp'
import fearOfTheDark from '../assets/shows/fear of the dark show.webp'
import theSeventhSonOfTheSeventhSonShow from '../assets/shows/seventh son of a seventh son show.webp'
import braveNewWorld from '../assets/shows/brave new world show.webp'
import theNumberOfTheBeast from '../assets/shows/the number of the beast show.webp'
import theBookOfSouls from '../assets/shows/the book of souls show.webp'
import acesHigh from '../assets/shows/aces high show.webp'
import killers from '../assets/shows/killers show.webp'
import theFinalFrontier from '../assets/shows/the final frontier show.webp'
</script>

<template>
  <img class="img-title" :src="titleIronMaiden" alt="Iron Maiden Title">
  <p>A fan page for the legendary band Iron Maiden dedicated to their musics and your mascot Eddie and his versions of
    the all times</p>
  <section class="card-list">
    <div class="card">
      <img :src="theTrooper" alt="The Trooper Card">
      <h3 class="card-title">The Trooper</h3>
    </div>
    <div class="card">
      <img :src="somewhereInTime" alt="Somewhere in Time Card">
      <h3 class="card-title">Somewhere in Time</h3>
    </div>
    <div class="card">
      <img :src="peaceOfMind" alt="Peace of Mind Card">
      <h3 class="card-title">Peace of Mind</h3>
    </div>
    <div class="card">
      <img :src="powerslave" alt="Powerslave Card">
      <h3 class="card-title">Powerslave</h3>
    </div>
    <div class="card">
      <img :src="fearOfTheDark" alt="Fear of the Dark Card">
      <h3 class="card-title">Fear of the Dark</h3>
    </div>
    <div class="card">
      <img :src="theSeventhSonOfTheSeventhSonShow" alt="Seventh Son of a Seventh Son Card">
      <h3 class="card-title">Seventh Son of a Seventh Son</h3>
    </div>
    <div class="card">
      <img :src="braveNewWorld" alt="Brave New World Card">
      <h3 class="card-title">Brave New World</h3>
    </div>
    <div class="card">
      <img :src="theNumberOfTheBeast" alt="The Number of the Beast Card">
      <h3 class="card-title">The Number of the Beast</h3>
    </div>
    <div class="card">
      <img :src="theBookOfSouls" alt="The Book of Souls Card">
      <h3 class="card-title">The Book of Souls</h3>
    </div>
    <div class="card">
      <img :src="acesHigh" alt="Aces High Card">
      <h3 class="card-title">Aces High</h3>
    </div>
    <div class="card">
      <img :src="killers" alt="Killers Card">
      <h3 class="card-title">Killers</h3>
    </div>
    <div class="card">
      <img :src="theFinalFrontier" alt="The Final Frontier Card">
      <h3 class="card-title">The Final Frontier</h3>
    </div>
  </section>

</template>
