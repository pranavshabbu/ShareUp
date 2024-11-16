ShareUp is a web application for secure file storage and sharing, built using python and MySQL. The project mainly illustrates concepts of information security, such as encryption, digital signatures, searchable encryption etc.

To try it out:

Create a new python project in the IDE of your choice and copy these files into that folder.

Run the following commands in terminal to install the required python packages:
pip install flask
pip install mysql-connector-python
pip install bcrypt
pip install pycryptodome
pip install python-docx
pip install PyPDF2
pip install python-pptx

Setup the parameters in dbconnect.py according to your localhost and run dbconnect.py. This will create the database and the required tables. A single user is created, with the username 'admin' and password 'adminpass'.

Run generate_aes_key.py to get the secret key used for encryption.
Run signatures.py to generate the private and public keys for digital signatures.

Run app.py by running 'python app.py' in the terminal.
You're in! Create a new user using 'signup' and try out the application. Try uploading the 'sample.txt' file in the 'uploads' folder.
