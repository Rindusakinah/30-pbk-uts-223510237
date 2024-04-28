<template>
  <div class="home">
    <div class="welcome-container">
      <h1 class="welcome-title">Welcome to Rindu To-Do List!</h1>
      <p class="welcome-message">Semoga Aplikasi ini dapat membantu harimu!</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>

<style>
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Fills the entire viewport height */
  background-color: #f5f5f5; /* Light gray background */
}

.welcome-container {
  text-align: center;
  padding: 20px;
  border-radius: 5px;
  background-color: #fff; /* White background for the welcome message */
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
}

.welcome-title {
  font-size: 2rem;
  margin-bottom: 10px;
}

.welcome-message {
  color: #666; /* Grayish text for the message */
}
</style>
