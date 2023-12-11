![hbnb logo](https://i.imgur.com/GM1iQ0P.png)

# <p align = "center">HolbertonBnB</p>

# <p align = "center">AirBnB Clone - Web Flask</p>

## Learning Objectives

- What is a Web Framework
- How to build a web framework with Flask
- How to define routes in Flask
- What is a route
- How to handle variables in a route
- What is a template
- How to create a HTML response in Flask by using a template
- How to create a dynamic template (loops, conditions…)
- How to display in HTML data from a MySQL database

![Step flask](https://i.imgur.com/WdM4CP5.png)

## Tasks
- **0-hello_route.py** : script that starts a Flask web application
  - 1 route :
    - `/` : display “Hello HBNB!”
- **1-hbnb_route.py** : script that starts a Flask web application
  - 2 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
- **2-c_route.py** : script that starts a Flask web application
  - 3 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
    - `/c/<text>` : display “C ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
- **3-python_route.py** : script that starts a Flask web application
  - 4 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
    - `/c/<text>` : display “C ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/python/` & `/python/<text>` : display “Python ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
- **4-number_route.py** : script that starts a Flask web application
  - 5 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
    - `/c/<text>` : display “C ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/python/` & `/python/<text>` : display “Python ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/number/<n>` : display “`n` is a number” only if `n` is an integer
- **5-number_template.py** : script that starts a Flask web application
  - 6 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
    - `/c/<text>` : display “C ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/python/` & `/python/<text>` : display “Python ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/number/<n>` : display “`n` is a number” only if `n` is an integer
    - `/number_template/<n>` : display a HTML page only if `n` is an integer
- **6-number_odd_or_even.py** : script that starts a Flask web application
  - 7 routes :
    - `/` : display “Hello HBNB!”
    - `/hbnb` : display “HBNB”
    - `/c/<text>` : display “C ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/python/` & `/python/<text>` : display “Python ”, followed by the value of the `text` variable (replace underscore `_` symbols with a space)
    - `/number/<n>` : display “`n` is a number” only if `n` is an integer
    - `/number_template/<n>` : display a HTML page only if `n` is an integer
        - `H1` tag: “Number: `n`” inside the tag `BODY`
    - `/number_odd_or_even/<n>` : display a HTML page only if n is an integer:
        - `H1` tag: “Number: `n` is `even|odd`” inside the tag `BODY`
