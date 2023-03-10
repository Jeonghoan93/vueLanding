<template>
          <div class="cover-photo">
  

    <div class="header">
      <h1>Vue 360 Course</h1>
      <h2>Enter your email and receive a free cheat sheet, <br />and I'll update you on the course!</h2>
      <form class="email-form">
        <input id="email" type="email" placeholder="youremail@example.com">
        <button class="button1">Send me the cheat sheet for free</button>
      </form>
      <p class="privacy">We respect your privacy. Unsubscribe at anytime.</p>
      <button class="button2">Built with ConvertKit</button>
    </div>

  </div>
</template>

<style>
body {
  height: 100%;
  margin: 0;
  padding: 0;
}
.cover-photo {
  display: flex;
  flex-direction: column;
  background-image: url('./bg.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  width: 100vw;
  position: relative;
}

.cover-photo::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
   background-color: rgba(0, 0, 0, 0.55);
}

.header {
    margin-top: 50px;
  position: relative;
  z-index: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
    color: #fff;
}

h1 {

  font-size: 3.2rem;
  font-weight: 700;
  margin-bottom: 2rem;
}

h2 {
  font-size: 1.3rem;
  font-weight: 500;
  color: #f1f1f1;
  margin-bottom: 2rem;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 2rem;
}


input[type="email"] {
    margin-top: 60px;
  padding: 0.5rem;
  width: 100%;
  max-width: 20rem;
  border-radius: 0.5rem;
  border: 1px solid #ccc;
  margin-bottom: 1rem;
}

.button1 {
  background-color: #1e8859;
  color: #ffffff;
  font-size: 1rem;
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
  border: none;
  cursor: pointer;
}

.button2 {
    margin-top: 30px;
  background-color: #ccfafa;
  color: #646262;
  font-weight:500;
  font-size: 0.8rem;
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
  border: none;
  cursor: pointer;
}



.privacy {
    margin-top: 50px;
  font-size: 1rem;
  margin-bottom: 1rem;
}

.convertkit {
  font-size: 1.2rem;
  color: #42b883;
}
</style>
