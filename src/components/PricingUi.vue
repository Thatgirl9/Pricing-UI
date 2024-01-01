<script setup></script>

<template>
  <div class="body-div">
    <div class="first-half">
      <div class="flex-div">
        <h1 class="header">Simple pricing for your business</h1>
        <p class="p-text">
          Plans that are carefully crafted to suit your business.
        </p>
      </div>
    </div>

    <div class="second-half">
      <!-- Shared Div -->

      <div class="shared-div">
        <div class="flex-semi-div">
          <!-- Grey Container -->
          <div class="grey-div">
            <div class="grey-semi-div">
              <p class="pro-p">Premium PRO</p>
              <h1 class="price">$329</h1>
              <p class="bill-p">billed just once</p>
              <button class="btn">Get Started</button>
            </div>
          </div>

          <!-- White Container -->
          <div class="white-div"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
:root {
  /* 16px = 1rem */

  /* COLORS */

  /* Text Colors */
  --text-color-primary: #f7fafc;
  --text-color-secondary: #2d3748;
  --text-color-tertiary: #171923;
  --text-color-1: #ffffff;

  /* Background Colors */
  --bg-color-primary: #6b46c1;
  --bg-color-secondary: #ffffff;
  --bg-color-tertiary: #805ad5;
  --bg-color-1: #652cd3;
  --bg-color-2: #d1d5db;

  /* Font Family */
  --inter-font: "Inter", sans-serif;
}

/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.body-div {
  height: 100vh;
  background-color: var(--bg-color-secondary);
  font-family: var(--inter-font);
}

.first-half {
  background-color: var(--bg-color-primary);
  padding: 2em;
  color: var(--text-color-1);
  height: 45vh;
  text-align: center;
  display: flex;
  /* justify-content: center; */
  /* align-items: center; */
  flex-direction: column;
}

.flex-div {
  display: flex;
  flex-direction: column;
  gap: 0.9em;
}

.header {
  font-size: 2.7rem;
  font-weight: 800;
}

.p-text {
  font-size: 1.2rem;
  color: var(--text-color-primary);
  font-weight: 500;
  opacity: 0.84;
}

.second-half {
  display: flex;
  justify-content: center;
  align-content: center;
}

.shared-div {
  border-radius: 12px;
  background: #fff;
  margin-top: -6.5em;

  /* xl */
  box-shadow: 0px 10px 10px -5px rgba(0, 0, 0, 0.04),
    0px 20px 25px -5px rgba(0, 0, 0, 0.1);
}

.grey-div {
  background-color: var(--bg-color-2);
  color: var(--text-color-tertiary);
  text-align: center;
  padding: 2.5em 0em;
  border-radius: 12px;
  width: 18em;
}

.grey-semi-div {
  padding: 0 2em;
  display: flex;
  flex-direction: column;
  gap: 0.5em;
  width: 100%;
}

.pro-p {
  font-size: 1.2rem;
  font-weight: 800;
}

.price {
  font-weight: 800;
  font-size: 2.5rem;
}

.bill-p {
  font-size: 1rem;
  font-weight: 500;
}

.btn {
  background-color: var(--bg-color-tertiary);
  color: var(--text-color-primary);
  border-radius: 8px;
  border: none;
  padding: 0.8em 3em;
  font-weight: 700;
  width: 100%;
}
</style>
