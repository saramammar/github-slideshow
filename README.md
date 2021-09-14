# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

-------------------------------

Clone this repository:
` git clone https://github.com/saramammar/github-slideshow.git `

Navigate to the repository in your shell:
` cd github-slideshow `

Create a branch, use whatever name you like. Feel free to use the suggested name below.
` git branch my-slide `

Or Create a new branch by issuing the command:
` git checkout -b new_branch `

Push the branch to GitHub:
` git push --set-upstream origin <BRANCH-NAME> `

Check out to your branch:
` git checkout my-slide `

Merge the main branch into the add-experience branch. To ensure that you're working with an up to date copy of main, we'll use its remote tracking branch:
` git merge origin/main `

Stage your new file:
` git add _posts/0000-01-02-saramammar.md `

After adding the text, commit the change while providing a commit message:
` git commit -m "<YOUR-MESSAGE>" `

Push your new commit to GitHub:
` git push `

Check out to the main branch:
` git checkout main `

Ensure the main branch is up to date:
` git pull `

If you want to undo the last git pull:
` git reset --hard master@{"10 minutes ago"} `

Merge your branch:
` git merge my-slide `

Push the merged history to GitHub:
` git push `

Delete your the branch locally:
` git branch -d my-slide `

-----------------------------------------

List all remote branches:
` git branch --all `

Switch to another branch (remote branch):
` git checkout -t origin/another-branch `

Set the cache for 1 hour:
` git config --global credential.helper "cache --timeout=86400" `
