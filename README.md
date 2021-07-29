# Flask-Auth

Flask-Auth is a collection of flask authentication libraries. 

## Flask-Security

### Basic SQLAlchemy Applicaiton

#### Dependencies
```bash
$ pip install flask-security flask-sqlalchemy
$ pip install wtforms[email]
$ pip install bcrypt
```

#### Environment Variable
```bash
$ export SECURITY_PASSWORD_SALT='<ome artitrary super secret string>'
```

#### Files
```
app.py
templates/index.html
```

### Basic SQLAlchemy Application with session