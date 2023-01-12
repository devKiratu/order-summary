<script></script>

<template>
  <div class="card">
    <img
      class="hero-img"
      src="../assets/images/illustration-hero.svg"
      alt="hero-img"
    />
    <div class="card-content">
      <h2>Order Summary</h2>
      <p class="item-text">
        You can now listen to millions of songs, audio books and podcasts on any
        device anywhere you like.
      </p>
      <div class="plan">
        <div style="display: flex; align-items: center">
          <img
            class="icon"
            src="../assets/images/icon-music.svg"
            alt="music-icon"
          />
          <div>
            <p class="plan-name">Annual plan</p>
            <p class="plan-price">$59.99/year</p>
          </div>
        </div>
        <button class="change-plan">Change</button>
      </div>
      <button class="pay">Proceed to Payment</button>
      <button class="cancel">Cancel Order</button>
    </div>
  </div>
</template>

<style scoped>
.card {
  background: white;
  width: 90%;
  max-width: 400px;
  min-width: 300px;
  border-radius: 20px;
  overflow: hidden;
  text-align: center;
}

.hero-img {
  width: 100%;
  object-fit: contain;
}

.card-content {
  height: 400px;
  padding: 20px 30px;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}

h2 {
  color: var(--dark-blue);
  font-weight: 900;
}

.plan {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: var(--very-pale-blue);
  width: 100%;
  padding: 15px;
  border-radius: 10px;
  overflow: none;
}

.icon {
  margin-right: 20px;
}

.plan-name {
  color: var(--dark-blue);
  font-weight: bold;
}
.plan-price {
  color: var(--desaturated-blue);
}

.item-text {
  color: var(--desaturated-blue);
}

button {
  cursor: pointer;
}

.change-plan {
  outline: none;
  border: none;
  background-color: inherit;
  color: var(--bright-blue);
  text-decoration: underline;
  font-weight: bold;
}

.pay {
  border: none;
  outline: none;
  padding: 15px;
  width: 100%;
  border-radius: 10px;
  background-color: var(--bright-blue);
  color: white;
  font-weight: bold;
  box-shadow: 0 20px 15px 5px var(--pale-blue);
}

.cancel {
  border: none;
  outline: none;
  padding: 15px;
  width: 100%;
  color: var(--desaturated-blue);
  font-weight: bold;
  background-color: inherit;
}
</style>
