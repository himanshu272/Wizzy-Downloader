# Wizzy-Downloader
A website which lets you download youtube videos and also maintain your profile and past downloads.This website has been developed using the Django Framework.
### Wizzy Downloader : A Walkthrough
##### Home Page
![pink](https://user-images.githubusercontent.com/24290847/27255161-f5a03e1c-5387-11e7-9048-0eba2e1fba5a.png)
![screenshot from 2017-06-17 23-16-22](https://user-images.githubusercontent.com/24290847/27255162-fd40d64a-5387-11e7-93c2-b952cf886d08.png)
![screenshot from 2017-06-17 23-16-07](https://user-images.githubusercontent.com/24290847/27255167-2b144674-5388-11e7-9e23-d2169d18b8d3.png)
![screenshot from 2017-06-17 23-16-16](https://user-images.githubusercontent.com/24290847/27255169-2b16b49a-5388-11e7-9773-b99944f0fa7b.png)
##### Download Page
Simply insert the YouTube link(e.g. https://www.youtube.com/watch?v=ScNNfyq3d_w ) in the given format in the textbox and check the url to get a preview. Click on download to download the video(Downloading uses the pytube module).
![screenshot from 2017-06-17 23-17-51](https://user-images.githubusercontent.com/24290847/27255189-add56c82-5388-11e7-9907-9d3db4347745.png)
##### Profile : Maintain your Downloads list
You can view recently downloaded videos here.
![screenshot from 2017-06-17 23-18-02](https://user-images.githubusercontent.com/24290847/27255197-f6a77b12-5388-11e7-942b-955b657b436b.png)
![screenshot from 2017-06-17 23-18-24](https://user-images.githubusercontent.com/24290847/27255196-f6a5b818-5388-11e7-8c3b-10d3d2c573aa.png)
##### SignUp and become a member
You can only avail all the features if you have registered.
![screenshot from 2017-06-17 23-18-38](https://user-images.githubusercontent.com/24290847/27255206-35de3d7a-5389-11e7-9a7a-2aed00eeb14d.png)
![screenshot from 2017-06-17 23-18-45](https://user-images.githubusercontent.com/24290847/27255207-35e2bc38-5389-11e7-94ef-5e2fbd7f3144.png)

### Installation Guide
##### Installing and Setting up Git
**Step-1**: Installing Git
•For macOS:
Install Xcode from the App Store this will automatically install git in your system.To check the version of git open the terminal and type "git --version".

•For Ubuntu:
Open the terminal and type the following commands:
"sudo apt-get update"
"sudo apt-get install git"

•For Windows:
1.Download git from the following URL: "https://git-scm.com/download/win"
2.When you've successfully started the installer, you should see the Git Setup wizard screen. Follow the Next and Finish prompts to complete the installation.

**Step-2**: Setup Git
Open your terminal/command prompt and type the following commands:
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
Replace the above username and email with your own username and email.

**Step-3**: Cloning a git repository
1.Go to the repository you want to clone and click on fork.
2.Then click on "Clone or Download".Copy the URL on your clipboard.
3.Open terminal/command prompt and type "git clone (and paste the URL)".
4.Use "cd (name of the repository" command to go to that repository in your system.
5.To check the items inside the repository use "ls" command.

##### Installing and Running Django
**Step-1**: Download Python
To download python just go to this url : https://www.python.org/download/

**Step-2**: pip
pip is already installed if you are using Python 2>=2.7.9 or Python 3>=3.4. To upgrade pip:
• On Linux or macOS:
Open terminal and then type "pip install -U pip".

• On Windows:
Open the command prompt and type "python -m pip install -U pip".
Here pip is a package manager that will help us to install opensource softwares.

**Step-3**: Virtual Environment
Type "sudo pip install virtualenv". This command will install virtual environment on your system. Virtual environment is very useful when it comes to use a software which involves constantly updating and its easy to upgrade Django from the virtual environment.

**Step-4**: Activate virtualenv
• On Linux or macOS:
1.Create a virtual environment folder on your desktop.
2.On your terminal, use "cd" command to go to the Desktop directory.
3.Then type "virtualenv hello"(I put hello, you can put any name you want, this will be the name of your folder).
4.To activate virtual machine, go inside that folder, type cd hello.Once you are inside that folder type "source bin/activate"(this will activate the virtualenv).

• On Windows:
1.Type "mkvirtualenv myproject".The virtual environment will be activated automatically and you'll see "(myproject)" next to the command prompt to designate that.If you start a new command prompt, you'll need to activate the environment again using: "workon myproject".

**Step-5**: Installing Django
All possible options to install can be found in this website : https://www.djangoproject.com/download/
Type "sudo pip install Django". This installs Django distribution on your virtual environment.

**Step-6**: Running the Django project
Type "python manage.py runserver" to run the project.

And Thats about all you would need to know to get you started.Cheers!!

### Technologies Used : 
1.Web Framework : Django<br>
2.Front-end : Bootstrap , jQuery








