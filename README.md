
      pip install flask 
      pip install flask-sqlalchemy 
      pip install flask-marshmallow 
      pip install marshmallow-sqlalchemy 
      pip install flask-restx
      pip install psycopg2-binary


Create DB

    python
    from app import db
    db.create_all() exit()

Start Server

     flask run
or 

     python app.py

     app.config['SQLALCHEMY_DATABASE_URI'] = 'sqlite:///db.db'

or

    app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://root:12345678@localhost/flask'

mysql(db)://root(user):12345678(password)@localhost/flask(db name)
or

    app.config['SQLALCHEMY_DATABASE_URI'] = 'postgres://postgres:123456@localhost/flask'
