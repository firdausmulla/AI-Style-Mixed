# AI-Style-Mixer
I have created a GenAI based web application that uses machine learning model. This application is completely made using Google Colab notebook. It is used to apply the artistic style of one image to another.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/AI-Style-Mixer-Colab/blob/main/AI_Style_Mixer.ipynb)

*(Click the "Open in Colab" badge above to run the project yourself!)*

## How it Works

The app asks the user to upload two images:
1.  **A Content Image** (like a selfie or a photo)
2.  **A Style Image** (like a painting or a pattern or anything the user want their image to be styled in)

The AI backend then "mixes" them, re-drawing the content image in the style of the style image provided by the user. It displays all three images side-by-side.

The below is the SS of my web page.
<img width="1321" height="835" alt="image" src="https://github.com/user-attachments/assets/22820a79-12b0-43c1-8193-776686192384" />


## Tech Stack
* **Python**
* **Google Colab** (as the development and hosting environment)
* **Flask** (as the web server backend)
* **pyngrok** (to create a secure public URL for the app)
* **TensorFlow & TensorFlow Hub** (to load and run the ML model)
* **HTML/CSS** (for the frontend)

## How to Run This Project

1.  **Click the "Open in Colab" Badge** at the top of this README.
2.  **Get an `ngrok` Authtoken:**
    * Go to [https://dashboard.ngrok.com/get-started/your-authtoken](https://dashboard.ngrok.com/get-started/your-authtoken) follow the steps and sign up for a free account.
    * Copy your authtoken.
3.  **Run the Cells:** In the Colab notebook, run the cells in order from top to bottom.
    * When you run **Cell 2**, it will ask for your `ngrok` authtoken. Paste it in and press Enter.
4.  **When you run the final, it will load the models, and print a URL that looks something like `https://[some-id].ngrok.io`.
5.  **Click that URL** to open your live web application in a new tab!
