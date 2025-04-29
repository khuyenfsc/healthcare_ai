# Installation and Setup Guide

## 1. Install Dependencies

First, you need to install all required dependencies listed in the `requirements.txt` file.

**Run the following command** in the root directory of the project:

```bash
pip install -r requirements.txt
This command will automatically install all the libraries required for your project.

## 2. Clone the VietTTS Repository into tts/ Directory
Next, you need to clone the VietTTS repository into a new directory called tts/. The tts/ folder does not exist in your project before this step, so you will need to create it by cloning the repository.

Run the following commands to clone the repository:

bash
Copy
Edit
git clone https://github.com/NTT123/vietTTS.git tts
cd tts
git checkout f5c5d0956d6ca2bf407011370f75a30dfd536c2f
This will clone the VietTTS repository into the tts/ directory and checkout the specific commit f5c5d0956d6ca2bf407011370f75a30dfd536c2f.

## 3. Ensure the tts/ Directory is Recognized in Python
If you want to make sure Python recognizes the vietTTS library, you can add the tts/ directory to the PYTHONPATH.

Run the following command in your terminal:

bash
Copy
Edit
export PYTHONPATH="$PYTHONPATH:$(pwd)/tts"
You can also add this command to a .env file or a startup script to set it automatically every time you run the application.

## 4. Configure and Start Using
Once you have completed the steps above, you can start using the vietTTS library and the functionalities of the project. Make sure all libraries and dependencies are correctly installed.


