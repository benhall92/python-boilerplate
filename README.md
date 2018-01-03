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
<h3>4. Creating A Virtual Environment</h3>
<p></p>
<pre>
<code>
cd         ~/LargeApp  
virtualenv env
</code>
</pre>
<h3>5. Create Application Files</h3>
<pre>
<code>
touch ~/LargeApp/run.py  
touch ~/LargeApp/config.py  
touch ~/LargeApp/app/__init__.py
</code>
</pre>

