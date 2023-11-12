---
title: "8. Making Changes To Your Website 🎲"
date: 2021-06-02T03:21:18+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/7.-deploy-your-site-using-netlify/" 
    prev-text="7. Deploy your site using Netlify"
    next-href="/posts/1.-start-here" 
    next-text="1. Start Over"
    >}}

{{< next href="/" text="Back Home">}}

---

Now that your site is live on Netlify, every time you make a changes to the content on your computer - your live site won't reflect these changes right away.

But because your hugo site is on a Git respository connected to Netlify, we can use `git` commands to tell Netlify to deploy these new changes. 

For changes to show, you will need to:

1. **add** all your new changes

    ```bash
    git add .
    ```

2. **commit** your changes, and finally
   
    ```bash
    git commit -m "Updated article about potatoes"
    ```
    > (assuming you updated your article on potatoes)

3. **push** them

    ```bash
    git push
    ```

{{< next-prev 
    prev-href="/posts/7.-deploy-your-site-using-netlify/" 
    prev-text="7. Deploy your site using Netlify"
    next-href="/posts/1.-start-here" 
    next-text="1. Start Over"
    >}}

{{< next href="/" text="Back Home">}}
