# Optimized Leibniz Pi Calculator

This project provides a web-based calculator that approximates the value of Pi using the Leibniz formula. It offers a simple, interactive interface to start and stop the calculation and displays the computed Pi value in real-time.

## Description

The script implements the Leibniz formula, a mathematical series, to approximate Pi incrementally. Key features include:

-   **Real-time Pi Approximation:** Dynamically displays the calculated Pi value as the computation progresses.
-   **Interactive Controls:** Provides "Start" and "Stop" buttons for user control.
-   **Visual Feedback:** Button states change to indicate the current calculation status.
-   **Clean and Clear Output:** The calculated Pi value is presented in a formatted display area.
-   **Optimized Performance:** Uses `requestAnimationFrame` for efficient rendering and smooth updates.

## How to Use in GitHub CodeSpaces and Start Hosting

Follow these steps to run the Pi calculator in GitHub CodeSpaces and host it with a simple server:

1.  **Create a GitHub Repository:**
    -      Create a new repository on GitHub.
    -      Clone the repository to your local machine (optional) or directly open it in CodeSpaces.

2.  **Add `index.html`:**
    -      Create a file named `index.html` in the root of your repository.
    -      Copy and paste the following HTML, CSS, and JavaScript code into `index.html`:

    ```html
    ```

3.  **Open in CodeSpaces:**
    -      In your GitHub repository, click the green "Code" button.
    -      Select the "CodeSpaces" tab.
    -      Click "Create codespace on main" (or your branch name).

4.  **Start a Simple HTTP Server:**
    -   Once CodeSpaces is running, open a new terminal within your CodeSpace.
    -   Use Python's built-in `http.server` to start a simple server. For example, to serve the files on port 8080, run the following command:

        ```bash
        python3 -m http.server 8080
        ```

    -   If you are using python 2, use this command.
        ```bash
        python -m SimpleHTTPServer 8080
        ```
    -   CodeSpaces will automatically detect the port and provide a "Ports" tab at the bottom.
    -   Click the "Ports" tab, and you'll see port 8080 listed.
    -   Click the globe icon next to port 8080 to open the application in a new browser tab.

5.  **Run the Application:**
    -   Your browser will open, displaying the Pi calculator.
    -   Click "Start Calculating Pi" to begin the approximation.
    -   Click "Stop" to halt the calculation.

## Notes

-      The Leibniz formula converges slowly, so achieving high precision requires many iterations.
-   CodeSpaces provides a convenient environment for running and testing web applications.
-   Using `python3 -m http.server` (or `python -m SimpleHTTPServer`) provides a quick way to host static files during development.
-   CodeSpaces automatically forwards ports, making it easy to access your application.
