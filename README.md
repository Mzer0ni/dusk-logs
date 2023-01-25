# Dusk logs thing

Strip your dusk.log and put it in data folder:

    grep '"run state transition"\|"Accepted block from provisioner"' dusk.log > dusk_log_stripped.log

Oh and you will need Python on your machine

Optional use a python virtual env so you don't pollute your local environment too much.
https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

    python3 -m venv env
    source env/bin/activate

Install requirements:

    pip install -r requirements.txt

Launch Jupyter Lab:

    jupyter lab


    