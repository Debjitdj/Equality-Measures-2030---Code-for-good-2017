# Equality Measures 2030

This project was done for **Code for good**, organized by J.P.Morgan on 17th November 2017. We developed this web app for a non-profit organization, called Equal Measures 2030. We were asked to use graphs and charts to visualize the data they provided us. 

### Prerequisites

* [Python 3.6](https://www.python.org/downloads/) is required. Though [Anaconda 4.3](https://www.anaconda.com/download/) is recommended.
* Need a browser (Other than Internet Explorer) to launch the web app.

### Installing

Download all the files and keep them in the same folder. You need to run the *restAPInew.py* file to start a local testing server. On your terminal (or Windows Command Prompt or git bash terminal or something similar), go to the directory where you have downloaded all the files. 

Here is an example for Windows Command Prompt. 

```
C:\Users\Debjit>cd jpmorgan

C:\Users\Debjit\jpmorgan>cd team-21

C:\Users\Debjit\jpmorgan\team-21>
```
Here is an example for git bash (almost similar)

```
Debjit@admin MINGW64 ~
$ cd jpmorgan/

Debjit@admin MINGW64 ~/jpmorgan (master)
$ cd team-21/

Debjit@admin MINGW64 ~/jpmorgan/team-21 (master)
$

```

Then run the *restAPInew.py* file with this code-

For Windows

```
C:\Users\Debjit\jpmorgan\team-21> python restAPInew.py

```
For others

```
Debjit@admin MINGW64 ~/jpmorgan/team-21 (master)
$ python restAPInew.py

```

**Don't press** CTRL+C otherwise it will stop the python code which will stop the server and the web app will not work.


When the local server is working, open a browser and go to this link *http://localhost:5000* to open the home page of the web app.

## Check out what we have done

There are *four* pages that we have made-

* http://localhost:5000
* http://localhost:5000/line_graph
* http://localhost:5000/complex_graph
* http://localhost:5000/maps

## Built With

* HTML, CSS, JS
* Python
* [Flask](http://flask.pocoo.org/)
* [Jinja2](http://jinja.pocoo.org/docs/2.10/)
* [Bootstrap](https://getbootstrap.com/)
* [ChartJS](http://www.chartjs.org/)

## Contributing

Please read [CONTRIBUTING.md](https://) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Debjit Mandal** - *Front End, Design*
* **Adela Ye** - *Front End, Design*
* **Zihan Ye** - *Back End (Server-Side)*
* **Andi Draghici** - *Back End (Data processing, Python)*
* **Sam McArdle** - *Back End (Data processing, Python)*


## Acknowledgments

* Many thanks to our mentors who were guiding us during the competiotion. 
* Thanks to your team members who worked so hard and spent that whole night to fix all the bugs and make our project run flawlessly.
