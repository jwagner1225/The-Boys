# The-Boys
## Installation 
The best way to install and use the contents of this repository would be through JupyterLab. In JupyterLab clone the `The-Boys` repository using the `git clone https://github.com/jwagner1225/The-Boys.git` command. This will add a folder titled `The-Boys` in your JupyterLab directory with the contents of the repository. To run the code, select and open `randomCode.ipynb`. This file contains the repository’s python code in a JupyterLab code cell. The code can be run from this cell by pressing `CNTRL + ENTER` on windows or `CMND + ENTER` on Mac. 
## Usage 
`randomCode.ipynb` is a very simple program which will prompt the user for two inputs: their name and their age. These inputs are stored in strings and used later in the code.\
When prompted with the following, type in your name and press ENTER:\
`What is your name: `\
When prompted with the following, type in your age and press ENTER:\
 `What is your age: `\
And that’s it! You will then be greeted with a personalized message created using the following code:
```python
print("Your name is " + name + " and you are " + age + " years old.")
```
## Development
### Contributing
To contribute to the repository users should branch the repository and from there add any desired changes. Once you branch `The-Boys` you can clone the repository into JupyterLab using the following command: `git clone https://github.com/[YOUR-USERNAME]/The-Boys.git`. This will add a new folder titled `The-Boys` in your JupyterLab directory. Within JupyterLab you can add files or edit existing ones. After finalizing your desired changes, you must commit changes to your branched repository back in GitHub. Use the following commands:\
`git add .`\
`git commit -m [YOUR COMMIT MESSAGE]`\
`git push`
You will then be prompted to enter your GitHub username and access token to commit the changes to your repository. Afterward, your branched repository should include the changes you made. To contribute to the original repository, create a pull request comparing changes across forks on GitHub. It is important to note however that user’s pull requests may not always be accepted. 
### Licensing
The contents of this repository are unlicensed and can all be freely accessed through the public domain. 
### Team
Jack Wagner (owner)\
Paolo Hidalgo (contributor)\
Nij Patel (contributor)