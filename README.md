# node-cxebwd

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/node-cxebwd)

firebase deploy
firebase init
firebase login

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
apiKey: "AIzaSyC9TWOHze2fGiUVNDCguK2XiKu7QF-l0jg",
authDomain: "music-autostreamer-ee1bc.firebaseapp.com",
projectId: "music-autostreamer-ee1bc",
storageBucket: "music-autostreamer-ee1bc.appspot.com",
messagingSenderId: "188458944520",
appId: "1:188458944520:web:061cd7fa7256771f4529bd",
measurementId: "G-HKM0BGPS6H"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/9.4.1/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.4.1/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyC9TWOHze2fGiUVNDCguK2XiKu7QF-l0jg",
    authDomain: "music-autostreamer-ee1bc.firebaseapp.com",
    projectId: "music-autostreamer-ee1bc",
    storageBucket: "music-autostreamer-ee1bc.appspot.com",
    messagingSenderId: "188458944520",
    appId: "1:188458944520:web:061cd7fa7256771f4529bd",
    measurementId: "G-HKM0BGPS6H"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
