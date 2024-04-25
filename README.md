# Business Dashboard README

This project is a Business Dashboard created using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides various components to visualize essential business metrics and insights. The dashboard utilizes the Recharts library for displaying graphical representations. Vite is used for the frontend development environment.

## Components

### 1. Profit and Revenue

- This component displays the overall profit and revenue data.

### 2. Revenue Month by Month

- Graphical representation of revenue trends month by month.

### 3. Campaigns and Targets

- Insights into ongoing campaigns and their performance against set targets.

### 4. Losses in Revenue

- Visualization of revenue losses over a specified period.

### 5. Profit Margins

- Analysis of profit margins to assess business profitability.

### 6. Product Prices vs Expenses

- Comparison between product prices and incurred expenses.

### 7. Expense Breakdown By Category

- Breakdown of expenses categorized by different expenditure types.

## **Machine Learning: Prediction Module**

In addition to the dashboard components, the project includes a Prediction module that utilizes machine learning for forecasting future revenue.

### Prediction Module Features:

- Utilizes regression algorithms to predict next year's revenue based on current month's data.

## Installation and Setup

Follow these steps to set up and run the project:

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies:
   ```
   npm install
   ```
4. Configure environment variables, including database connection details.
5. Populate the MongoDB database with relevant data.
6. Start the frontend development server:
   ```
   npm run dev
   ```
7. Start the backend server:
   ```
   npm start
   ```
8. Open the dashboard in your web browser.

## Technologies Used

- **MongoDB**: NoSQL database for storing business data.
- **Express.js**: Web application framework for Node.js used for backend development.
- **React.js**: JavaScript library for building user interfaces.
- **Node.js**: JavaScript runtime environment for server-side development.
- **Recharts**: A composable charting library for React.
- **Vite**: Next-generation frontend tooling for React development.

## Acknowledgements

- https://www.npmjs.com/package/regression
- https://www.npmjs.com/package/recharts
