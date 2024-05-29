<!-- برای فعال کردن گیت هاب در محیط vscode این مراحل را انجام دهید: -->
- [ ] In this work we run a machine learning task to predict weight based on the height of a person from scratch

##for active push code in vs cod via terminal vscode follow these steps:

1. Check for existing keys-
```
a. ls -al ~/.ssh
```
3. Create a key if it does not exist-
Paste the text below and substitute it with your GitHub email address.
```
a. ssh-keygen -t ed25519 -C "your_email@example.com"
```
b. When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.
```
c. At the prompt, type a secure passphrase.
```

5. Adding your SSH key to the ssh-agent-
Fire up the SSH agent and add the key
```
1. eval `ssh-agent -s`
2. ssh-add ~/.ssh/id_ed25519

4. Adding key to GitHub account-
```
Pull up the key and add it to the GitHub account
```
1. cat ~/.ssh/id_ed25519.pub
2. Navigate to the GitHub account and add key
```
- [X] Hooray! now you should be able to push files to your GitHub account.


<!-- اگر خطای نبودن ریپازیتوری را داد از این دستور استفاده کنید: -->
- [X] if get this error:(you have not repository)  so you type this command in terminal:
```
git remote set-url origin https://github.com/<user_name>/<repo_name>.git
```
To publish a repository in PYPI, we must do the following steps: in the code folder of the requirements and readme file, setup.py and MANIFEST.in, then create a subfolder in this subfolder, two files named __init__.py and a file Python that contains the name of the package and has the same name as the last folder. In the test folder, which is under the folder of the second folder, there is a __init__.py file and a python file that must start with the name test.
First, in the action section, we run the Python package to create the first yaml file, and then Python publishes it to PyPI.
In the secret code section, we put the value of API-TOKEN-PYPI.
##In the lower part, you can see two images of the Python package before and after it was published in PYPI:

![1](https://github.com/mori-cyber/pythonpackge_morteza/assets/65276280/b0430046-78fb-4439-b9c2-1fab05e1338d)

And this is my package in PyPI:

![2](https://github.com/mori-cyber/pythonpackge_morteza/assets/65276280/2a325f31-af57-4672-8a79-25359482cf5f)




