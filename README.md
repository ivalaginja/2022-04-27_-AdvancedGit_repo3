# Advanced Git for Astronomers part 3: working with several branches

Welcome to **workflow 3** of the "Advanced Git for Astronomers" tutorial!

With this repository, we  will be learning how to manage several active branches at a time on a repository. We will 
see how merge conflicts arise, how to solve them, and how to work in a way that tries to avoid them in the first place, 
as best as possible.

We will also work through an example that shows how to provide a "conda recipe" for a Python installation that 
is needed to run the code on your repository.

For further info, please contact:
iva.laginja@obspm.fr

If you want to sign up for announcements about further installments of our git courses, feel free to sign up for notifications here (Google form):
https://forms.gle/CkofT5ASMpfYCYN17


## Requirements for workflow 2 of Advanced Git for Astronomers:

1. Create a GitHub account:
  - go to https://github.com/
  - click on the link to "Sign up"
  - provide a username, email address and password and create your account
  - validate the confirmation email
  
2. Install GitKraken:
  - go to https://www.gitkraken.com/download
  - download the appropriate installer for your operating system
  - run the installation
  - when you open the app for the first time it will prompt you to sign in - use your GitHub account for this, and 
  the email you used to create your GitHub account
  
3. Install conda:
  - On **Windows**:
    1. Go to the Miniconda website and install miniconda for Python 3.7 for your respective OS: https://docs.conda.io/en/latest/miniconda.html
    2. Make sure to add Miniconda to your PATH during the installation, even if it is marked as not recommended. This is required so that Git Bash can recognise it (see next point).
    3. Install Git Bash from here: https://gitforwindows.org/
    
  - On **MacOS**/**Linux**:
    1. Go to the Miniconda website and install miniconda for Python 3.7 for your respective OS: https://docs.conda.io/en/latest/miniconda.html