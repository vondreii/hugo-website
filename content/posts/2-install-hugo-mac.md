---
title: "2. Install Hugo (Mac) ⬇"
date: 2021-06-02T08:08:43+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/1.-start-here" 
    prev-text="1. Start Here"
    next-href="/posts/3.-create-a-new-hugo-project/" 
    next-text="3. Create a new Hugo Project"
    >}}
<!-- {{< prev 
    href="/posts/1.-start-here" 
    text="1. Start Here"
    >}} -->

---

> **To install Git on your Mac, you will need to first install Homebrew!**

## Install a Package Manager (if you don't have one already)

We will use [Homebrew](https://brew.sh/), a Package Manager, to assist in downloading Git and Hugo on our system.

{{< centered-img src="/images/2/homebrew.png" title="homebrew" alt="homebrew">}}

**1.** Open up the macOS Terminal or Linux shell prompt

**2.** Then, copy-paste the following command and press `enter`
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

**3.** The script will run and may request your device's login password
- Type your password even though you don't see anything being typed onto the Terminal/Shell, then press `enter`
  
**4.** You will get a "Installation successful!" message once Homebrew has completed and successfully been installed.

> 💡 ***[Homebrew](https://brew.sh/)*** is a Package Manager. Package managers allow you to download and install certain programs or tools easily using commands in a MacOS Terminal or Linux Prompt Shell. For example, NuGet is for downloading packages/libraries easily into VS. This is a similar concept where you can download some programs/tools using the command line.

### Install Git

You can confirm you have Git installed by entering the `git` command and seeing Git commands printed out.

If not, enter `brew install git` within the Terminal or Shell Prompt.

## Install Hugo

We can now install Hugo by entering `brew install hugo` on our Terminal or Shell Prompt

Enter `hugo help` to confirm Hugo is installed. You will get a bunch of Hugo flags and commands printed out.

{{< next-prev 
    prev-href="/posts/1.-start-here" 
    prev-text="1. Start Here"
    next-href="/posts/3.-create-a-new-hugo-project/" 
    next-text="3. Create a new Hugo Project"
    >}}
<!-- {{< prev 
    href="/posts/1.-start-here" 
    text="1. Start Here"
    >}} -->
