# 🚗 MileTracker

**MileTracker** is a full-stack web application that allows users to log trips, calculate mileage between locations, view destination weather, and generate downloadable PDF trip reports.

The project focuses on accurate data handling, API-driven calculations, and presenting structured trip data in a clear, usable format.

---

## Project Context
MileTracker was developed as a group capstone project for a full-stack JavaScript bootcamp. The goal was to design and deploy a production-ready application that integrates multiple external data sources, supports authenticated users, and manages structured records over time.

---

## My Contributions
- Owned the design and implementation of the expense tracking feature from end to end
- Built GraphQL queries and mutations to create, update, delete, and retrieve expense records
- Implemented frontend components to manage expenses by trip and folder
- Developed logic to calculate total trip costs based on associated expenses
- Ensured expense data was consistently stored, loaded, and displayed across user sessions
- Resolved merge conflicts and stabilized expense-related features during team integration

---

## Skills Demonstrated
- Structured data modeling and validation
- CRUD operations on structured data
- GraphQL queries and mutations
- Data aggregation and calculation logic
- Frontend–backend integration
- Debugging and merge conflict resolution

---

## 🔧 Technologies Used
- **Frontend:** React, Vite, Apollo Client, TypeScript
- **Backend:** Node.js, Express, GraphQL (Apollo Server)
- **Database:** MongoDB (Mongoose)
- **Authentication:** JSON Web Tokens (JWT)
- **APIs:** OpenRouteService, OpenWeatherMap, UselessFacts, National Park Service, Google Maps
- **CI/CD:** GitHub Actions
- **Deployment:** Render

---

## 🚀 Features
- 🧭 Add trips by entering a start and end location
- 📏 Automatically calculates mileage between locations
- 🌦️ Displays weather for the destination
- 🗑 Delete trips individually
- 📄 Download a PDF report of all logged trips
- 🔐 User authentication with JWTs
- 📦 Protected API keys in environment variables
- ⚙️ GitHub Actions runs type checks on every push

---

## 🌍 Live Demo

- **Frontend:** [https://miletracker-client.onrender.com](https://miletracker-client.onrender.com)
- **Backend (GraphQL API):** [https://miletracker-wokk.onrender.com/graphql](https://miletracker-wokk.onrender.com/graphql)

## 📸 Screenshots

### Login Page

![Login Page](./images/MileTracker-LoginPage.jpg)

### Home Page

![Home Page](./images/MileTracker-HomePage.jpg)

### Vehicle Manager Page

![Vehicle Manager](./images/MileTracker-VehicleManager.jpg)

### Add Trip Page

![Add Trip Page](./images/MileTracker-AddTrip.jpg)

### Your Trips Page

![Your Trips Page](./images/MileTracker-TripDashboardR.jpg)

### Trip Report Printer Page

![Trip Report Printer Page](./images/MileTracker-TripReportPrinter.jpg)

<!-- ### Expense Report Printer Page

![Expense Report Printer Page](./images/<your-image-here>)-->

---

## 🧪 Local Development

1. Clone the repo
2. Run the backend:

```bash
cd server
npm install
npm run start
```

Run the Front End

```bash
cd client
npm install
npm run dev
```

Environmental variables:
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
OPENROUTE_API_KEY=your_route_api_key
WEATHER_API_KEY=your_weather_api_key


👏 Credits

Developed by Liebe, Colton, Maddie and Stephen as the final capstone project for a full-stack JavaScript bootcamp.
