---
title: "2. Install Hugo (Windows) ⬇"
date: 2021-06-02T09:03:52+10:00
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

> **To install Hugo on Windows, you will need to first install a Package Manager.**

## Install a Package Manager (if you don't have one already)

Before we can install Hugo, we need to install a Package Manager. The package Manager we will use is called [Scoop](https://scoop.sh/).

> [Scoop](https://scoop.sh/) is a package manager that allow you to download and install certain programs or tools easily using commands in the command line or PowerShell. 

Installing Scoop has similar steps to using Homebrew on a Mac or Linux system.

**1.** Search for Windows Powershell, right click, 'Run as Admin'

**2.** Copy paste the following command and press `enter`

```bash
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

**3.** If the above script is not allowed to be executed, try running this first:

```bash
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```

If successful, you will be able to type `scoop help` and other scoop commands.

{{< centered-img src="/images/2/scoop.png" title="homebrew" alt="homebrew">}}

## Install Hugo

**1.** We can now install Hugo. Run the following command in Powershell:

```bash
scoop install hugo
```

**2.** Now within PowerShell (or go to Command Line), you can enter one of the commands below to confirm that hugo is now on your machine:

```bash
hugo version
```

This will tell you the version of Hugo that was installed.

```bash
hugo help
```

This will print a bunch of flags and commands that can be used.

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
    