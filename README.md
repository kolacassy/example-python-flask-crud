# Example Python Flask Crud

 Simple example python flask crud app for sqlite.
 
## Screenshots


![image](screenshots.png)  
 
 
### Installing (for linux)

open the terminal and follow the white rabbit.


```
git clone https://github.com/slimprepdevops/example-python-flask-crud.git
```
```
cd example-python-flask-crud/
```
```
pip install flask
```
```
sudo apt install python3.8-venv
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install --upgrade pip
```
```
pip install -r requirements.txt
```
```
export FLASK_APP=crudapp.py
```
```
flask db init
```
```
flask db migrate -m "entries table"
```
```
flask db upgrade
```
To make the flask app visible from your public IP, run the command with the --host part
```
flask run --host=0.0.0.0
```
You can now view your application from your browser on your public IP

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
