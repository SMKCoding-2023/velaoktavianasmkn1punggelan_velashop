<template>
    <div class="home">
      <div class="header">  
      </div>
      <div class="content">
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Home',
  }
  </script>
  
  <style scoped>
  /* Gaya khusus untuk halaman Home */
  .home {
    text-align: center;
    padding: 20px;
    background-image: url('/images/baground.jpg');
    background-size: cover;
    color: white;
  }
  
  .header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
  }
  
  .header p {
    font-size: 1.5em;
    color: #777;
  }
  
  .content h2 {
    font-size: 1.8em;
    margin-top: 20px;
  }
  
  .content ul {
    list-style-type: disc;
    font-size: 1.2em;
    text-align: left;
    padding-left: 20px;
  }
  
  /* Gaya tambahan untuk elemen list */
  .content li {
    margin: 10px 0;
  }
  
  /* Gaya untuk tautan jika Anda ingin menambahkan tautan navigasi */
  /* .content a {
    color: #007BFF;
    text-decoration: underline;
  } */
  </style>
