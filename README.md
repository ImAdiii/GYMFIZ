# GYMFIZ
GymFiz is a full-stack fitness web app built with HTML, CSS, JS, Node.js, Express, and MongoDB. It offers daily progress reports, nearby gym search, and BMI and calorie calculators to help users track goals, stay healthy, and discover fitness options—all in one convenient platform.

Of course! Here’s a more detailed **“How to Run”** section that also describes the MongoDB setup for your `README.md`:

---

### 🏃‍♂️ How to Run the Project

#### 1. **Clone the repository**

```bash
git clone https://github.com/your-username/gymfiz.git
cd gymfiz
```

#### 2. **Set up MongoDB**

* Make sure you have **MongoDB installed** and running locally, or use a **MongoDB Atlas** cloud instance.
* If using MongoDB locally:

  * Start the MongoDB service (`mongod`)
  * The default MongoDB URI is usually `mongodb://localhost:27017/gymfiz`

#### 3. **Create environment file**

Create a `.env` file in the project’s root directory and add:

```env
MONGODB_URI=mongodb://localhost:27017/gymfiz
PORT=5000
JWT_SECRET=your_secret_key
```

> Replace `MONGODB_URI` with your MongoDB connection string if you’re using MongoDB Atlas.

#### 4. **Install dependencies**

```bash
npm install
npm i express
npm i 
```

#### 5. **Start the server**

```bash
npm start
```

#### 6. **Access the application**

* Backend will run on `http://localhost:5000`.
* Front-end files (HTML, CSS, JS) can be opened directly in your browser or served via a separate static server.

---

✅ **Optional:**
If using MongoDB Atlas:

1. Create a free cluster at [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas)
2. Get the connection URI from the dashboard.
3. Replace the `MONGODB_URI` in your `.env` file with the new URI.

That’s it — GymFiz will be up and running! Let me know if you’d also like to add a section for **running tests** or **deploying**.
