<p>This project has been taken from <a href="https://www.digitalocean.com/community/tutorials/how-to-structure-large-flask-applications" target="_blank">here</a></p>
<h1>Python Boilerplate</h1>
<h3>A boilerplate Python project using Flask</h3>
<p>Requirements:</p>
<ul>
<li>Flask-SQLAlchemy</li>
<li>Flask-WTF</li>

<h2>1. Setting up Python, pip and virtualenv</h2>
<p><strong>sudo pip install virtualenv</strong></p>
<pre>
<code>
sudo pip install virtualenv  
sudo pip install flask  
sudo pip install Flask-WTF  
sudo pip install flask-sqlalchemy
</code>
</pre>
<h2>2. Structure</h2>
<pre>
<code>
~/LargeApp  
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
</pre>
<h3>3. Creating Application Folders</h3>
<pre>
<code>
mkdir ~/LargeApp  
mkdir ~/LargeApp/app  
mkdir ~/LargeApp/app/templates  
mkdir ~/LargeApp/app/static  
</code>
</pre>
<h3>4. Run the App locally</h3>
<p>CD in to /LargeApp.</p>
<pre>
<code>
python run.py  
</code>
</pre>
<p>Visit the site at http://0.0.0.0:8080/</p>

