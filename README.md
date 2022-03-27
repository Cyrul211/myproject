Instalacja Flask
#tworzenie pliku

mkdir myproject 

cd myproject  
#utworzenie wirtualnego środowiska oraz jego instalacja

py -3 -m venv venv 

venv\Scripts\activate 

pip install Flask 

set FLASK_APP=hello.py 

flask run 

#utworzenie pliku requirements.txt 

pip install pipreqs 
pipreqs 
