# Frontend Practice Assignment

Your task is to consume the data from your Node.js API and display it beautifully using Tailwind CSS and Recharts.

## Requirements:
1.  **Data Fetching:**
    *   Create a component that uses `useEffect` to call `http://localhost:3001/api/signups`.
    *   Handle loading states and potential errors cleanly.
2.  **Data Visualization (Recharts):**
    *   Pass the fetched data into a Recharts `<BarChart />`.
    *   Make sure the chart has a responsive width.
3.  **Styling (Tailwind CSS):**
    *   Create a modern, clean dashboard layout.
    *   Add a sidebar on the left and a main content area on the right.
    *   Use some nice hover effects on buttons.

## Why is this good practice?
The interviewer wants to see you cleanly manage React state (`useState`, `useEffect`), safely type your API responses with TypeScript, and build a visually appealing layout without writing hundreds of lines of custom CSS.
