# Currency_Converter

## Overview
This is a **Currency Converter** application built using Java with a Graphical User Interface (GUI). The application allows users to convert currencies from one type to another (e.g., from USD to EUR) with real-time exchange rates. The goal is to provide a simple, interactive interface for currency conversion.

## Features
- Convert between multiple **currencies** (e.g., USD, EUR, GBP, INR).
- **User-friendly GUI** built with **Java Swing**.
- Real-time currency conversion (can be integrated with an API for live exchange rates).
- Simple input and output fields for entering and displaying conversion results.
- Option to clear the input fields for a new conversion.
- Error handling for invalid input to ensure smooth user experience.

## Technologies Used
- **Java**: The programming language used for building the application.
- **Swing**: Java's GUI toolkit used to create the graphical user interface.
- **Exchange Rate API (Optional)**: The project can be extended to fetch real-time exchange rates if integrated with an API like Open Exchange Rates.

## Requirements
- **Java 8 or above**.
- No external libraries are required, but an API for live exchange rates can be integrated if desired.

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/manishdahake10/Currency-converter.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Currency-converter
    ```

3. Compile the `Currency_Converter.java` file:
    ```bash
    javac Currency_Converter.java
    ```

4. Run the application:
    ```bash
    java Currency_Converter
    ```

## Usage
Once the program runs, the user will be able to:
- Select the currency to convert from.
- Enter an amount in the selected currency.
- Choose the currency to convert to.
- Click the **Convert** button to view the result.
- Optionally, click the **Clear** button to reset the input fields.

## Output
![ScreenShot](https://github.com/user-attachments/assets/7c09e86b-cceb-482a-99f1-557f294f9886)


## Code Structure
The project consists of the following structure:

- `Currency_Converter.java`: The main Java file that handles the GUI and conversion logic.
- The GUI components are set up using **Java Swing**.
- Currency conversion logic is implemented using predefined exchange rates or can be integrated with an API for live rates.

## Contribution
Feel free to fork this repository and contribute by opening issues or submitting pull requests. If you would like to enhance this project or fix bugs, feel free to contribute with your changes!

## Author
Manish Dahake  
GitHub: [manishdahake10](https://github.com/manishdahake10)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
