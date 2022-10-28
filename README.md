# First_Streamlit_Application
First streamlit application to create a fast Python based UI


1. Click on the 'Code' tab on the Github repo page -> copy the branch URL -> git clone <url> in your local repository space
   
2. Create a virtual environment in the local directory named "virtual_env". These commands are to be run on your Anaconda Promp (Note that First_Streamlit_Application is my repo/directory name for this project):
   >python -m venv ...\First_Streamlit_Application\virtual_env
   
3. Activate the virtual environment:
   >...\First_Streamlit_Application\virtual_env\Scripts\activate
   
4. Create the following folders (and file) under the First_Streamlit_Application directory:
   - .streamlit/ (dot is important)
   - app/
   - data/
   - assets/
   - requirements.txt

5. You can just mimic the sub-directories and files from my repository. Preferably, build them yourself rather than just cloning my repo :-)

6. Under /app, utils.py must hold the head, body and content related functions of the UI being built. main.py must contain a call to the functions in utils.py. 
   
7. From Anaconda Prompt, run this command:
   >streamlit run app/main.py
   
# Customizations
   a). Create a solarized theme:
    >vi .streamlit/config.toml
     [theme]
     primaryColor="#d33682"
     backgroundColor="#002b36"
     secondaryBackgroundColor="#586e75"
     textColor="#fafafa"
     font="sans serif"

