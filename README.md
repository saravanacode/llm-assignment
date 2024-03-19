# ProtonDatalabs AI developer Assignment - Chatbot application



## Project structure

In this project you find 2 directories

1. `backend` containing the server side **python** code
2. `frontend` containing the client side **typescript** code.\
   In both these directories, it is your job to complete the missing modules and add necessary functionalities to make the app fully functional.
3. And a streamlit app.py code that is the main code i have created

### Backend

**Requirements**: Python 3.10 or above and streamlit 

1. `app.py` which is the entry point to streamlit app
2. This project has a few Python packages as dependencies, you can install them in your virtual environment using `requirements.txt`. If you were to use other dependencies, then please add them to `requirements.txt`.
3. Then install the python packages using `pip install -r requirements.txt`


##USAGE

To run this app

1.) git clone the repository https://github.com/saravanacode/llm-assignment.git
2.) Then into the project directory and run streamlit run app.py


##Working 

1.) The app get pdf,txt,img,csv or any file and process it as chunks and convert it into embedding with sentence transformer (all-MiniLM-L6-v2)
2.) Then it procces it as vectors and the vectors are passed with the client prompt to get the appropiate results with the llama.cpp model(mistral-7b-instruct-v0.1.Q2_K.gguf)

##POINTS
1.) This app can only run in cuda or gpu devices 
2.) if you dont have gpu run ths in colab with document_chatbot.ipynb or with this link
