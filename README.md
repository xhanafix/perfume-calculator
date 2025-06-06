Perfume Cost & Yield Calculator
A simple, intuitive, and powerful web-based tool for perfume hobbyists and small-batch producers. This calculator demystifies the process of calculating production costs and potential yield based on the costs of your raw materials.
This tool is built with vanilla HTML, JavaScript, and styled with Tailwind CSS, making it lightweight, fast, and easy to modify.
➡️ View Live Demo (Link to your GitHub Pages or other deployment)
✨ Features
 * ✅ Detailed Cost Analysis: Calculates the final cost per bottle, incorporating the price of alcohol base, perfume oil, and the empty bottle itself.
 * ✅ Production Yield Calculation: Instantly determines the maximum number of bottles you can produce based on your available raw materials, identifying the limiting ingredient.
 * ✅ Dynamic Formula Breakdown: Shows the exact formulas and values used for the calculations, providing transparency and helping you understand the numbers.
 * ✅ Fixed Ratio Logic: Uses a standard 60% alcohol base to 40% perfume oil ratio, which can be easily customized in the code.
 * ✅ Modern & Responsive UI: Clean, user-friendly interface built with Tailwind CSS that works beautifully on both desktop and mobile devices.
 * ✅ No Dependencies: Runs entirely in the browser with no need for external libraries or frameworks.
🛠️ Technologies Used
 * HTML5: For the structure and content.
 * Tailwind CSS: For all styling and responsive design, loaded via a CDN.
 * JavaScript (ES6): For all the calculation logic and DOM manipulation.
🚀 Getting Started
There are two easy ways to get this project running on your local machine.
Method 1: Simple Download
 * Download the repository as a ZIP file and extract it.
 * Simply open the index.html file in your favorite web browser.
Method 2: For Developers (Using Git)
 * Clone the repository to your local machine:
   git clone https://github.com/your-github-username/your-repo-name.git

 * Navigate into the project directory:
   cd your-repo-name

 * Open the index.html file in your browser.
⚙️ Configuration
Customizing the Perfume Ratio
The core logic of the calculator is based on a 60/40 ratio (60% alcohol base, 40% perfume oil). If you use a different ratio (e.g., 70/30), you can easily change it.
 * Open the index.html file.
 * Scroll down to the <script> tag at the bottom.
 * Find these two lines in the // --- ===== COST CALCULATION ===== --- section:
   const baseAmountInFinal = finalQuantity * 0.60; // <-- Change this value
const oilAmountInFinal = finalQuantity * 0.40;  // <-- Change this value

 * Adjust the decimal values to match your desired ratio. Ensure they add up to 1.0 (e.g., 0.70 and 0.30 for a 70/30 split).
 * Save the file, and the calculator will now use your custom ratio.
🤝 How to Contribute
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
 * Fork the Project.
 * Create your Feature Branch (git checkout -b feature/AmazingFeature).
 * Commit your Changes (git commit -m 'Add some AmazingFeature').
 * Push to the Branch (git push origin feature/AmazingFeature).
 * Open a Pull Request.
📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.
Created with care in Bagan Serai, Perak.
