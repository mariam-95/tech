
### `Firebase Authentication`
 We  use Firebase Authentication to allow users to sign in to our app using one sign-in methods : including email address and password sign-in , after sign-in user and bulid his CV by adding his experiences and upload it in our DB .

  [Enable to  Authentication by E-mail and Password :](C:\Users\TOSHIBA\Downloads\user-pass.png)
   
  ![alternativetext](homework/add-user.PNG)
  (login.png)
  (C:\Users\TOSHIBA\Desktop\login.png) 
  
 So we connect our app to Firebase :
 
 ### Initialize Firebase
```
   var config =
    { apiKey: "AIzaSyDIjXzl5bhjWdp1sMzEjjWQNugET-TD1a0", <br>
    authDomain: "fortydays1-7d14c.firebaseapp.com", <br>
    databaseURL: "https://fortydays1-7d14c.firebaseio.com", 
    projectId: "fortydays1-7d14c", storageBucket: "fortydays1-7d14c.appspot.com",
    messagingSenderId: "618062853732",
    appId: "1:618062853732:web:b80f534fc3851d2c", };

firebase.initializeApp(config);
```


### How To Run
 Clone the GitHub repository then write this command. 
### `npm install`

### `npm start`
 Open [http://localhost:3000](http://localhost:3000) to view it in the browser .
