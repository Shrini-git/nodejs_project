# Nodejs API project for InsuredMine
Sample api project in nodejs



1. Become a root user in EC2 server :
sudo su - root

2. Install GIT Client in EC2 server :
sudo yum install git -y

3. Download code from GIT repository to EC2 Server :
git clone https://github.com/Shrini-git/nodejs_project.git

4. Install NVM (node version manager) in EC2 server :
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

5. Add the following lines at the end of the bashrc file : 
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion


6. Install Node server and NPM in EC2 Instance :
nvm install --lts

7. Install the body-parser module :
npm install body-parser

8. Start node server to run node application :
node server.js


9. Now open following url in browser to hit api :
 http://<EC2 Server Hostname>:8080/hello

# Thank you
