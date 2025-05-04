Conexion a la bdd

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDawiw9RbKSqAL03zVVo4LIOi-ggE01f8w",
  authDomain: "tasky-69b74.firebaseapp.com",
  projectId: "tasky-69b74",
  storageBucket: "tasky-69b74.firebasestorage.app",
  messagingSenderId: "1069303930447",
  appId: "1:1069303930447:web:c977ee712c5afcf5c9143a",
  measurementId: "G-0W7B1PMRD2"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
