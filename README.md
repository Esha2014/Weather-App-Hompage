<!DOCTYPE html>
<html>
  <head>
    <title>My Weather App Homepage</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <style>
      body {
  min-height: 100vh;
  margin: 0;
  background: linear-gradient(to bottom, darkblue, blue, lightblue);
  background-repeat: no-repeat;
  background-size: cover;
  color: white;
  font-family: Arial, sans-serif;
  padding: 30px;
}

h1 {
  color: white;
  font-style: italic;
  margin: 0 0 10px;
}

.page-title {
  animation: slideIn 1s ease-out forwards;
  position: relative;
  opacity: 0;
}

h2 {
  margin-top: 10px;
}

.city-card {
  position: relative;
  display: inline-block;
  margin: 20px 0;
}

.city-image {
  height: 250px;
  width: 650px;
  border-radius: 20px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
  object-fit: cover;
  transition: 0.3s;
  display: block;
}

.city-image:hover {
  transform: scale(1.03);
}

.city-title {
  position: absolute;
  top: 35%;
  left: 37%;
  transform: translate(-50%, -50%);
  color: white;
  -webkit-text-stroke: 0.7px black;
  z-index: 1;
}

.city-link {
  position: absolute;
  top: 35%;
  left: 89%;
  transform: translate(-50%, -50%);
  color: darkblue;
  font-size: 15px;
  text-decoration: underline;
  z-index: 1;
}

@keyframes slideIn {
  from {
    transform: translateX(-100%);
    opacity: 0;
  }
  to {
    transform: translateX(0);
    opacity: 1;
  }
}
    </style>
    <h1 class="page-title">My Weather App Homepage</h1>
    <h2>Choose Your City</h2>

    <a href="https://karachitemp26.oneapp.dev/" target="_blank" rel="noopener noreferrer">
      <div class="city-card">
        <h1 class="city-title">Weather Forecast Of<br />KARACHI</h1>
        <img
          src="https://assets.st-note.com/production/uploads/images/243352076/rectangle_large_type_2_e576fe1ba07b1212c43ce5bf1a9600bc.jpeg"
          alt="Karachi city"
          class="city-image"
        />
        <h1 class="city-link">Click Here To Check Todays Forecast</h1>
      </div>
    </a>

    <a href="https://sukkurtemp26.oneapp.dev/" target="_blank" rel="noopener noreferrer">
      <div class="city-card">
        <h1 class="city-title">Weather Forecast Of<br />Sukkur</h1>
        <img
          src="https://www.thefridaytimes.com/digital_images/large/2022-03-07/a-sukkur-travel-guide-20-spots-of-historical-and-cultural-significance-around-the-city-1687413712-2731.jpg"
          alt="Sukkur city"
          class="city-image"
        />
        <h1 class="city-link">Click Here To Check Todays Forecast</h1>
      </div>
    </a>

    <a href="https://hyderabadtemp26.oneapp.dev/" target="_blank" rel="noopener noreferrer">
      <div class="city-card">
        <h1 class="city-title">Weather Forecast Of<br />Hyderabad</h1>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6dA9sVyVgSFqz1u_Fd8XNFLZh9uBryNdT67YqSD8qVw&s=10"
          alt="Hyderabad city"
          class="city-image"
        />
        <h1 class="city-link">Click Here To Check Todays Forecast</h1>
      </div>
    </a>

    <a href="https://lahorertemp26.oneapp.dev/" target="_blank" rel="noopener noreferrer">
      <div class="city-card">
        <h1 class="city-title">Weather Forecast Of<br />Lahore</h1>
        <img
          src="https://www.shutterstock.com/image-photo/lahore-pakistan-march-1st-2026-260nw-2749709539.jpg"
          alt="Lahore city"
          class="city-image"
        />
        <h1 class="city-link">Click Here To Check Todays Forecast</h1>
      </div>
    </a>

    <a href="https://islamabadtemp26.oneapp.dev/" target="_blank" rel="noopener noreferrer">
      <div class="city-card">
        <h1 class="city-title">Weather Forecast Of<br />Islamabad</h1>
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTF18IDrWFtrR30JLoeQ9LlsecVQz4w1xoodcZAGVyuMF2xeqOHMiK3DCU&s=10"
          alt="Islamabad city"
          class="city-image"
        />
        <h1 class="city-link">Click Here To Check Todays Forecast</h1>
      </div>
    </a>
  </body>
</html>
