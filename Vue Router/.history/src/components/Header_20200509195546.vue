<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
   
        <router-link to="/" tag="li"><a>Home <span class="sr-only">(current)</span></router-link>
    
        <router-link to="/user" tag="li">User</router-link>
    
    </ul>
  </div>
</nav>
</template>