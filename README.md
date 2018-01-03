<p>This project has been taken from <a href="https://www.digitalocean.com/community/tutorials/how-to-structure-large-flask-applications" target="_blank">here</a></p>
<h1>Python Boilerplate</h1>
<h3>A boilerplate Python project using Flask</h3>
<p>Requirements:</p>
<ul>
<li>Flask-SQLAlchemy</li>
<li>Flask-WTF</li>

<h2>1. Setting up Python, pip and virtualenv</h2>
<p><strong>sudo pip install virtualenv</strong></p>
<code>sudo pip install virtualenv</code>
<h2>2. Structure</h2>
<code>
~/LargeApp<br/>
    |-- run.py
    |-- config.py
    |__ /env             # Virtual Environment
    |__ /app             # Our Application Module
		|-- __init__.py
		|-- /module_one
			|-- __init__.py
			|-- controllers.py
			|-- models.py
		|__ /templates
			|__ /module_one
				|-- hello.html
		|__ /static
		|__ ..
		|__ .
	|__ ..
	|__ .
</code>
<h3>3. Creating Application Folders</h3>
<code>
mkdir ~/LargeApp<br/>
mkdir ~/LargeApp/app<br/>
mkdir ~/LargeApp/app/templates<br/>
mkdir ~/LargeApp/app/static<br/>
</code>
<h3>4. Creating A Virtual Environment</h3>
<p></p>
<code>
cd         ~/LargeApp<br/>
virtualenv env
</code>
<h3>5. Create Application Files</h3>
<code>
touch ~/LargeApp/run.py<br/>
touch ~/LargeApp/config.py<br/>
touch ~/LargeApp/app/__init__.py
</code>

