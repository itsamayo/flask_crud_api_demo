# REST API With Flask & SQL Alchemy & Marshmallow

> Products API using Python Flask, SQL Alchemy and Marshmallow

## Quick Start

``` bash
# Install dependencies
$ pip install -r requirements.txt

# Create DB
$ python
>> from app import db
>> db.create_all()
>> exit()

# Run Server (http://localhost:8080)
flask run
```

## Endpoints

* GET     /product
* GET     /product/:id
* POST    /product
* PUT     /product/:id
* DELETE  /product/:id