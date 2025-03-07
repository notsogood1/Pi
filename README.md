# Optimized Leibniz Pi Calculator

This project provides a web-based calculator that approximates the value of Pi using the Leibniz formula. It offers a simple, interactive interface to start and stop the calculation and displays the computed Pi value in real-time.

## Description

The script implements the Leibniz formula, a mathematical series, to approximate Pi incrementally. Key features include:

-   **Real-time Pi Approximation:** Dynamically displays the calculated Pi value as the computation progresses.
-   **Interactive Controls:** Provides "Start" and "Stop" buttons for user control.
-   **Visual Feedback:** Button states change to indicate the current calculation status.
-   **Clean and Clear Output:** The calculated Pi value is presented in a formatted display area.
-   **Optimized Performance:** Uses `requestAnimationFrame` for efficient rendering and smooth updates.

## How to Use in GitHub CodeSpaces (Assuming `index.html` is in your Repository)

Follow these steps to run the Pi calculator directly from your existing GitHub repository using CodeSpaces:

1.  **Open Your Repository in CodeSpaces:**
    -      Click the green "Code" button.
    -      Select the "CodeSpaces" tab.
    -      Click "Create codespace on main" (or your branch name).

2.  **Start a Simple HTTP Server:**
    -   Once CodeSpaces is running, a terminal will open. If not, open a new terminal within your CodeSpace.
    -   Use Python's built-in `http.server` to start a simple server. Assuming your `index.html` file is in the root of your repository, run the following command to serve the files on port 8080:

        ```bash
        python3 -m http.server 8080
        ```
       
3.  **Access Your Application:**
    -   CodeSpaces will automatically detect the port and provide a "Ports" tab at the bottom of the window.
    -   Click the "Ports" tab, and you'll see port 8080 listed.
    -   Click the globe icon next to port 8080 to open the application in a new browser tab.

4.  **Interact with the Calculator:**
    -   Your browser will open, displaying the Pi calculator.
    -   Click "Start Calculating Pi" to begin the approximation.
    -   Click "Stop" to halt the calculation.

## Notes

-      CodeSpaces automatically forwards ports, making it easy to access your application.
-   Using `python3 -m http.server` (or `python -m SimpleHTTPServer`) is a convenient way to serve static files during development in CodeSpaces.
