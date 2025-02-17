# Batch Calculator

## Overview
The **Batch Calculator** is a web-based application designed to help users efficiently calculate the required baking batches for various types of bread and pizza dough. The program ensures that minimum requirements are met while optimizing the batch sizes for maximum efficiency. I developed this program while working as a baker at my local Schlotzsky's to streamline the batch planning process. Therefore, it is only applicable to a Schlotzsky's restaurant.

## Features
- Calculate baking batches for:
  - 8" and 10" pizzas
  - Large, medium, and small sourdough buns
  - Medium and small jalapeño cheddar buns
- Dynamically adjusts calculations based on user input for on-hand quantities.
- Ensures minimum requirements are met for each type of bread and pizza dough.
- Optimizes batch sizes to reduce waste and improve efficiency.
- Displays clear, detailed results for each calculated batch.
- Includes a "Print" button for a printer-friendly version of batch results with enlarged text for readability.
- Clean, professional interface with a responsive design and attractive background.

## Technologies Used
- **HTML5**: For the structure and layout of the web application.
- **CSS3**: For styling and creating a visually appealing, user-friendly interface.
- **JavaScript**: For dynamic functionality, calculations, and user interaction.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/batch-calculator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd batch-calculator
   ```
3. Open `index.html` in your preferred web browser to run the application.

## Usage
1. Input the current on-hand quantities for each type of bread or pizza dough in the respective fields.
2. Click the **Calculate** button to compute the required batches based on minimums and batch sizes.
3. Review the results in the output box below the input fields.
4. Use the **Print** button to print a formatted version of the batch calculations.
5. Click the **Clear** button to reset all fields and start a new calculation.

## Batch Logic
The batch calculation logic considers:
- **Minimum requirements**: Ensures minimum quantities are met.
- **Batch sizes**: Optimizes for efficient use of resources.
- **Additional adjustments**: Uses leftover batch weight to produce additional items (e.g., medium buns).

### Example Output
```
Pizza Batch: 20 - 8", 15 - 10"
1.25 Sourdough Batch: 24 small, 45 medium, 4 large
0.25 Jalapeno Batch: 2 small, 19 medium
```

## Challenges & Solutions
- **Dynamic Batch Selection**: Implemented an iterative approach to determine the most efficient batch size for each type of dough.
- **Alignment and Layout**: Adjusted input fields, results box, and buttons for a professional, symmetrical design.
- **Print Functionality**: Ensured that printed results are clear and easy to read with enlarged text.

## Future Improvements
- Add support for additional bread types and batch sizes.
- Implement a backend to save and retrieve past calculations.
- Create a mobile app version for on-the-go usage.

## Author
This program was created to provide an efficient solution for calculating baking batches. The focus was on developing a functional, user-friendly tool that meets the needs of its users while overcoming technical challenges.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
Thank you for using the **Batch Calculator**! Feel free to contribute or share feedback to make it even better.

