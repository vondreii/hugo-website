---
title: "4. Add and Configure a Theme 🎨"
date: 2021-06-02T06:06:16+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/3.-create-a-new-hugo-project/" 
    prev-text="3. Create a new Hugo Project"
    next-href="/posts/5.-write-your-first-article/" 
    next-text="5. Write Your First Article"
    >}}
    
---
## Adding a Hugo Theme

There are so many [Hugo themes](https://themes.gohugo.io/) to choose from and they have slightly different ways to set it up depending on the one you pick. Most come with instructions on how to set them up, so be sure to check that they have setup instructions.

In this tutorial, we will use the [Mini theme](https://themes.gohugo.io/hugo-theme-cactus-plus/) for our Hugo site. 

**1.** To install the Mini theme into your Hugo project, enter the following commands in your Command Line / Terminal:

```bash
cd myWebsite
git init
git submodule add https://github.com/nodejh/hugo-theme-mini.git themes/mini
```

> **git init** - Initializes your myWebsite folder into a git repository. This means you will be able to store your code  on GitHub.

**2.** Open your `myWebsite` folder on your computer, navigate to `themes/mini/exampleSite`.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/4/miniThemes.gif?raw=true)

**3.** Copy the content, layouts, static and config.yaml files into your `myWebsite` folder.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/4/copyContentsLayoutsStaticConfig.gif?raw=true)


**4.** Copy the provided `netlify.toml` file and place it into your `myWebsite` folder.

{{< download >}}

**5.** Delete the `config.toml` file in your `myWebsite` folder because the `config.yaml` file should replace it.

**6.** Now, we need to make some adjustments to the `config.yaml` file for the theme to work. Open `config.yaml` using a text editor (such as Atom, Notepad++, or VS Code).

**7.** Delete lines 6 and 7 and change `theme: hugo-theme-mini` to `theme: mini`.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/4/configYaml.gif?raw=true)

**8.** Save the file.

**9.** Finally run `hugo serve` on your Command Line or terminal. 

**10.** Then on your favorite browser, go to [http://localhost:1313/](http://localhost:1313/). You should see the theme is installed and already has content!

{{< next-prev 
    prev-href="/posts/3.-create-a-new-hugo-project/" 
    prev-text="3. Create a new Hugo Project"
    next-href="/posts/5.-write-your-first-article/" 
    next-text="5. Write Your First Article"
    >}}