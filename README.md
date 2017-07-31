React Admin AppWEB
================================

Installation / Running
----------------------

1. `git clone <repository-url>` this repository
2. change into the new directory
3. `npm install`
4. `npm start` will run the app
5. Visit the app at [http://localhost:3000](http://localhost:3000)

Deploy in Firebase
----------------------

1. `npm install -g firebase-tools` this repository
2. `firebase init`
3.  Firebase will prompt you to select a project select appweb-c37a1
4.  Configure and deploy Firebase Hosting sites with the Space key
5.  The directory name will be "dist"
3. `npm run build` will run the app
4. `firebase deploy`
5. Visit the app at [https://appweb-c37a1.firebaseapp.com/](https://appweb-c37a1.firebaseapp.com/)
