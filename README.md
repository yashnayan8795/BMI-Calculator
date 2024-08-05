# BMI Calculator with Tkinter

This BMI Calculator is a simple and interactive graphical application built using Python's Tkinter library. It allows users to input their name, weight, and height to calculate their Body Mass Index (BMI) and categorize it into health categories. The application also saves the data and displays BMI trends over time using Matplotlib and Pandas.

## Features

- **User Input**: Enter name, weight (in kilograms), and height (in meters).
- **BMI Calculation**: Calculates BMI using the formula `BMI = weight / (height ^ 2)`.
- **Categorization**: Classifies BMI values into categories: Underweight, Normal weight, Overweight, and Obesity.
- **Data Storage**: Saves user data including name, weight, height, BMI, category, and date.
- **Trend Visualization**: Displays BMI trends over time for the user.

## Requirements

- Python 3.x
- Tkinter (usually included with Python installations)
- Pandas
- Matplotlib

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/bmi_calculator.git
    cd bmi_calculator
    ```

2. **Install Required Packages**:
    ```bash
    pip install pandas matplotlib
    ```

## Usage

1. **Run the Application**:
    ```bash
    python bmi_calculator.py
    ```

2. **Input Data**:
   - Enter your name, weight in kilograms, and height in meters.
   - Click the "Calculate BMI" button.

3. **View Results**:
   - The application will display your BMI and the corresponding health category.

4. **Save Data**:
   - The data is automatically saved in a CSV file (`bmi_data.csv`).

5. **View Trends**:
   - Click the "Show Trend" button to see your BMI trend over time.

## Code Structure

- **Main Window Setup**: Initializes the Tkinter main window with larger font settings and increased window size.
- **Input Fields**: Creates labels and entry widgets for user input.
- **Result Display**: Sets up a label to display the BMI result.
- **Functions**:
  - `validate_inputs()`: Validates and converts user inputs.
  - `calculate_bmi()`: Computes the BMI.
  - `categorize_bmi()`: Categorizes the BMI value.
  - `save_data()`: Saves the data to a CSV file.
  - `load_data()`: Loads existing data from the CSV file.
  - `plot_trend()`: Plots the BMI trend for the user.
  - `on_calculate()`: Handles the BMI calculation and data saving process.
- **Buttons**: Creates buttons for calculating BMI and showing the trend.

## ScreenShots

<img width="290" alt="image" src="https://github.com/user-attachments/assets/a3cd8fca-1f5b-499b-8531-1d61332c2dee">

<br>

<img width="266" alt="image" src="https://github.com/user-attachments/assets/da426192-0d99-476a-91d5-8a3998883372">

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

[Your Name](https://github.com/yourusername)

Feel free to reach out if you have any questions or suggestions!
