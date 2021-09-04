# Federated Learning framework - Server from nanara1119
- using Django
- add estimation stage in data preprocessing
- share statistical information with all clients

5. pip install -r requirements.txt<br>

# run
1. python manage.py runserver
2. http://127.0.0.1:8000/
3. show "index ok"
 
# make zip file 
include file & folder
<ol>
<li>.ebextensions</li>
<li>requirements.txt</li>
</ol>


exclude file & folder
<ol>
<li>.git</li>
<li>.idea</li>
<li>venv (auto make from requirements.txt)</li> 
<li>.gitignore</li>
</ol>

# API
<ol>
<li>[get] / <br>
- status check</li>
<li>[get] /weight <br>
- request global weight</li>
<li>[put] /weight <br>
- update local weight</li>
</ol>