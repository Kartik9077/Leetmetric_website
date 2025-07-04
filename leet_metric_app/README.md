# Leetcode Stats Dashboard

A modern, interactive web dashboard designed to display detailed statistics for Leetcode users. This application allows users to visualize key performance metrics such as total problems solved, acceptance rates, and difficulty distribution. The dashboard is built using **vanilla JavaScript**, **Tailwind CSS**, **ApexCharts**, and **Chart.js** for dynamic data visualization and a seamless user experience.

![Screenshot 2024-11-11 201848](https://github.com/user-attachments/assets/20de34a4-0aed-46ee-acd9-f8936e08d850)

## Features

- **Real-time Leetcode Statistics**: Provides detailed information on Leetcode user stats, including:
  - Total problems solved
  - Total Questions
  - Problem difficulty distribution (Easy, Medium, Hard)
  - Problem-solving progress over time
- **Interactive Data Visualizations**: Utilizes interactive charts for better understanding and tracking of your progress.
- **Mobile-First, Responsive Design**: Built with **Tailwind CSS**, ensuring a responsive and mobile-friendly interface that works across devices.
- **User Input**: Users can input their Leetcode username to fetch and display personalized data from the Leetcode platform.

## Usage

- **Enter Leetcode Username**: On the dashboard, input a valid Leetcode username in the provided text field.
- **View Stats**: After entering the username, the dashboard will automatically fetch the relevant data and populate various statistics.
- **Charts and Visualizations**: The application will display interactive charts (using **ApexCharts** and **Chart.js**) to visualize:
  - Total problems solved by difficulty in percentage (Doughnut chart)
  - Progress over time (Radar Chart)
  - Total Questions (Pie Chart)
  - Total problems solved by difficulty in numbers (Vertical bar chart)

## Technologies Used

- **HTML5**: Structure and semantics for the dashboard.
- **Vanilla JavaScript**: For handling user input, data fetching, and DOM manipulation.
- **Tailwind CSS**: Utility-first CSS framework for responsive and customizable styling.
- **ApexCharts**: Charting library for rendering interactive, responsive charts.
- **Chart.js**: Additional charting library used for bar charts.
- **Leetcode API**: API calls to retrieve user-specific stats from Leetcode.

## Installation

To run this project locally, follow the steps below:

```bash
git clone https://github.com/nilav-talukdar/leetmetric.git
cd leetcode-stats-dashboard
