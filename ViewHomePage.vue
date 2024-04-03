<template>
    <div class="container">
      <div class="small-card">
        <img src="https://m.media-amazon.com/images/I/512fqKl2HpL._AC_UF1000,1000_QL80_.jpg" alt="Card Image" class="card-image">
        <div class="card-content">
          <h3>Title</h3>
          <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisi.</p>
          <p>Views: 34000</p>
        </div>
        <input type="text" placeholder="Enter your comment" v-model="comment" class="comment-input">
      </div>
    </div>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
  }
  
  .small-card {
    border: 2px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    max-width: 600px; 
    margin-top: 20px; 
  }
  
  .card-image {
    width: 100%;
    max-height: 400px; 
    object-fit: cover;
    border-radius: 10px 10px 0 0; 
  }
  
  .card-content {
    padding: 20px 0; 
  }
  
  h3 {
    font-size: 24px;
    margin-bottom: 10px;
  }
  
  p {
    font-size: 16px;
    color: #666;
    margin-bottom: 10px;
  }
  
  .comment-input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }
  </style>
  