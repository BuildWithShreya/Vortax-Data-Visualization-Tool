# Chart Sharing Feature Using Web Share API

This project demonstrates how to share a chart image generated on an HTML `<canvas>` element using the **Web Share API**.

## Features
- Upload data from a CSV or Excel file.
- Generate a chart using the `Chart.js` library.
- Share the chart image using the **Web Share API**.
- Download the chart as an image.

## How to Use

### 1. Upload Data File
You can upload a CSV or Excel file containing the data for the chart. The file is processed to generate a chart.

#### Example File Types:
- `.csv`
- `.xlsx` (Excel)

### 2. Generate Chart
After uploading the data, a chart is generated on an HTML `<canvas>` element using the `Chart.js` library.

### 3. Share the Chart
Once the chart is rendered, you can share it as an image using the **Web Share API** if supported by the browser. This feature works primarily on mobile devices or environments that support the Web Share API.


