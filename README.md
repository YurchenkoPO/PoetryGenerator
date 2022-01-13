# poetry_generator
Repo with project for Architecture of computer networks course.
Generates poetry of famous poets by beginning

Now the application can generate texts that rely on poems of:
* Shakespeare
* Pushkin

# Architecture
The app consists of:
* LSTM model for text generation (Aleksandr Delev, M05-013e)
* Flask app (Yurchenko Petr, M05-013e)

# How to run:

1. Clone the repository
2. Create conda env:

```bash
ENV_NAME=poetry_generator
conda create -y -n $ENV_NAME python=3.7
conda activate $ENV_NAME
pip install -r requirements.txt
ipython kernel install --user --name=$ENV_NAME
```

3. Run next code in console:

```bash
export FLASK_APP=poetry_generator.py
flask run
```

4. Open local URL
5. Enjoy! :)
