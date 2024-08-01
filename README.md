CPU Scheduling Algorithm Visualization
Overview
This project visualizes the performance of various CPU scheduling algorithms. It includes functions to display Gantt charts, timeline charts, and performance comparison charts for different algorithms. The primary focus is on comparing completion time, turn around time, waiting time, response time, and context switches for each algorithm.

Features
Visualization of Gantt and timeline charts
Performance comparison of various CPU scheduling algorithms
Detailed charts for Round Robin scheduling with varying time quantums
Prerequisites
HTML
CSS
JavaScript
Chart.js library for creating charts
File Structure
index.html: Contains the HTML structure and includes necessary scripts.
styles.css: Contains the CSS styles for the visualization.
scripts.js: Contains the JavaScript code to generate and display the charts.
Functions
showRoundRobinChart
Generates a line chart comparing completion time, turn around time, waiting time, response time, and context switches for different time quantums in Round Robin scheduling.

javascript
Copy code
function showRoundRobinChart(outputDiv) {
    // Function implementation...
}
showAlgorithmChart
Generates a bar chart comparing completion time, turn around time, waiting time, and response time for different CPU scheduling algorithms.

javascript
Copy code
function showAlgorithmChart(outputDiv) {
    // Function implementation...
}
showOutput
Displays the Gantt chart, timeline chart, final table, and time log. Additionally, it calls showRoundRobinChart and showAlgorithmChart based on the selected algorithm.

javascript
Copy code
function showOutput(input, output, outputDiv) {
    // Function implementation...
}
CPUScheduler
Simulates the CPU scheduling process for various algorithms and generates the necessary data for visualization.

javascript
Copy code
function CPUScheduler(input, utility, output) {
    // Function implementation...
}
calculateOutput
Main function triggered by the "Calculate" button. It initializes input, utility, and output objects, then calls CPUScheduler and showOutput.

javascript
Copy code
function calculateOutput() {
    // Function implementation...
}
How to Use
Open index.html in a web browser.
Enter the process details and select the scheduling algorithm.
Click the "Calculate" button to visualize the output.
Screenshots
Round Robin Chart

Algorithm Comparison Chart

Gantt Chart

Timeline Chart

Final Table

Time Log
