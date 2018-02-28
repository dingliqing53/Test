# bi-analytics
This repository houses business intelligence and analytics scripts to support the Autolist business team.

Want to use git?

Here's how:

1) Set up your SSH Key: `https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/`

2) Navigate to the local folder you'd like your repository to live. `cd path/to/folder`

3) Enter the following command in your command line:`git clone [Repo SSH link here]`

You should now see the repository folder (bi-analytics) in the directory you cloned the repo in.

Before working, make sure to checkout and pull master so you have the most up-to-date code:

`git checkout master`

`git pull`

To perform code adjustments, create a branch using the following:
`git checkout -b feature-name-here`

-b is a command to create a branch but you can also checkout an existing branch and remove -b from the command above.

*NEVER* upload code that contains credentials

`git add *`

`git commit`

Enter in a commit message, hit Esc and then type `:wq`

`git push`

(You will get an error. Copy and paste the provided command to continue)

Come back to github and you should now see your new/edited branch in the repository! Next step is to open a pull request, get the code reviewed and merge to Master.

Upon merging into master, make sure to delete the branch you were working in since it is now obsolete.

Congratulations!
