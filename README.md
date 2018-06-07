
POCH is a food order site built on Django with the CRUD functionality.


For running this, you need to have the following requirements
1. Python 2.7
Can download it here.
(MAC Users-https://www.python.org/ftp/python/2.7.15/python-2.7.15-macosx10.9.pkg & 
Windows Users- https://www.python.org/ftp/python/2.7.15/python-2.7.15.amd64.msi)
2. pip
pip is a package manage for Python. It makes installing and uninstalling Python packages (such as Django!) very easy. 
For the rest of the installation, we’ll use pip to install Python packages from the command line.

To install pip on your machine, go to https://pip.pypa.io/en/latest/installing/, and follow the Installing with get-pip.py instructions.

Install virtualenv and virtualenvwrapper¶
virtualenv and virtualenvwrapper provide a dedicated environment for each Django project you create. While not mandatory,
this is considered a best practice and will save you time in the future when you’re ready to deploy your project. Simply type:

pip install virtualenvwrapper-win
Then create a virtual environment for your project:

mkvirtualenv myproject
The virtual environment will be activated automatically and you’ll see “(myproject)” next to the command prompt to designate that. 
If you start a new command prompt, you’ll need to activate the environment again using:

3. Django==1.8.5

Install Django¶
Django can be installed easily using pip within your virtual environment.

In the command prompt, ensure your virtual environment is active, and execute the following command:

pip install django
This will download and install the latest Django release.

After the installation has completed, you can verify your Django installation by executing django-admin --version in the command prompt.
