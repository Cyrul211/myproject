mkdir myproject 
cd myproject  
py -3 -m venv venv 
venv\Scripts\activate 
pip install Flask 
set FLASK_APP=hello.py 
flask run 
pip install pipreqs 
pipreqs 
