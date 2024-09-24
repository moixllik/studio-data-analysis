run:
	@python3 src/

pkgs:
	sudo apt update -y
	sudo apt install -y python3-venv python3-pip

venv:
	python3 -m venv venv
	source venv/bin/activate

install:
	pip install -r requirements.txt

freeze:
	pip freeze > requirements.txt

