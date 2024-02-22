<div align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
<h1 align="center">Empress Charts: Deceptively Simple, Intuitively Powerful</h1>
<p align="center">
Elevate your data visualization with zero-dependency, Github-inspired charts crafted by Empress.
<br />
<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/charts/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/charts/issues/new">Request Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
The Empress 'charts' project is tailored for developers and data enthusiasts who desire an effortless, sleek, and intuitive way to visualize their data. It addresses the challenges of complex data visualization, offering a responsive charting library that is refreshingly simple to use and requires no dependencies.

### 🌟 Key Features
- Zero dependencies for a smoother project integration.
- Responsive and intuitive charts that adapt to various display sizes.
- GitHub-inspired design that is familiar and user-friendly.
- Supports a diverse array of chart types (bar, line, scatter, pie, percentage) to suit different data visualization needs.

### 🛠 Built With
This section is currently under review and will be updated with the major frameworks/libraries used in the project once available.

## Getting Started

### Prerequisites
To utilize this library, you need to have [`npm`](https://www.npmjs.com/get-npm) installed on your system.

### Installation
Clone the repository using the following link:

```
https://github.com/empress-eco/charts.git
```

Install the library with npm:

```sh
$ npm install Empress-charts
```

Next, include the library in your project:

```js
import { Chart } from "Empress-charts"
```

For ES6 modules like Vue.js, use:

```js
import { Chart } from 'Empress-charts/dist/Empress-charts.esm.js'
// import CSS
import 'Empress-charts/dist/Empress-charts.min.css'
```

Alternatively, you can include it within your HTML:

```html
<script src="https://cdn.jsdelivr.net/npm/Empress-charts@1.6.1/dist/Empress-charts.min.umd.js"></script>
```

## Usage
Here is a basic example to get you started with our library:

```js
const data = {
    labels: ["12am-3am", "3am-6pm", "6am-9am", "9am-12am",
        "12pm-3pm", "3pm-6pm", "6pm-9pm", "9am-12am"
    ],
    datasets: [
        {
            name: "Some Data", chartType: "bar",
            values: [25, 40, 30, 35, 8, 52, 17, -4]
        },
        {
            name: "Another Set", chartType: "line",
            values: [25, 50, -10, 15, 18, 32, 27, 14]
        }
    ]
}

const chart = new Chart("#chart", {
    title: "My Awesome Chart",
    data: data,
    type: 'axis-mixed', // or 'bar', 'line', 'scatter', 'pie', 'percentage'
    height: 250,
    colors: ['#7cd6fd', '#743ee2']
})
```

## Contributing
We warmly welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Clone the repo.
3. Navigate into the project directory: `cd charts`
4. Install dependencies: `npm install`
5. Install npm-run-all (if necessary): `npm i npm-run-all -D`
6. Run the app in development mode: `npm run dev`
7. Open a Pull Request

## License and Acknowledgements

### License
This project operates under the MIT License. Your contributions will also be licensed under the MIT License.

### Acknowledgements
We deeply appreciate the Empress Community for their foundational contributions to this project. Their innovative tools and dedication have been instrumental in building the functionalities we rely on. Our profound gratitude goes to them for their pioneering work and ongoing support.