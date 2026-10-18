// Import Firebase SDKs (Modular v10)
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
import { getDatabase, ref, set, get, update, onValue, push, remove } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-database.js";

const firebaseConfig = {
  apiKey: "AIzaSyDEFxZCVy9zy1MXD6KSL6v8YhEBl-GTP5E",
  authDomain: "darwin-hr-b3ff6.firebaseapp.com",
  databaseURL: "https://darwin-hr-b3ff6-default-rtdb.firebaseio.com",
  projectId: "darwin-hr-b3ff6",
  storageBucket: "darwin-hr-b3ff6.firebasestorage.app",
  messagingSenderId: "857574481786",
  appId: "1:857574481786:web:e4ce1117d41cce816b40c3",
  measurementId: "G-B8G8KEEW64"
};

const app = initializeApp(firebaseConfig);
const database = getDatabase(app);

export { database, ref, set, get, update, onValue, push, remove };
