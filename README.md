Campsite Commander

Campsite Commander is a simple and efficient Android inventory application designed for outdoor enthusiasts. It allows users to easily track, categorize, and manage their camping gear and food supplies, ensuring nothing important is left behind. This app was developed using Kotlin in Android Studio, focusing on fundamental Android development principles.

Features

   Splash Screen:A welcoming, themed entry point to the application.
   Add Gear:Easily add new items to your packing list with details like category, quantity, and comments.
*   Detailed View:See a complete, organized list of all your items with all their details in a scrollable view.
*   Dynamic Item Count:The main screen automatically calculates and displays the total number of items packed using a loop.
*   Intuitive Navigation:Simple button-based navigation between screens for a smooth user experience.
*   Error Handling:Provides constructive feedback for incorrect or missing user input.
*   Nature-Themed UI:A dark mode/nature-themed color palette for a pleasant user interface.

Screenshots

| Splash Screen | Main Screen | Detailed List |
| ![Splash Screen](screenshots/splash.png) | ![Main Screen](screenshots/main.png) | ![Detailed List](screenshots/detailed.png) |

 Technical Implementation

This project was built to satisfy a specific set of academic requirements, demonstrating proficiency in core Android development concepts.

*   Language:Kotlin
*   Architecture:Standard Android Activity Lifecycle with XML for layouts.
*   Data Storage:Utilizes in-memory parallel `ArrayLists` managed by a singleton `DataManager` object for simplicity and to meet project specifications.
*   Core Concepts Demonstrated:
    *   UI/UX:XML-based layouts, including `LinearLayout`, `RelativeLayout`, `TextView`, `Button`, and `ScrollView`.
    *   Navigation:Explicit `Intents` to transition between different `Activities`.
    *   Data Structures:Use of parallel `ArrayLists` to manage related data (item names, categories, quantities).
    *   Control Flow: `for` loops are used for calculations (total items) and for dynamically building the detailed view.
    *   Error Handling: `try-catch` blocks and conditional checks (`if/else`) to handle invalid user input gracefully.

Evaluation Checklist

This project successfully implements all the required functionality:

- Correct implementation of arrays and loops:Parallel arrays store data, and loops are used for calculation and display.
- Accuracy in calculating and displaying the total number of items:The total is correctly calculated by looping through the quantities array.
- Proper screen navigation:Buttons correctly navigate between the main, detailed, and add-item screens.
- Well-designed layout and user interface:The app uses a consistent, nature-themed color palette and logical layouts.
- Clear and concise code with meaningful comments:The code is commented to explain key functionalities.
- A finished-looking app with a new icon:The app has a custom launcher icon and a polished feel.
- Error Handling:The app prevents crashes from bad input and guides the user.


Setup and Installation

To run this project on your local machine:

1.  Clone the repository:
       bash
    (https://github.com/Zintle-Mdutyana09/Grocery-Items.git)
    
2.  Open in Android Studio:
     Launch Android Studio.
     Select "File" then "Open".
     Navigate to the cloned project directory and open it.
3.  Build the Project:Let Gradle sync and build the project.
4.  Run the App:Run it on an Android emulator or a physical device.
