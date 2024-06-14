# Invoice-Extractor
**Invoice-Extractor** is a Streamlit web application designed to extract information from invoice images using advanced AI models. It leverages the Google Generative AI Gemini Pro vision model to analyze uploaded invoice images based on user-defined prompts.

**Features:**
1. **Upload Image**: Users can upload invoice images in JPG, JPEG, or PNG format.
2. **Input Prompt**: Users provide a text prompt specifying the information they seek from the invoice image.
3. **AI Analysis**: The application utilizes the Gemini Pro vision model to process the image and generate relevant information based on the input prompt.
4. **Output**: Displays the extracted information from the invoice image in response to the user's prompt.
   
**Technologies Used:**
1. **Python**: Language used for backend processing.
2. **Streamlit**: Framework used for building interactive web applications.
3. **Google Generative AI**: Provides the Gemini Pro vision model for image analysis.
4. **PIL**: Python Imaging Library for image handling.
   
**How to Run:**
1. Install dependencies using **'pip install -r requirements.txt'**.
2. Set up your Google API key in a **'.env'** file.
3. Run the Streamlit app using **'streamlit run app.py'**.
4. Ensure your Python environment is version 3.9 or higher.

**Usage:**
1. Upload an invoice image and specify a prompt related to the information you want from the invoice.
2. Click the "Tell me about the image" button to initiate the AI analysis.
3. View the extracted information from the invoice image based on your input prompt.
