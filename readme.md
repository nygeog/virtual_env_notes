Create a folder in the current directory which will contain the Python executable files, and a copy of the pip library which you can use to install other packages. 

	virtualenv env

Activate Virtual Env.

	source env/bin/activate
	
Deactivate Virtual Env.	

	deactivate
	
	
http://docs.python-guide.org/en/latest/dev/virtualenvs/

### Save 
Press i to enter inline insert mode. Type the description at the very top, press esc to exit insert mode, then type :x! (now the cursor is at the bottom) and hit enter to save and exit. You can also add the commit message from the command line. and the editor will not be opened in the first place.
	
Install Requirements.txt
* http://stackoverflow.com/questions/7225900/how-to-pip-install-packages-according-to-requirements-txt-from-a-local-directory

		pip install -r /path/to/requirements.txt
	
