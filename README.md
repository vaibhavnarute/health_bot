# Gemini Health App

## Overview
The Gemini Health App is a health management application that uses the Google Gemini Pro Vision API to analyze food items from an uploaded image and calculate the total calories. The app provides detailed information about each food item and its calorie intake.

## Features
- Upload an image of food items.
- Input a prompt for the analysis.
- Get a detailed response with the total calories and breakdown of each food item.

## Installation

### Prerequisites
- Python 3.11
- [pip](https://pip.pypa.io/en/stable/installation/)
- [Streamlit](https://streamlit.io/)
- [Google Generative AI](https://cloud.google.com/generative-ai)
- [Pillow](https://python-pillow.org/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/health_app.git
   cd health_app
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

5. Create a 

.env

 file in the root directory and add your Google API key:
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run health.py
   ```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload an image of food items and input a prompt.

   ![output1](https://github.com/user-attachments/assets/30c9830b-737e-4b21-bd82-7400542efb28)


5. Click the "Tell me the total calories" button to get the analysis.
   ![output2](https://github.com/user-attachments/assets/b4251399-0f46-4396-b9ca-1dd058806571)


## File Structure
```
health_app/
│
├── .env                # Environment variables
├── health.py           # Main application file
├── requirements.txt    # List of required packages
└── README.md           # Project documentation
```

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- [Streamlit](https://streamlit.io/)
- [Google Generative AI](https://cloud.google.com/generative-ai)
- [Pillow](https://python-pillow.org/)

