# AirBnB Clone

![](./images/airbnb.png)

The AirBnB clone is a full stack project developed during the fundations stage of Holberton school, this project is realized with technologies such as Python, flash and MySql database connection for the logical part and JavaScript, CSS, HTML for the dynamic part.

This is the most updated and complete sample of the project since the project was made in several versions and this package gathers all the previous versions.

![](./images/web_dynamic_diagram.png)

## Previous versions

* holbertonschool-AirBnB_clone
* holbertonschool-AirBnB_clone_v2
* holbertonschool-AirBnB_clone_v3
* holbertonschool-AirBnB_clone_v4

## Technologies


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

# Install

* Clone this repository: `git clone "https://github.com/alejuran/AirBnB_clone.git"`
* Access AirBnb directory: `cd AirBnB_clone`
* Run hbnb(interactively): `./console` and enter command
* Run hbnb(non-interactively): `echo "<command>" | ./console.py`

The project was developed in several iterations, being V4 the last one. This iterations encompassed several concepts and integrations that will be explained below.

## The Console

The first iteration of the project consisted on building an interactive console in order to allow for development testing.

The Console was coded in order to work with a temporary storage engine based on JSON, and included the next features:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

The console has 2 modes.

**Interactive**

## Web Static

This part of the project consisted in building the basic CSS and HTML source code.


## MySQL

This section consisted on the data modeling for the relational database in MySQL.


## Web Framework

This iteration consisted on building the first approach to dynamic content for the application by using Flask and Jinja, and effectively having Server Side Render.

For this development, the MySQL database started being used in order to serve content to the client, and provide it with back end based features.

All of the HTML and CSS source code started being hosted in the server, and no items were hard coded, but instead produced through dynamic data integration.


## RESTful API

Although the Server Side Render with Flask and Jinja was interesting, this section consisted on developing a different approach to dynamic content generation, starting with a RESTful API.

This Application Programming Interface was built with Flask and SQLAlchemy in order to work with MySQL and respond to HTTP requests.

The endpoints can be seen below.

## Web Dynamic

This was the final iteration of the project and consisted in changing the Server Side Render for Client Based Render using JavaScript with jQuery, and the RESTful API from before.

## About Myself

I am a software developer with a passion for technology and an insatiable curiosity for understanding how things work from the inside.

My experience spans a wide range of technologies, including HTML, CSS, Python, C, JavaScript, React, Django, Flask, Bootstrap, MySQL, MongoDB, Git, Sass, linux and terminal commands. 

I'm always excited to keep learning and discovering new tools and technologies. I love collaborating on challenging projects and finding innovative solutions to problems. Programming for me is more than a job, it's an art form that allows me to bring ideas to life and create impactful digital experiences.

```
AirBnB_clone$./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  create  destroy  help  quit  show  update

(hbnb) all MyModel
** class doesn't exist **
(hbnb) create BaseModel
7da56403-cc45-4f1c-ad32-bfafeb2bb050
(hbnb) all BaseModel
[[BaseModel] (7da56403-cc45-4f1c-ad32-bfafeb2bb050) {'updated_at': datetime.datetime(2017, 9, 28, 9, 50, 46, 772167), 'id': '7da56403-cc45-4f1c-ad32-bfafeb2bb050', 'created_at': datetime.datetime(2017, 9, 28, 9, 50, 46, 772123)}]
(hbnb) show BaseModel 7da56403-cc45-4f1c-ad32-bfafeb2bb050
[BaseModel] (7da56403-cc45-4f1c-ad32-bfafeb2bb050) {'updated_at': datetime.datetime(2017, 9, 28, 9, 50, 46, 772167), 'id': '7da56403-cc45-4f1c-ad32-bfafeb2bb050', 'created_at': datetime.datetime(2017, 9, 28, 9, 50, 46, 772123)}
(hbnb) destroy BaseModel 7da56403-cc45-4f1c-ad32-bfafeb2bb050
(hbnb) show BaseModel 7da56403-cc45-4f1c-ad32-bfafeb2bb050
** no instance found **
(hbnb) quit
```

## Bugs
No known bugs at this time. 

## Author

Alejanro Urán

[![Twitter: alejuran](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/alejuran)
[![Linkedin: alejandroua](https://img.shields.io/badge/-linkedin-blue?style=for-the-badge&logo=Linkedin&Color=black&link=https://www.linkedin.com/in/alejandroua/)](https://www.linkedin.com/in/alejandroua/)

