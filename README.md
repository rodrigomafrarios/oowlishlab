# Simple Flask Application

## Up and Running

To get the application up and running follow these steps:

1. Create and activate a virtual environment:

```bash
$ python -m venv venv
$ source venv/bin/activate
```

2. Install the dependencies:

```bash
$ pip install -r requirements.txt
```

3. Start the development server:

```bash
$ APP_SECRET_TOKEN=SomeSecretToken python app.py
```

===================================================
# ANSWER
===================================================

* create a secret on AWS Secret Manager
* set aws credentials on the code app.py
* the file `ec2-bootstrap.yaml` is a cloudformation template for launch a ec2 instance and setup python api
* import the template on cloudformation
* create a stack specifying the template `ec2-bootstrap.yaml` and upload it.
