<template>
  <div id="skyways-project">
    
    <nav class="navbar">
      <h2 class="logo">SkyWays</h2>
      <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#owner">Owner</a>
        <a href="#tours">Tours</a>
        <a href="#references">References</a>
      </div>
    </nav>

    <h1 class="sky-text">SkyWays Travel Agency</h1>

    <p class="intro">
      Welcome to <strong>SkyWays Travel Agency</strong><br>
      We help passengers book airline tickets at the lowest possible price.<br><br>
      Travel smart. Travel affordable. Travel with SkyWays.
    </p>

    <img class="hero-img"
      src="https://images.unsplash.com/photo-1526778548025-fa2f459cd5c1"
      alt="Travel">

    <div class="container">
      <div>
        <h2>Lowest Ticket Finder</h2>
        <p>
          We compare airline fares to help you find the most affordable flight
          for your destination.
        </p>
        <button>Search Flights</button>
      </div>

      <div>
        <h2>Easy Registration</h2>
        <p>
          Create an account to receive travel updates, booking reminders,
          and exclusive promos.
        </p>
        <button>Register Now</button>
      </div>

      <div>
        <h2>Reliable Service</h2>
        <p>
          SkyWays ensures safe, reliable, and stress-free booking
          for local and international travel.
        </p>
      </div>
    </div>

    <h1 id="owner">About the Owner</h1>

    <div class="container">
      <div>
        <img class="owner-img" src="https://scontent.fmnl17-8.fna.fbcdn.net/v/t39.30808-6/572745873_4205598996395473_8046824233149610494_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=6ee11a&_nc_eui2=AeEp4bawIA0pomz4Lz-3bQH5DcwAhunZNVANzACG6dk1UM_5xKa_rhLIBeGsS01q9uLM02Yyn1J6jLqWWcGtAxPN&_nc_ohc=ZWkQBH_BAl4Q7kNvwF16z_g&_nc_oc=AdnV7262RxsnrTSIZ-VUBJewJQPrtlzDoW3ZdfMGZvPxeSZ1UIKRkslvtHqF0RgRi94&_nc_zt=23&_nc_ht=scontent.fmnl17-8.fna&_nc_gid=h3eaK0vsaZsO-GMXlD48cw&oh=00_AfpEePJl5QJk5hxRIjwgox5MsUdvFI5pXJZY65hoIS9P8Q&oe=69745B9A" alt="Rafael Martinez">
        <h2>Rafael Laurence E. Martinez</h2>
        <p>
          <strong>Owner & Founder</strong><br><br>
          Rafael Laurence E. Martinez is the founder and owner of SkyWays Travel Agency.
          As a BSIT student, he combines technology and business to develop a modern,
          user-friendly, and affordable travel booking platform.
        </p>
      </div>

      <div>
        <h2>Vision</h2>
        <p>
          To become a trusted travel agency that allows people to explore
          destinations while spending less.
        </p>
      </div>

      <div>
        <h2>Mission</h2>
        <p>
          To provide affordable travel options, efficient service,
          and a simple online booking experience.
        </p>
      </div>
    </div>

    <h1 id="tours">Top Tourist Spots in the Philippines</h1>

    <div class="container">
      <div>
        <img src="https://media.istockphoto.com/id/685040322/photo/boracay-island-aerial-view-western-visayas-philippines.jpg?s=612x612&w=0&k=20&c=wUxUbayAjvsR2ABNoMUYLGI13DbUj0W_abb1DhU8pd4="
              alt="Boracay">
        <h2>Boracay</h2>
        <p>White sand beaches and nightlife</p>
        <p><strong>3 Days / 2 Nights</strong></p>
        <p>₱4,999 <span class="promo">PROMO</span></p>
      </div>

      <div>
        <img src="https://t4.ftcdn.net/jpg/03/05/21/23/360_F_305212356_Gq63F2I8WbcvalHbucwbHcvQhsjh5YzB.jpg"
              alt="Palawan">
        <h2>Palawan</h2>
        <p>Crystal-clear lagoons</p>
        <p><strong>4 Days / 3 Nights</strong></p>
        <p>₱6,999 <span class="promo">PROMO</span></p>
      </div>

      <div>
        <img src="https://www.abrahamtours.com/philippines/wp-content/uploads/2023/07/Abraham-Bohol-tours-countryside-june-2024-2.webp"
              alt="Bohol">
        <h2>Bohol</h2>
        <p>Chocolate Hills experience</p>
        <p><strong>3 Days / 2 Nights</strong></p>
        <p>₱5,499 <span class="promo">PROMO</span></p>
      </div>

      <div>
        <img src="https://discoversiargao.com/images/com_adsmanager/contents/siargao-tour-packages_18_2.jpg"
              alt="Siargao">
        <h2>Siargao</h2>
        <p>Surfing capital of PH</p>
        <p><strong>4 Days / 3 Nights</strong></p>
        <p>₱5,999 <span class="promo">PROMO</span></p>
      </div>
    </div>

    <h1 id="references">References</h1>

    <ul class="references">
      <li>Images sourced from Unsplash</li>
      <li>Images sourced from iStockphoto</li>
      <li>Images sourced from Freepik</li>
    </ul>

    <footer>
      <p>© 2026 SkyWays Travel Agency | All Rights Reserved</p>
    </footer>

  </div>
</template>

<script setup>
// No extra logic needed for the basic migration
</script>

<style>
/* --- Your New CSS Integrated Below --- */
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #1A1A1A;
  color: #F1F1F1;
  text-align: center;
}

.sky-text {
  font-size: 48px;
  font-weight: bold;
  background: linear-gradient(to right, #87CEEB, #1E90FF);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #111;
  padding: 15px 30px;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.nav-links a {
  color: #FFD700;
  text-decoration: none;
  margin: 0 10px;
}

.nav-links a:hover {
  text-decoration: underline;
}

/* Headings */
h1 {
  color: #FFD700;
  margin-top: 40px;
}

/* Hero */
.hero-img {
  width: 80%;
  max-width: 600px;
  border-radius: 10px;
  margin: 20px 0;
}

/* Intro */
.intro {
  max-width: 800px;
  margin: auto;
}

/* Flex Containers */
.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}

.container div {
  background: #2C2C2C;
  width: 260px;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.4);
  transition: transform 0.3s;
}

.container div:hover {
  transform: scale(1.05);
}

/* Images */
.container img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}

/* Buttons */
button {
  background: #FFD700;
  border: none;
  padding: 10px 15px;
  border-radius: 6px;
  cursor: pointer;
}

button:hover {
  background: orange;
}

/* Promo */
.promo {
  background: red;
  color: white;
  padding: 4px 6px;
  border-radius: 5px;
  font-size: 12px;
}

/* References */
.references {
  list-style: none;
  padding: 0;
}

/* Footer */
footer {
  margin-top: 40px;
  padding: 20px;
  background: #111;
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
    align-items: center;
  }

  .navbar {
    flex-direction: column;
  }
}

.owner-img {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid #FFD700;
  margin-bottom: 10px;
}
</style>