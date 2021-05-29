# Depresscape

Depressscape employs semantic analysis to process social media input and diagnose distress in users. The outcome is shown in the form of a rating varying from 0-100, which is shown to the user, and if the depression rate is high, a warning is sent to the user's emergency contact. This system is built to support multiple languages so that users across the world can get profit and identify their depression via social media, allowing them to receive care as soon as possible.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. The project is divide into two part Depresscape App and Backend

### Prerequisites

What things you need to install the software and how to install them

##### Depresscape App

<ul>
<li><a href="https://flutter.dev/docs/get-started/install/windows#get-the-flutter-sdk">Install Flutter</a></li>
<li><a href="https://flutter.dev/docs/get-started/install/windows#android-setup">Android Emulator</a></li>
</ul>

##### Backend

<ul>
<li><a href="https://www.python.org/downloads/release/python-3810/">Python 3.8</a></li>
</ul>

Download both the project and arrange file structure as shown below

```
Depresscape Project
├── depresscape
│   └── ...(Depresscape App Code)
└── backend
    └──...(Depresscape Backend Code)

```

### Installing

A step by step series of examples that tell you how to get a development env running

##### Depresscape App

Step 1:
From Depresscape Project directory which is root directory cd into depresscape:

```
cd depresscape
```

Step 2:
Execute the following command in console to get the required dependencies:

```
flutter pub get
```

Step 3:
Check that an Android Emulator device is running:

```
flutter devices
```

Step 4:
Run the app with the following command:

```
 flutter run
```

Output:

<img src="https://drive.google.com/uc?export=view&id=1FyhHS3SjzHVbyxdxqw1lbH0D2oYfXj6-" width="200" />

##### Backend

Step 1:
From Depresscape Project directory which is root directory cd into backend:

```
cd backend
```

Step 2:
Create a virtual environment:

```
virtualenv -p python3 venv
```

Step 3:
Activate the virtual environment:

```
source venv/bin/activate
```

Step 4:
Installing dependencies for backend:

```
pip install -r requirements.txt
```

Step 5:
Run the backend:

```
python app.py
```

Output:

<img src="https://drive.google.com/uc?export=view&id=1la-pu8okqrePr5WbUCl8Pk38jy_ogDJj"  />
