#industry level git commands

part 1:git configuration commands

1.git config --global
command name:git config --global user.name
syntax:git config --global user.name "your name"
purpose:sets your username for git.every commit will show this name.

2.git config --global user.email
syntax:git config --global user.email "your email"
purpose:sets your email for commits.

3.git config --list:
purpose:shows all list git configuration settings.

4.git config --unset
purpose:removes a configuration value.
ex:git config --unset user.name

screenshot:![alt text](git_config.png)

--part 2:repository setup commands:
1.git init:
command name:git init
syntax:git init
purpose:creates a new git repository in your project folder.
it creates a hidden  .git folder .
 screenshot:![alt text](image.png)

 2.git clone
 syntax:git clone <repository-url>
 purpose:copies a repository from github to your computer.
 example:git clone https://github.com/username/project.git
 
screenshot:![alt text](image-1.png)

3.git clone --branch branch-name repository -url
purpose:clones only a specific branch

