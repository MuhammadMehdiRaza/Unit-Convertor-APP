# Unit Converter App

This is a simple Android application built with Kotlin and Jetpack Compose. It allows users to convert values between different units, such as meters, centimeters, feet, and millimeters.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

---

## Features

- Convert values between units such as **Meters**, **Centimeters**, **Feet**, and **Millimeters**.
- User-friendly interface with dropdown menus for selecting input and output units.
- Real-time calculation as the user inputs values.

---

## Technologies Used

- **Programming Language:** Kotlin
- **Framework:** Jetpack Compose
- **Material Design 3 (M3):** For a modern and responsive UI.

---

## Setup and Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/MuhammadMehdiRaza/UnitConverter.git
   cd UnitConverter

   ```

2. **Open the Project and Build the Project**

   ```bash
   Sync Gradle and build the project to download dependencies
   ```

3. **Run the App**
   ```bash
   Connect an emulator or physical device and click on the Run button in Android Studio.
   ```

## Usage

1. **Enter a Value**

   Input the value you want to convert in the Enter Value field.

2. **Select Input and Output Units**

   Use the dropdown buttons to select the units for conversion.

3. **View the Result**

   The result will be displayed in real-time below the input fields.

## Project Structure

1. **MainActivity.kt**

- contains the main logic for the Unit Converter app, including dropdown menus and conversion formulas.

2. **UI Components**

- Jetpack Compose components like Column, Row, and DropdownMenu are used for layout and interactivity.

3. **Conversion Logic**

- The app calculates conversion values using pre-defined conversion factors for the selected units.

## Known Limitations

- Only cm,mm,m,feet units are used.

## Future Enhancements

- Add more units for conversion (e.g., kilometers, inches, miles).
- Include support for weight, volume, and temperature conversions.
- Implement localization for multiple languages.
- Save conversion history for user reference.
- Enhance the UI with animations and dark mode support.

## Contributing

Contributions to enhance the project are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgments

- **Jetpack Compose:** For providing a modern and declarative way to build UIs.

- **Material Design 3** For ensuring a clean and responsive design.

- **Chat GPT and Ygit push -u origin mainoutube:** Now a days, with these tools, learning rate has progressively improved compared to past. I encourage everyone to take benefit.
