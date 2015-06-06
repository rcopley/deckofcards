# deckofcards
An API to simulate a deck of cards

The docs are on http://deckofcardsapi.com

Feel free to fork and do whatever you want with the project, it's all under the MIT license.

Install
-------

From inside the application's directory, run the following:

```
pip install -r requirements.txt
python manage.py migrate
```

Usage
-----

```
python manage.py runserver 0.0.0.0:8000
```

Once the server is running you can access it at http://127.0.0.1:8000 (or the machine's address if the machine is remote). API documentation is available at the app's front page or at http://deckofcardsapi.com.

The server can be stopped using Ctrl+C.