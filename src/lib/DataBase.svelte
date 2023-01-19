// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
    apiKey: "AIzaSyBRJBqarProQM21-Z-eKNp3uEKmEgAXcZk",
    authDomain: "lb-m151-2019-v1.firebaseapp.com",
    projectId: "lb-m151-2019-v1",
    storageBucket: "lb-m151-2019-v1.appspot.com",
    messagingSenderId: "309960868152",
    appId: "1:309960868152:web:83246b4f45c319c1f581cd",
    measurementId: "G-TXXJE0N8FC"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);