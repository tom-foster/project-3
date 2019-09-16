# project-3

## Get started

Project 3 is using WSL and Ubuntu from the web app store.

Firstly go to ~/.bashrc and change the shorthand so it's consistent with installs over how you call python and pip.
You'll also need to install pip for the Ubuntu windows app too.

```bash
code ~/.bashrc
# Once editor loads add to the bottom of the file
alias python=python3
alias pip=pip3
```

Once done exit the editor and refresh so the commands come in to play.
```bash
source ~/.bashrc
```

Need to navigate to the mounted drive where I keep project on the HDD. You have to navigate to the mounted drive for this.

/mnt/d/Users/Tom/Documents/website_projects/python_projects/project-3

Install the virtual environment as per usual. However it will now activate and set up with actual Ubuntu files.

```bash
source venv/bin/activate
```