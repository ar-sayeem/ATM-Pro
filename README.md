# ATM-Pro

ATM-Pro is a Java-based Swing application that simulates an ATM system. It provides a graphical user interface for users to interact with various banking functionalities such as login, balance checking, and withdrawals.

## Features
- User-friendly Swing-based GUI.
- Login functionality with password validation.
- Multiple banking operations like balance checking and withdrawals.
- Lightweight and easy to run.

## Prerequisites
To run this project, ensure you have the following installed:
- Java Development Kit (JDK) 8 or higher
- An IDE like NetBeans (recommended) or Visual Studio Code with Java extensions

## How to Run

### Using NetBeans
1. Open NetBeans IDE.
2. Go to `File > Open Project`.
3. Navigate to the `ATM-Pro` folder and select it.
4. Build the project using `Clean and Build`.
5. Run the project by clicking the `Run` button. The `Login` class is the entry point.

### Using VS Code
1. Open the `ATM-Pro` folder in VS Code.
2. Install the "Extension Pack for Java" from the Extensions Marketplace.
3. Open the `Login.java` file in the `src/ar_bank_30May23` directory.
4. Press `F5` or click the `Run` button to start the application.

### Using Command Line
1. Navigate to the `src` directory:
   ```bash
   cd "f:\25Fall\Presentation + Project\#AR_Project\ATM-Pro\src"
   ```
2. Compile the Java files:
   ```bash
   javac ar_bank_30May23/*.java
   ```
3. Run the `Login` class:
   ```bash
   java ar_bank_30May23.Login
   ```

### Notes
- Ensure the `images` folder is present in the `src` directory as it contains assets required for the GUI.
- The `data.txt` file is used for storing sample data. Ensure it is in the root directory.

## Project Structure
```
ATM-Pro/
├── build/                # Compiled classes
├── images/               # Image assets for the GUI
├── nbproject/            # NetBeans project files
├── src/                  # Source code
│   ├── ar_bank_30May23/  # Java and .form files
│   └── images/           # Image assets for the GUI
├── build.xml             # Build script
├── data.txt              # Sample data file
├── manifest.mf           # Manifest file
```

## License
This project is licensed under the MIT License.