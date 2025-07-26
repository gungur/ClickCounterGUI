# FirstGUI - Simple Java Swing Counter Application

## Overview
FirstGUI is a simple Java Swing application that demonstrates basic GUI components and event handling. It features a button that increments a counter and displays the current count when clicked.

## Features
- Graphical user interface with a clickable button
- Counter that increments with each button click
- Real-time display of click count
- Clean, minimalist design with proper padding

## Requirements
- Java Development Kit (JDK) 8 or later

## How to Run
1. Compile the program:
   ```bash
   javac FirstGUI.java
   ```
2. Run the compiled program:
   ```bash
   java FirstGUI
   ```

## Usage
1. The application window will appear with a button labeled "Click me" and a counter display.
2. Each time you click the button, the counter increments by 1.
3. The updated count is displayed immediately below the button.

## Code Structure
- **JFrame**: Main application window
- **JPanel**: Container for UI components with 30px padding
- **JButton**: Clickable button that triggers the counter
- **JLabel**: Displays the current click count
- **ActionListener**: Handles button click events

## Customization Options
You can easily modify the program to:
- Change the window title by modifying `frame.setTitle()`
- Adjust the padding by changing the `createEmptyBorder()` parameters
- Change the button text by modifying the JButton constructor
- Alter the counter message format in the `actionPerformed` method

## Screenshot
[Insert URL Here]
