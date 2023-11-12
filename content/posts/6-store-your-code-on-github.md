---
title: "6. Store your code on Github 📂"
date: 2021-06-02T04:09:43+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/5.-write-your-first-article/" 
    prev-text="5. Write Your First Article"
    next-href="/posts/7.-deploy-your-site-using-netlify/" 
    next-text="7. Deploy your site using Netlify"
    >}}

---

## Create a Github repository

In order for the code to be hosted on the web (using Netlify, which we will get into later), we will store the code for our website remotely on [Github](https://github.com/).

**1.** If you haven't already, make sure you have an account setup with [Github](https://github.com/).

**2.** On Github, create a new repository (A Github repository is a place where you can store your code for a project).

- Add a name for the repository. We are using *"hugo-site"*
- You can make your repository **public** or **private**
- Leave the other options as their defaults
- Click on **Create repository**

![Create Repo](/images/6/createRepo.png)

**3.** Open the Git Bash terminal, and navigate to the local folder in your computer where you are storing the files for your Hugo Website. Run the commands:

```markdown
git add .
git commit -m "first commit"
```

**4.** After that, run three more commands (which are found on the Github page after you have created the repository).

![Initialise Repo](/images/6/initRepo.png)

If completed successfully, you should be able to see your code stored in your Github repository when you refresh the page:

![Code Stored on Github](/images/6/storedCode.png)


{{< next-prev 
    prev-href="/posts/5.-write-your-first-article/" 
    prev-text="5. Write Your First Article"
    next-href="/posts/7.-deploy-your-site-using-netlify/" 
    next-text="7. Deploy your site using Netlify"
    >}}