# Mern E-Store
## How to run this project on your local system?
1. In your code editor search for a link "https://estore-server.onrender.com" and replace them all with "http://localhost:5000".

2. Now go to the **"frontend"** folder, open the frontend folder in an integrated terminal and run the command **`npm install`** to install all the dependencies.

3. Now to run the fronted on your local system, run the command **`npm start`** in the same terminal.

4. Now go to the **"backend"** folder and open it in another integrated terminal, and run the command **`npm install`** again to install the backend dependencies.

5. In the backend folder's root directory create a **.env** file, and create 3 environment variables like shown below:

   - **JWT_SECRET** = (Generate or type out a random string of characters)
   - **PAYPAL_CLIENT_ID** = (Generate a Paypal client ID by visiting this link: https://developer.paypal.com/home)
   - **MONGODB_URI** = (Paste the MongoDB database connection link here. )

6. And run **`node server.js`** in the same backend terminal.

   Your app will be running in your browser on link **http://localhost/3000**
