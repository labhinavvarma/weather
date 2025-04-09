Create venv envirment 
# For Windows
python -m venv venv
venv\Scripts\activate

# For Linux
python3 -m venv venv
source venv\bin\activate

#install mcp[cli]
pip install "mcp[cli]"

#to run the file 
python run server.py


-->optional
#install uv
pip install uv

#version check for uv
uv --version

#running with uv
uv run server.py
