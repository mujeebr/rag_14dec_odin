# creating a virtual environment and activated it
python -m venv "rag_web"
source rag_web/bin/activate - MAC
# we used commands like pwd to check the current WD
# touch Readme.MD is a new file we created to write the steps we followed in this project
# clear, cls
# pip install -r requirements.txt
# git add filename, git add .
# git status
# streamlit run app.py - to run a streamlit application
streamlit run your_script_name.py --server.port=8509

docker build -t myrag:v1 .
docker run -p 8080:8080 myrag:v1
