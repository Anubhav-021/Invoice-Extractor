# MultiLanguage Invoice Extractor

Welcome to the MultiLanguage Invoice Extractor! This application leverages Google Generative AI to analyze and extract information from invoices in various languages, providing a powerful tool for businesses and individuals dealing with invoices from multiple regions.

## 🎯 Overview

The MultiLanguage Invoice Extractor is a Streamlit application designed to simplify the process of understanding and extracting data from invoices. By uploading an invoice image, users can query specific details, and the app will provide accurate responses based on the content of the uploaded invoice.

## Key Features:

1. MultiLanguage Support: The app supports invoices in multiple languages, making it accessible globally.
2. Generative AI Integration: Uses Google Generative AI (Gemini Vision Model) to interpret and respond to user queries.
3. Image Upload: Users can easily upload invoice images in formats like JPG, JPEG, and PNG.
4. Real-time Analysis: Get instant feedback and information based on the uploaded invoice.
   
## 🛠️ How It Works

1. Upload Invoice Image: Start by uploading an image of the invoice. The app supports formats such as JPG, JPEG, and PNG.
2. Input Query: Type in any specific question or prompt related to the invoice. The app is designed to understand and respond to various queries regarding the invoice details.
3. AI Analysis: The uploaded invoice is processed using the Gemini Vision Model from Google Generative AI, which extracts and interprets the relevant details.
4. Get Response: The app will display the extracted information or answer your query based on the content of the invoice.

## 📷 Screenshots
Here are a few screenshots to give you a feel for the app:

Main Interface: The header and input fields where users can upload invoices and input prompts.
Uploaded Image Preview: A preview of the uploaded invoice image.
AI Response: The app’s response to a user’s query based on the uploaded invoice.
🚀 Getting Started
Prerequisites:
Python 3.x
Streamlit
Pillow
google-generativeai
dotenv
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/multilanguage-invoice-extractor.git
cd multilanguage-invoice-extractor
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Set Up Environment Variables:

Create a .env file in the root directory of your project and add your Google API key:

plaintext
Copy code
GOOGLE_API_KEY=your_google_api_key_here
Run the Application:

bash
Copy code
streamlit run app.py
Usage
Once the app is running, you can open it in your browser, upload an invoice image, and start querying the invoice content.

🤝 Contributing
Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request. Make sure to follow the contributing guidelines.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
A special thanks to Google for providing the Generative AI tools that power this application. Also, a shoutout to the Streamlit team for making it so easy to build and deploy web apps!

Feel free to modify the content to better suit your style or add any additional details that you think are relevant!











