# Projects
Notes
Installation requirements
-Download and Install Microsoft Visual Studio community from visualstudio.microsoft.com 
-Download and Install Python 3.11.2 from python.org
-Open Microsoft Visual Studio and open the folder Student online notes
-Right click on the folder in visual studio and open in terminal
-Now start by creating a virtual environment and activate 
      e.g. py -m venv env or virtualenv env(creation of virtual environment)
           env\Scripts\activate.bat(activation of virtual environment)
-Install requirements.txt
      e.g. py -m pip install -r rqeuirements.txt or pip install -r requirements.txt
-Create super user(optional)
      e.g. py -m manage createsuperuser
-Run migration
      e.g. py -m manage migrate
-Then lastly we runserver
      e.g. py -m manage runserver
