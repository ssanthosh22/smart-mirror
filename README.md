Smart-Mirror
============

Raspberry pi powered mirror which can display the news, weather, and
time.

Installation and Updating
-------------------------

### Code

If you have
[git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
installed and clone the repository. If you have
[git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
installed, clone the repository.

    git clone git@github.com:Santhosh-root/smart-mirror.git

**Alternatively, you can download a zip file containing the project
(green button on the repository page)** Navigate to the folder for the
repository

    cd smart-mirror

### Install your dependencies

make sure you have [pip](https://pip.pypa.io/en/stable/installing/)
installed before doing this

    sudo pip install -r requirements.txt

    sudo apt-get install python-imaging-tk

### Add your api token

Make sure vim is installed on your system: `sudo apt-get install vim`
Use `vim` to edit you file

    vim smartmirror.py

replace `weather_api_token` with the token you got from forecast.io \#\#
Running To run the application run the following command in this folder

    python smartmirror.py

Demo and Build Instructions
---------------------------

[![alt text](https://imgur.com/a/BQNCDZZ)]
