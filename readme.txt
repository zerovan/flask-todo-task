pip install virtualenv
virtualenv myproject
myproject\Scripts\activate
pip3 install flask flask-sqlalchemy
// write app.py file
python app.py // run the server

// for migration after writing the code
// shell into python
python
set FLASK_APP=app.py
flask shell | python
from app import db
db.create_all()
exit()
