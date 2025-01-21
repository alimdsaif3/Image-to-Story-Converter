# 🏰 Image to Speech GenAI Tool 🌟♨️  
An innovative AI tool that generates audio short stories based on the context of uploaded images. It leverages cutting-edge GenAI models from Hugging Face, OpenAI, and LangChain, and is deployed on both Streamlit Cloud and Hugging Face Space.  

---

## 📢 Deployments  

### Run App on Streamlit Cloud  
[![Launch App On Streamlit](https://img.shields.io/badge/Streamlit-Run%20App-orange)](https://image-to-story-converter-yrm9ahzx9fc4ksspczutsb.streamlit.app/)  

### Run App on HuggingFace Space Cloud  
[![Launch App On HuggingFace Space](https://img.shields.io/badge/HuggingFace-Run%20App-yellow)](https://huggingface.co/spaces/alimdsaif3/Image-to-Speech-GenAI-Tool-Using-LLM)  

---

## 🎯 Key Features  

1. **Image to Text**  
   - Uses Hugging Face's image-to-text transformer model ([Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)) to analyze the image and generate descriptive text.  

2. **Text to Story**  
   - Utilizes OpenAI's GPT-3.5-Turbo model to create a short, imaginative story (default: 50 words) from the descriptive text.  

3. **Story to Speech**  
   - Converts the story into a narrated audio file using Hugging Face's text-to-speech model ([espnet/kan-bayashi_ljspeech_vits](https://huggingface.co/espnet/kan-bayashi_ljspeech_vits)).  

4. **User-Friendly Interface**  
   - Built with Streamlit for easy image uploading and playback of generated audio.  

---

## 📈 System Design  

![System Design Diagram](img/system-design.drawio.png)  

---

## 📂 Demo  

### Couple Test Image Output  
![Couple Test Image Output](img-audio/CoupleOutput.jpg)  
*Audio file available in the `img-audio` folder.*  

### Family Test Image Output  
![Family Test Image Output](img-audio/FamilyOutput.jpg)  
*Audio file available in the `img-audio` folder.*  

### Picnic Test Image Output  
![Picnic Vacation Test Image Output](img-audio/PicnicOutput.jpg)  
*Audio file available in the `img-audio` folder.*  

---

## 🌟 Requirements  

The following libraries and tools are required:  

- `os`  
- `python-dotenv`  
- `transformers`  
- `torch`  
- `langchain`  
- `openai`  
- `requests`  
- `streamlit`  

---

## 🚀 Usage  

### Prerequisites  
- Obtain personal API tokens for Hugging Face and OpenAI.  
- Save the tokens in a `.env` file with the following format:  
  ```env
  OPENAI_API_KEY=<your-api-key-here>  
  HUGGINGFACE_API_TOKEN=<your-access-token-here>  
Steps
Set up a virtual environment (venv) and install dependencies:
bash
Copy
Edit
pip install -r requirements.txt  
Run the app:
bash
Copy
Edit
streamlit run app.py  
Upload an image via the app interface.
The app will:
Generate descriptive text for the uploaded image.
Create a short story based on the text.
Provide a playable audio file of the narrated story.
▶️ Installation
Clone the Repository
bash
Copy
Edit
git clone https://github.com/alimdsaif3/Image-to-Story-Converter.git  
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt  
Run the App Locally
bash
Copy
Edit
streamlit run app.py  
©️ License
This project is distributed under the MIT License. For details, see the LICENSE file in the repository.

🤝 Contributions
If you like this project, please ⭐ the repository! Contributions are welcome. Submit a pull request if you have suggestions or enhancements.

---

#### **If you like this LLM Project do drop ⭐ to this repo**
#### Follow me on [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-saif-ali-9815a774/) &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alimdsaif3)

---
