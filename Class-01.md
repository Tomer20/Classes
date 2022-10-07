# Class 01

In this class we'll clone a git repo containing two python apps.

We'll review the applications, and will run them.

### Git

#### Install

Execute in the terminal:

```bash
$ brew install git
```

#### Configure

Once git cli is installed:

1. Create [GitHub](https://github.com/) account

2. [Create an SSH key pair](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

3. [Add SSH public key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

Then, go back to your terminal and configure your local git user:

```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

The username is what will be shown on commit messages on GitHub, so you'd want to match it to your GitHub user.

Same as for your email.

Now you're ready to clone repositories from GitHub :D

#### Git clone

Choose a folder where you will clone your git projects. Mine is `~/Projects` (where `~` stands for home folder).

To create this folder from terminal:

```bash
$ mkdir ~/Projects
```

Enter to the newly created folder:

```bash
$ cd ~/Projects
```

In here we will clone [devops-workshop](https://github.com/Tomer20/devops-workshop) repository:

```bash
$ git clone git@github.com:Tomer20/devops-workshop.git
```

Open your favorite IDE and create a new project on this path: `~/Projects/devops-workshop`

To continue, follow devops-workshop's README files:

- [Timer](https://github.com/Tomer20/devops-workshop/blob/master/timer/README.md)

- [Auth](https://github.com/Tomer20/devops-workshop/blob/master/auth/README.md)
