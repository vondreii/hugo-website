---
title: "7. Deploy your site using Netlify 🚀"
date: 2021-06-02T03:21:18+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/6.-store-your-code-on-github/" 
    prev-text="6. Store your code on Github"
    next-href="/posts/8.-making-changes-to-your-website/" 
    next-text="8. Making Changes To Your Website"
    >}}

---
## Deploy your site using Netlify

[Netlify](https://www.netlify.com/) is a web-hosting service that can host your website for free. We will be using the GitHub repository we created for our Hugo blog with Netlify.

**1.** If you don't have an account already, create a new account and sign up to [Netlify](https://app.netlify.com/). You should have the option to sign in/sign up using a Github account, so choose that option:

  ![/images/7/netlify-0.png](/images/7/netlify-0.png)

**2.** Enter your Github credentials:

  ![/images/7/netlify-1.png](/images/7/netlify-1.png)

**3.** Click on 'New Site from Git'

  ![/images/7/netlify-2.png](/images/7/netlify-2.png)

**4.** Click on 'Github'

  ![/images/7/netlify-3.png](/images/7/netlify-3.png)

  You may be asked to grant permissions to Netlify. If this happens, select **'Authorize Netlify'.**

**5.** You may then be asked to install Netlify. 
Here, you are not installing anything on your local computer. You are actually just connecting your Netlify account to a chosen Github repository:

  ![/images/7/netlify-4.png](/images/7/netlify-4.png)

  You can either choose:

  - **All repositories:** Netlify will have access to all repositories that you will have on your account.
  - **Select repositories:** You are only giving Netlify permission to certain repositories of your choice.

  In this case, it does not really matter which option you choose as the end result will be the same.

**6.** Select **'Install'**.

  Now select the repository that you want to host (in this case, the repository where your Hugo code is stored).

  ![/images/7/netlify-5.png](/images/7/netlify-5.png)

**7.** When you get to this page, leave the **Site settings** as the default. For the **Basic Build Settings**, use the same settings as shown in the image:

  ![/images/7/netlify-6.png](/images/7/netlify-6.png)

**8.** After the setting up process is complete, you will now be taken to a page where you will be able to manage the deployment of your site. 
  - Netlify automatically re-deploys your site everytime you make a commit and push it to your Github repository.
  - If the latest deploy attempt was successful, your site will be made live on the web at a randomly generated domain name. You can visit your live website on the randomly generated `<some-random-name>.netlify.app` link.

  ![/images/7/netlify-7.png](/images/7/netlify-7.png)

**9.** If you wish, you can change the randomly generated domain name to something less random, by going into **Domain settings**.

  ![/images/7/netlify-8.png](/images/7/netlify-8.png)

  Here, you can either:

  - Add a custom domain name, that can end with *`.com`*, *`.gov`*, or more.
      - These are custom names that you buy on your own which you can use in Netlify. These will not have the *`.netlify.app`* at the end.
  - Or, you can edit the randomly generated one to something that sounds nicer.
      - This is a free domain name and will have the *`.netlify.app`* at the end.

      ![/images/7/netlify-9.png](/images/7/netlify-9.png)

**10.** Because we are setting up a website for free, we will just edit our domain name and keep the *`.netlify.app`* at the end.

  ![/images/7/netlify-10.png](/images/7/netlify-10.png)

**11.** After you save the new site name, we can go to [https://blast-furnace-hugo-example.netlify.app/](https://blast-furnace-hugo-example.netlify.app/) and see our website live!

  > **NOTE:** You will need to give your hugo site a different name, since this tutorial already uses `blast-furnace-hugo-site`.

{{< next-prev 
    prev-href="/posts/6.-store-your-code-on-github/" 
    prev-text="6. Store your code on Github"
    next-href="/posts/8.-making-changes-to-your-website/" 
    next-text="8. Making Changes To Your Website"
    >}}