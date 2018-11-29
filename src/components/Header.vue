<template>
  <div id="header">
      <ul class="nav nav-pills navbar-fixed-top">
        <li class="nav-item">
        <a class="nav-link" href="#">Home</a>
    </li>
     <li class="nav-item">
       <a class="nav-link" href="#">About Us</a>
     </li>
     <li class="nav-item">
       <a class="nav-link" href="#">Facts</a>
     </li>
     <li class="nav-item">
       <a class="nav-link" href="#">Services</a>
     </li>
   </ul>
  </div>
</template>

<script>
export default {
    data() {
        return {
            show: true
        }
    }
}
</script>

<style>

#header .nav-item a {
    color: #fff;
    transition: all 2s ease;
}

#header .nav-item a:hover {
    background: transparent;
    color: #840000;
}

#header .nav-item a:focus {
    background: transparent;
}
</style>
