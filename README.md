# MyGoogleWebApp
Google Web App Project

Installation:
- Create a cloud web app (https://console.cloud.google.com/appengine)
- Select pyhton project on cosole download cloud sdk and install it, gcloud init.
- do the following to install app-engine-python:
  - $ gcloud components install app-engine-python
  - Create a PyCharm project (Can be used sample python project from https://github.com/GoogleCloudPlatform/python-docs-samples) 
  use appengine/flexible/hello_world sample in it.
  - For PyCharm prooject setting, google_appengine path is one of them according to installation (for current user or all): 
    - C:\Users\<username>\AppData\Local\Google\Cloud SDK\google-cloud-sdk\platform\google_appengine\
    - C:\Program Files (x86)\Google\Cloud SDK\google-cloud-sdk\platform
  - Select bundled python environemnt (C:\Program Files (x86)\Google\Cloud SDK\google-cloud-sdk\platform\bundledpython)
  - Install requirements for this project if needed in PyCharm.
  - Run locally with python run environment not a appengine server task. (Like python main.py)
    - https://stackoverflow.com/questions/46432589/how-to-use-python-3-with-google-app-engines-local-development-server)
