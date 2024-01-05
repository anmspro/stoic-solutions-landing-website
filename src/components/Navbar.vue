
<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="../assets/images/aure-logo.png" alt="Stoic Solutions Logo" height="30">
        </a>
        <div class="navbar-text ml-auto">
          <strong>Stoic Solutions</strong>
        </div>
        <div class="collapse navbar-collapse">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
            <li class="nav-item"><a class="nav-link" href="#">About</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
    name: 'Navbar',
}
</script>

<style scoped>
.navbar {
    border-bottom: 2px solid #3498db;
}

/* .navbar-brand img {
    filter: brightness(0) invert(1);
} */

.navbar-text {
    font-size: 1.2rem;
    color: #3498db;
}

.navbar-nav .nav-link {
    color: #3498db;
}

.navbar-nav .nav-link:hover {
    color: #2980b9;
}
</style>
