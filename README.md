# Crypto_live_dashboard
# Description
It is a Live auto updating Dashboard. This dashboard visualizes Crypto Market Data. Data used is dynamic, coming directly from crypto API. 
Creating a crypto live dashboard using React with live data fetching from an API and interactive features like a dropdown to select different currencies is a great project. To implement this, i've used ApexCharts for rendering dynamic and interactive charts. 

‣ ApexCharts Overview:
ApexCharts is a popular JavaScript charting library that allows you to create beautiful and interactive charts for your web applications. It is well-suited for creating real-time and dynamic charts, making it a perfect choice for your crypto live dashboard project.

‣ Chart Component:
In my React project, i've created a chart component that utilizes ApexCharts to render the cryptocurrency price data dynamically. This component includes:

‣ State Management: I manage the state of the chart data, allowing it to update in real-time as new data is fetched from the API.

‣ Dynamic Data: I use the data fetched from the API to update the chart's data series whenever the user selects a different currency.

‣ Real-time Data Updates:
ApexCharts supports real-time updates, which means that as new data arrives from the API, you can use JavaScript intervals or web sockets to keep the chart updated live without requiring a full page refresh.

‣ User Interaction:
Users can interact with the chart by zooming in, panning, or hovering over data points to view detailed information. You may also include a tooltip that displays the exact value of a data point when the user hovers over it.

► you need to install :
    # npx create-react-app my-app
    # npm i nodemon
    # npm install apexcharts --save
    # npm install react-apexcharts apexcharts

► To Run :
    # nodemon start

► Production build :
    # npm run build
