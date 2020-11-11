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

# install cli
git clone https://github.com/aws/aws-elastic-beanstalk-cli-setup.git

# For Ubuntu and Debian
apt-get install \
    build-essential zlib1g-dev libssl-dev libncurses-dev \
    libffi-dev libsqlite3-dev libreadline-dev libbz2-dev

./aws-elastic-beanstalk-cli-setup/scripts/bundled_installer

eb platform select
- pick python (option 10)

eb init
- command configure the eb-cli
- 

eb init 

eb create oowlishlab --region us-east-1

eb open