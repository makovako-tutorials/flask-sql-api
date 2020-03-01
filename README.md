# Flask + SQLAlchemy

Created after folowing [this](https://www.youtube.com/watch?v=PTZiDnuC86g) video.

It is basic crud api with saving data to sqlite db.

## Initialize databaze

- in python console
- `from app import db`
- `db.create_all()`

## Routes

- `/product` - GET - get all products
- `/product` - POST - create product
- `/product/1` - GET - get product with id 1
- `/product/1` - PUT - update product with id 1
- `/product/1` - DELETE - delete product with id 1

## Notes

- flask for routing
- sqlalchemy for accessing database and not using sql language
- marshmellow for serialization
- `@app.route('/route/\<param\>)
- classes for resources
- schema for formating resources and lists of them