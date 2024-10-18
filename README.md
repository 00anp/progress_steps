# Progress Steps

## Description
This project showcases a step-by-step progress bar with interactive buttons for navigating between steps. Users can click the "Next" and "Prev" buttons to advance or go back through the steps, and the progress bar adjusts accordingly. The design is fully responsive and includes smooth transitions for a better user experience.

## Features
- Step-based progress indicator with clickable navigation.
- Dynamic progress bar that updates based on the active step.
- Responsive and minimalistic design.
  
## Tech Stack
- **HTML5**: Provides the structure of the progress bar and buttons.
- **CSS3**: Handles the layout and styling, including transitions and responsiveness.
- **JavaScript**: Manages the click events for the navigation buttons and updates the progress bar dynamically.

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd progress-steps
    ```
3. Open `index.html` in your browser:
    ```bash
    open index.html
    ```

## Code Explanation
- **HTML**: The structure consists of a container with four circles representing the steps, and two buttons ("Prev" and "Next") for navigation. The progress bar fills dynamically based on user interaction.
  
- **CSS**: 
  - Uses CSS variables for customizable colors.
  - The `.progress-container` houses the progress bar, which adjusts its width based on the user's progress.
  - Circles change color when active, providing a visual indicator of the current step.

- **JavaScript**: 
  - The script listens for clicks on the "Next" and "Prev" buttons.
  - The `update()` function dynamically adjusts the progress bar's width and manages which circles are active.
  - Disables the "Prev" button when at the first step, and the "Next" button at the last step.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
