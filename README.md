# Lab1

## _Common steps_

### Create virtual environment using python3.11

```
python3.11 -m venv venv
```

### Activate virtual environment (Windows)

```
venv\Scripts\activate
```

### Activate virtual environment (Unix-like)

```
source venv/bin/activate
```

### Upgrade pip

```
pip install -U pip
```

### Install development dependencies

```
pip install -r requirements.txt
```

### Migrate DB

```
python manage.py migrate
```

