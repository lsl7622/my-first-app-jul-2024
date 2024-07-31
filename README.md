# my-first-app-jul-2024

## Setup
Create virtual enviroment: 
#sh is a shell command so it appears in a clean way 
```sh
conda create -n ump-env python=3.11
```

Activate the enviroment:

```sh 
conda activate ump-env
```

install packages: 

```sh 
#pip install requests
#pip install plotly
#pip install python-dotenv

# best practice to list the packages in the requirements.txt file:
pip install -r requirements.txt
```


## Usage

Run the script:

```sh
python app/unemployment.py

# equivalent:
python -m app.unemployment
```
