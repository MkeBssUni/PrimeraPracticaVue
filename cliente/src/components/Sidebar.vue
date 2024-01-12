<template>
    <b-sidebar id="sidebar-1" shadow
    z-index="-1"
    visible
    no-close-on-route-change
    no-close-on-backdrop
    no-header-close
    >
      <b-nav vertical class="pt-5">
        <b-nav-item>
          <b-link :to="{name:'inicio'}">Inicio</b-link>
        </b-nav-item>
        <b-nav-item>
          <b-link :to="{name:'main'}">Main</b-link>
        </b-nav-item>
        <b-nav-item>
          <b-link :to="{name:'tercero'}">Tercero</b-link>
        </b-nav-item>
      </b-nav>
    </b-sidebar>
  </template>
  
  <style scoped>

  </style>
  