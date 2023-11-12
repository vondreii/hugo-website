---
title: "5. Write Your First Article 📇"
date: 2021-06-02T05:08:38+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/4.-add-and-configure-a-theme" 
    prev-text="4. Add and Configure a Theme"
    next-href="/posts/6.-store-your-code-on-github/" 
    next-text="6. Store your code on Github"
    >}}

---
## Website Pages and Content

Congratulations! Your website is actually ready to be publicly available on the Internet. But, we haven't shown you how to create your own articles/blog posts.

Earlier, when we copy-pasted the **content, layouts, static** folders and **config.yaml** file into our `myWebsite` folder, we were taking all the demo site's content, which can be found [here](https://themes.gohugo.io/theme/hugo-theme-cactus-plus/). So, they're not really our own content.

So the pages you see at [http://localhost:1313/](http://localhost:1313/) are just placeholders. We now want to change it so that we have our own content on our pages. 

**1.** Let's open our `myWebsite` Hugo project folder on a VSCode. 

**2.** If we expand the `content/posts` folder, we will see some `.md` (Markdown) files.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/5/posts.gif?raw=true)

The way Hugo works is that each `.md` file in the folder `contents/posts` (as seen in the gif) represents a page on the actual website.

So if you want to add a new page to your website, just add a new `.md` file, and write some content in it. You do not need to write any other code, since Hugo will do the rest.

## Adding a new page

**1.** To add a new page to your website, you can either create a new `.md` file manually under the  `contents/posts` folder, or you can run this command in your terminal or command line:

```bash
hugo new posts/my-first-article.md
```

**2.** If you go back into the `content/posts` folder, you will see a new file, called `my-first-article.md`. This is a new page you have just created on your website.

> If you used the command above to generate the file, you will see that the file was generated already with some meta data (the title, date, and draft). The title can be changed and will not affect the link. If you created the file manually, you will have to type these in yourself.

![image info](/images/5/addingANewPage.png)

> When you create the page with `my-first-article.md`, `my-first-article` will be the link of the page in the browser `http://localhost:1313/posts/my-first-article`. 

**3.** Open up the `my-first-article.md` file on your text editor and change `draft: true` to `draft: false` and save it.

- When `draft` is set to `true`, the page will NOT show on your website, since it's still a draft.
- When the `draft` is set to `false`, that means that the page will be published and you and other people will be able to open and read it.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/5/draft.gif?raw=true)

Re-visit [http://localhost:1313/](http://localhost:1313/) in your browser. You should be able to see your new page.

## Adding Content to a Page

We can start writing in some content in the new page we have just created.

- Feel free to write anything if you're already familiar with Markdown.
- If you're curious, check out the Markdown Syntax Guide [here](https://tutorial-blog.netlify.app/posts/markdown-syntax-guide/) **OR**
- If you're in a hurry, we have also prepared some dummy content for you to fill in so that your article is ready to go.

```markdown
---
title: "All About Potatoes"
date: 2021-06-02T19:02:09+10:00
draft: false
---

# **All About Potatoes**

Potatoes were introduced to Europe in the 16th Century by the Spanish. Today, they are now popular in many parts of the world and are included in many dishes such as Roast Chicken and Potato Bake. The world’s largest potato producing country is China, and today, there are now 5,000 different types of potatoes. 

### **Potato Plants**

Potato plants can grow up to 60cm high, depending on the variety. 

### **Potato Facts**
- Potatoes are a vegetable.
- Potatoes are actually 80% water and 20% solid. 
- Potatoes are sometimes used to make alcoholic beverages.
- Idaho is known as the 'Potato State' as they grow many potatoes and have their own potato museum.

### **Potato Quotes**
- Everything in this world is either a potato or not a potato.

### **Resources**
- You can read more about potatoes [here](https://en.wikipedia.org/wiki/Potato). 

![image info](/images/Potatoes.png)
```

To get images to work, add a new `images` folder under the `static` folder (in your website's directory). Inside the `images` folder you have just created, add a photo called `Potatoes` (make sure the photo matches the extension, in this case, a `png` image).

To view your new page, re-visit [http://localhost:1313/](http://localhost:1313/).

{{< next-prev 
    prev-href="/posts/4.-add-and-configure-a-theme" 
    prev-text="4. Add and Configure a Theme"
    next-href="/posts/6.-store-your-code-on-github/" 
    next-text="6. Store your code on Github"
    >}}