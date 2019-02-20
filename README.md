# Django_linux
Shorten django commands, (works on linux (all debian distros))

djan
usage:
	djan <command>  
	is equalent to,
	python3 manage.py <command>

	```bash
	djan runserver
	```

djangogo
usage:
	```bash
	djangogo
	```

	equalent of:

	```bash
	python3 manage.py makemigrations
	python3 manage.py migrate
	python3 manage.py runserver
	```


Feel free to add more

I made this cuz typing all the above commands became a pain, and python is a language built to be short and sweet :p


INSTALLATION

```bash
git clone https://github.com/amey-kudari/Django_linux.git
sudo mv djangogo /usr/bin
sudo mv djan /usr/bin
chmod +x /usr/bin/djangogo
chmod +x /usr/bin/djan
```

OR run install.sh
```bash
sudo bash install.sh
```
