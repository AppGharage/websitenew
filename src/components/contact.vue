<template>
  <div class="max-w-screen-xl mx-auto md:p-4 px-5 md:px-10 xl:px-0 space-y-16 md:space-y-24">
      <div class="flex flex-col lg:flex-row py-0 px-0 md:px-0 lg:mt-32 md:mt-10 mb-24">
        <div class="space-y-5 w-full lg:w-1/2 flex flex-col pb-10 lg:pb-0">
          <h2
            class="font-semibold text-2xl md:text-5xl tracking-normal text-gray-900 text-left"
          >
            Have a project in mind?
          </h2>
          <div class="flex flex-col">
            <div class="border-4 border-blue-400 w-1/3 mt-2"></div>
            
          </div>
          <p class="text-xl text-gray-900">
            Let us know how can help you.
          </p>
          <div class="flex items-start space-x-5 text-base font-medium text-gray-500">
            <span
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                /></svg></span
            ><span>info@appgharage.com</span>
          </div>
          <div class="flex items-start space-x-5 text-base font-medium text-gray-500">
            <span
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                /></svg></span
            ><span>(+233) 054 - 879 - 7248</span>
          </div>
        </div>
        <div class="w-full lg:w-1/2 md:mt-0 lg:px-10">
          <!-- <h2
            class="font-semibold text-3xl tracking-normal text-gray-900 text-left"
          >
            Got an Idea ? Send us a message. 
        </h2> -->
          <form class="w-full space-y-5 pt-10 rounded-lg">
            <div>
              <label for="price" class="block text-sm font-medium text-gray-700 mb-2"
                >Full name <span class="text-red-700 text-lg">*</span></label
              >
              <div
                class="relative w-full bg-white flex items-center rounded-md border-2 border-gray-200"
              >
                <input
                  type="text"
                  v-model="fullName"
                  class="px-3 py-3 bg-white w-full rounded-md focus:outline-none"
                  :class="[
                    fullnameValidation
                      ? 'focus:ring-1 focus:ring-green-400 text-gray-900'
                      : 'focus:ring-1 focus:ring-red-400 text-red-800',
                  ]"
                  @keyup="validatename()"
                />
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-8 w-8 text-green-500 mr-2 absolute right-0"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  v-if="fullnameValidation"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  />
                </svg>
              </div>
            </div>
            <div>
              <label for="price" class="block text-sm font-medium text-gray-700 mb-2"
                >Email <span class="text-red-700 text-lg">*</span></label
              >
              <div
                class="relative w-full bg-white flex items-center rounded-md border-2 border-gray-200"
              >
                <input
                  type="email"
                  v-model="email"
                  @keyup="validateEmail()"
                  class="px-3 py-3 bg-white w-full rounded-md focus:outline-none"
                  :class="[
                    emailValidation
                      ? 'focus:ring-1 focus:ring-green-400 text-gray-900'
                      : 'focus:ring-1 focus:ring-red-400 text-red-800',
                  ]"
                />
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-8 w-8 text-green-500 mr-2 absolute right-0"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  v-if="emailValidation"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  />
                </svg>
              </div>
            </div>
            <div>
              <label for="price" class="block text-sm font-medium text-gray-700 mb-2"
                >Tell us all about it <span class="text-red-700 text-lg">*</span></label
              >
              <textarea
                type="text"
                placeholder=""
                v-model="message"
                class="px-3 py-3 bg-white w-full focus:outline-none h-64 rounded-md border-2 border-gray-200"
              ></textarea>
            </div>
            <div
              class="bg-red-100 px-4 py-2 rounded-md text-xs md:text-sm flex items-center justify-start w-full mx-auto"
              v-if="formSubmission"
            >
              <svg viewBox="0 0 24 24" class="text-red-600 w-5 h-5 sm:w-5 sm:h-5 mr-3">
                <path
                  fill="currentColor"
                  d="M11.983,0a12.206,12.206,0,0,0-8.51,3.653A11.8,11.8,0,0,0,0,12.207,11.779,11.779,0,0,0,11.8,24h.214A12.111,12.111,0,0,0,24,11.791h0A11.766,11.766,0,0,0,11.983,0ZM10.5,16.542a1.476,1.476,0,0,1,1.449-1.53h.027a1.527,1.527,0,0,1,1.523,1.47,1.475,1.475,0,0,1-1.449,1.53h-.027A1.529,1.529,0,0,1,10.5,16.542ZM11,12.5v-6a1,1,0,0,1,2,0v6a1,1,0,1,1-2,0Z"
                ></path>
              </svg>
              <span class="text-red-800">
                Please fill all spaces and enter a valid email address
              </span>
            </div>
            <button
              class="w-full py-3 font-medium text-white text-base flex items-center justify-center space-x-2 bg-blue-700 rounded-br-2xl"
              @click.prevent="contact()"
            >
              <span
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 transform rotate-45 mb-1"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"
                  /></svg
              ></span>
              <span>Send Message</span>
            </button>
          </form>
        </div>
    </div>
    <transition
      enter-active-class="animate__animated animate__backInDown animate__faster"
      leave-active-class="animate__animated animate__fadeOutUpBig"
    >
      <Success v-if="success" />
    </transition>
    <transition
      enter-active-class="animate__animated animate__backInDown animate__faster"
      leave-active-class="animate__animated animate__fadeOutUpBig"
    >
      <Error v-if="error" />
    </transition>
  </div>
</template>

<script>
import axios from "axios";
import Success from "./success.vue";
import Error from "./error.vue";

export default {
  data() {
    return {
      fullName: "",
      email: "",
      message: "",
      error: false,
      success: false,
      formSubmission: false,
      emailValidation: false,
      fullnameValidation: false,
      fullnameValidationError: false,
    };
  },
  methods: {
    validatename: function () {
      var validName = /^[a-zA-Z]+ [a-zA-Z]+$/;
      if (this.fullName.match(validName)) {
        this.fullnameValidation = true;
      } else {
        this.fullnameValidation = false;
      }
    },

    validateEmail: function () {
      var validRegex = /^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/;
      if (this.email.match(validRegex)) {
        this.emailValidation = true;
      } else {
        this.emailValidation = false;
      }
    },
    contact: function () {
      if (
        this.fullnameValidation === true &&
        this.emailValidation === true &&
        this.message != ""
      ) {
        axios
          .post("https://getform.io/f/fbd05d3c-87b8-4954-a1b7-8e5158a5f530", {
            name: this.fullName,
            email: this.email,
            message: this.message,
          })
          .then(() => {
            this.success = true;
            this.fullName = this.email = this.message = "";
            this.fullnameValidation = this.emailValidation = false;
            this.formSubmission = false;
            setTimeout(() => {
              this.success = false;
            }, 3000);
          })
          .catch(() => {
            this.error = true;
            setTimeout(() => {
              this.error = false;
            }, 3000);
          });
      } else {
        this.formSubmission = true;
      }
    },
    sendMail: function () {
      axios
        .post("/sendmail", {
          from: this.email,
          name: this.fullName,
          to: "decryme@gmail.com",
          subject: "Node Contact Request",
          text: this.message,
        })
        .then((res) => console.log(res));
    },
  },
  components: { Success, Error },
};
</script>
