<template>
<header class="header">
    <div class="logo">
      <img src="https://www.freeiconspng.com/uploads/hd-youtube-logo-png-transparent-background-20.png" alt="Logo">
    </div>
    <div class="search-bar">
      <input type="text" placeholder="Search">
      <button>Search</button>
    </div>
    <div class="buttons">
      <button >Home</button>
      <button>Profile</button>
    </div>
  </header>
</template>

<script setup>

</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 20px;
  background-color: #333;
  color: white;
}

.logo img {
  height: 40px; /* Adjust as needed */
}

.search-bar input {
  padding: 5px;
  margin-right: 10px;
}

.search-bar button {
  padding: 5px 10px;
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

.buttons button {
  padding: 5px 10px;
  margin-left: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}
</style>