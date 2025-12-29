# Browser Automation Flow Designer (브라우저 자동화 흐름 디자이너)

A sophisticated, browser-based visual programming environment for designing and simulating web automation workflows.

## Features

*   **Interactive Web Recorder**: Capture user interactions (clicks, text input, navigation) within an embedded browser view.
*   **Visual Flowchart Editor**: A drag-and-drop interface to arrange recorded actions, add control flow (conditionals, loops), waits, assertions, and data extraction steps.
*   **Robust Element Selector**: Visually select DOM elements and generate resilient selectors (CSS, XPath, or attribute-based).
*   **Detailed Action Configuration**: A panel for customizing parameters and logic for each action in the flowchart.
*   **JavaScript Code Exporter**: Export the entire visual workflow into clean, executable JavaScript code (e.g., Playwright/Puppeteer).
*   **Simulated Execution Environment**: An in-browser interpreter to "run" the automation against a URL for immediate testing and debugging.
*   **Step-by-Step Feedback**: Visual feedback during simulated execution.
*   **Integrated Debugging Console**: A console for debugging automation workflows.
*   **Data Extraction and Storage**: Nodes for extracting and temporarily storing scraped information.

## Demo

To run the project locally, follow these steps:

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/browser-automation-flow-designer.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd browser-automation-flow-designer
    ```
3.  Open the `index.html` file in your web browser.

## Tech Stack

*   **Frontend**: Vanilla JavaScript (or a lightweight framework like Lit/Preact with Web Components).
*   **Visual Editor**: Canvas or SVG for node rendering.
*   **Execution Engine**: A custom in-browser interpreter.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.
