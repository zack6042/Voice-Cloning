# Voice-Cloning
Voice Cloning application using the SO-VITS_SVC architecture with models for some famous people for inference

#Disclaimer
Disclaimer: This application is intended for educational and research purposes only. Voice cloning technology has the potential to be misused, and unauthorized use of someone's voice without their explicit permission may lead to legal consequences. It is crucial to respect privacy and obtain proper consent before using this technology.
README for Flask Web Application using SO-VITS-SVC Architecture
Welcome to the Flask web application that utilizes the SO-VITS-SVC architecture for voice cloning and synthesis. This README will guide you through the setup, usage, and key resources associated with this project.

#Table of Contents
Introduction
Features
Installation
Prerequisites
Clone the Repository
Set Up Virtual Environment
Install Dependencies
Download Pre-trained Models
Usage
Running the Application
Using Docker
Resources
License
Contributing
Introduction
This project implements a Flask web application that leverages the SO-VITS-SVC (Soft Voice Conversion and Variational Inference Text-to-Speech) architecture. The SO-VITS-SVC model enables robust voice conversion and synthesis by extracting acoustic features and conditioning the VITS model to produce high-quality, personalized voice outputs.

Features
Voice cloning from input audio files.
Real-time speech synthesis using pre-trained models.
User-friendly web interface for uploading audio files and listening to synthesized outputs.
Installation
Prerequisites
Python 3.7 or higher
pip (Python package installer)
Git
CUDA-compatible GPU (for Docker usage)
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Set Up Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies
bash
Copy code
pip install -r requirements.txt
Download Pre-trained Models
Download the pre-trained models from the SO-VITS-SVC GitHub repository:

SO-VITS-SVC GitHub Repository
Usage
Running the Application
To run the Flask application locally:

bash
Copy code
export FLASK_APP=app.py
flask run
Open your web browser and navigate to http://127.0.0.1:5000 to access the application.

Using Docker
To run the application using Docker, use the following command:

bash
Copy code
docker run --gpus all -p 8080:8080 --name voicecloning abdelrahman915/imageprefinal:Lastdance
Navigate to http://127.0.0.1:8080 in your web browser to access the application.

Resources
SO-VITS-SVC GitHub Repository
Colab Notebook for SO-VITS-SVC
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
We welcome contributions to this project. Please open an issue or submit a pull request on GitHub.
Special thanks to my amazing team:
-Abdelrahman915

For major changes, please open an issue first to discuss what you would like to change.
