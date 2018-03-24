
# Github Pages

To use github pages, you have to create a special repository.

# Create a repository

Log into github and create a repository for github.io prefixed
with your username.

    username.github.io

Replace username with your username in github.

# Create ssh key files

If you do not have a SSH key in github, create a key and install
it into github.

    ssh-keygen -t rsa -b 4096 -C "user@example.com"

Replace *user@example.com* with your email adress.

Copy the contents of the file ~/.ssh_id_rsa.pub to your SSH keys
in github account settings.

For details, see (https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)[github account]

# Test the key

ssh -T git@github.com

# Clone the repository

git clone git@github.com:username/username.github.io

# Add some files

...

# Use ssh agent

Use *ssh-agent* to keep your SSH credentials in memory.
This makes pushing your changes easier.

(https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)[ssh agent]


# Verify your page

Open a browser and visit https://yourname.github.io

# Sum up

It is easy to setup up github account, create an SSH key and
repository and add some files. You can write github pages in
HTML or Markdown language. Access to your github pages is
redirected to https by default.


