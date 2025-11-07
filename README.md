# Streamlit Gemini Quick Test

This project is a simple Streamlit application that allows users to interact with the Gemini model through a chat interface. It is designed to test the connectivity and functionality of the Gemini API.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/streamlit-gemini-quicktest.git
   cd streamlit-gemini-quicktest
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Set the environment variable for the Gemini API key:
   ```
   export GEMINI_API_KEY='your_api_key'  # On Windows use `set GEMINI_API_KEY='your_api_key'`
   ```

## Usage

To run the Streamlit application locally, use the following command:
```
streamlit run streamlit_gemini_test.py
```

Open your web browser and navigate to `http://localhost:8501` to interact with the application.

## Deployment

This project includes a GitHub Actions workflow for deploying the Streamlit application. To deploy, push your changes to the `main` branch, and the workflow will automatically deploy the application to Streamlit Sharing.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.