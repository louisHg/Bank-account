<template>
  <q-page class="q-pa-lg">
    <div class="center">
      <div>
        <div class="titre q-my-md">
          Welcome to the
          <br />
          <span class="animated-text">Bank Account Manager project</span>
        </div>
        <div class="q-mb-md">
          <img
            src="../assets/bank-svgrepo-com.svg"
            alt=""
            class="rounded-circle"
            height="200"
            width="180"
          />
        </div>
        <p class="home q-mb-md">
          This application is designed to help to manage
          <br />
          users' bank accounts efficiently and securely.
          <br />
          With this tool an administrators can:
        </p>
        <ul class="home q-my-md remove-points">
          <li class="q-my-xs">
            Deposite and drop off money to the Bank Accounts
          </li>
          <li class="q-my-xs">View account balances</li>
          <li class="q-my-xs">Track transaction history</li>
        </ul>
        <div style="display: flex; justify-content: space-around">
          <a href="https://github.com/louisHg/Bank-account" target="_blank">
            <img
              src="../assets/github.svg"
              alt="Github Repository"
              height="50"
              width="50"
              class="pointer"
            />
          </a>
          <a href="https://www.linkedin.com/in/louis-huyghe" target="_blank">
            <img
              src="../assets/linkedin.svg"
              alt="LinkedIn Profile"
              height="50"
              width="50"
              class="pointer"
            />
          </a>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
