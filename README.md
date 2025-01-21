🏰 Image to Speech GenAI Tool Using LLM 🌟♨️

An AI tool that generates an audio short story based on the context of an uploaded image by prompting a GenAI LLM model. The tool integrates Hugging Face AI models, OpenAI, and LangChain. It is deployed on Streamlit and Hugging Space Cloud platforms separately.

📢 Run App with Streamlit Cloud

Launch App On Streamlit

📢 Run App with HuggingFace Space Cloud

Launch App On HuggingFace Space

🎯 Demo:

Example Outputs:

Audio: Available in the img-audio folder.

Audio: Available in the img-audio folder.

Audio: Available in the img-audio folder.

📈 System Design



🏆 Approach

The application uses Hugging Face AI models to generate text from an image and convert the text into audio narration. The execution is divided into three parts:

1. Image to Text

Model: Salesforce/blip-image-captioning-base

Generates a text scenario based on the AI's understanding of the image context.

2. Text to Story

Model: OpenAI's gpt-3.5-turbo

Generates a short story (adjustable to 50 words) based on the scenario.

3. Story to Speech

Model: espnet/kan-bayashi_ljspeech_vits

Converts the generated story into a narrated audio file.

User Interface

Built with Streamlit to enable uploading an image and playing the resulting audio.

🌟 Requirements

The following libraries are required to run the application:

os

python-dotenv

transformers

torch

langchain

openai

requests

streamlit

🚀 Usage

Obtain personal API tokens for Hugging Face and OpenAI.

Set up a virtual environment (venv) and install the ipykernel library for local IDE use.

Save tokens in a .env file within the project directory:

OPENAI_API_KEY=<your-api-key-here>
HUGGINGFACE_API_TOKEN=<your-access-token-here>

Run the app locally:

streamlit run app.py

Once the app is running:

Upload an image to the interface.

The app generates:

Scenario text from the image.

A short story based on the scenario.

An audio narration of the story.

The app is also deployed on Streamlit Cloud and Hugging Face Space for easy access.

▶️ Installation

Clone the repository:

git clone https://github.com/alimdsaif3/Image-to-Story-Converter.git

Install the required dependencies:

pip install -r requirements.txt

Set up your API keys in a .env file as described above, then run the app with:

streamlit run app.py

©️ License

Distributed under the MIT License. See the LICENSE file for more details.

🤝 Contributions

If you like this project, please ⭐ the repository! Contributions are welcome. Submit a pull request with your improvements or suggestions.

#### Follow me on [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-saif-ali-9815a774/) &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alimdsaif3)

