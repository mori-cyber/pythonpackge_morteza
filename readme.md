<!-- برای فعال کردن گیت هاب در محیط vscode این مراحل را انجام دهید: -->
- [ ] in this work we run a machine learning task for predict weight based on height a person from scratch

##for active push code in vscod via terminal vscode follow these steps:

1. Check for existing keys-
a. ls -al ~/.ssh

2. Create key if does not exist-
Paste the text below, substituting in your GitHub email address.
a. ssh-keygen -t ed25519 -C "your_email@example.com"
b. When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.
c. At the prompt, type a secure passphrase.

3. Adding your SSH key to the ssh-agent-
Fire up the SSH agent and add the key
1. eval `ssh-agent -s`
2. ssh-add ~/.ssh/id_ed25519

4. Adding key to Github account-
Pull up the key and add to Github account
1. cat ~/.ssh/id_ed25519.pub
2. Navigate to Github account and add key

Hooray! now you should be able to push files to Github account.


<!-- اگر خطای نبودن ریپازیتوری را داد از این دستور استفاده کنید: -->
if get this error:(you have not repository)  so you type this command in terminal:
git remote set-url origin https://github.com/<user_name>/<repo_name>.git

