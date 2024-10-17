# Node-ec2-bootstrap


Simple node.js app that servers "A Monk in Cloud"

Great for testing simple deployments on Cloud

## Step 1: Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
Activate nvm by typing the following at the command line.

```bash
. ~/.nvm/nvm.sh
```

Use nvm to install the latest version of Node.js by typing the following at the command line.

```bash
nvm install node
```

Test that node and npm are installed and running correctly by typing the following at the terminal:

```bash
node -v
npm -v
```

## Step 2: Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

```bash
sudo apt-get update -y
sudo apt-get install git -y
```

Just to verify if system has git installed or not, please run below command in terminal:
```bash
git — version
```

This command will print the git version in the terminal.

How to generate and set up SSH keys:

1. Generate a new SSH key pair:

```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
2. When prompted, you can press Enter to accept the default file location:

```
Enter file in which to save the key (/home/YOU/.ssh/id_ed25519):
```


3. Enter a secure passphrase (optional but recommended):

```

Enter passphrase (empty for no passphrase):
Enter same passphrase again:

```
