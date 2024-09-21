**Cloning a repo:**

In Github, navigate to directory, click **code**, copy the https url.

Open terminal. Change the working directory to the one where you want the code

Type **git clone**, paste the copied url.

Press **enter** to create the clone.

Cd to the cloned repo. Type **git init .**

(git status often to check)

Create a markdown file in the cloned repo on the desktop.

Open the repo in VSCode, do some work for testing purposes.

Back in terminal, **git add .**

Type **git commit -m “message”**

Type **git push -u origin main** as per usual. Seems to work.

---

**Caching credentials.**

This is when you want to set up a computer for frequent git/github interaction.

Install **Git Credential Manager**.

Navigate to Github docs/get started/caching credentials.
Click on the **instructions in the GCM repo**

We’ll try debian, but I’m going to do that on the downstairs laptop after I have cloned this repo

Just testing this

Just forget about all of this.

So, to login you will need a personal access token, which we know how to generate. The important thing is to set the computer up for a connection with Github.

First up, enter **git config --global credential.helper store**

This will store your login info so you never have to enter it again. I did it while in the actual local repo, but not sure if this matters. (it didn't, because I initially entered this command while in the root folder)

So when you push to the upstream repo you should never need to login again. Worked a couple of times already so see how we go.
You will only have to enter your username and PAC once.
