---
layout: page
title: Get Started
---

## 1. Create a Github Account

Go to [github.com](https://github.com) and sign up for a free account.

## 2. Create a New Repository

There are two kinds of Github Pages sites: user and project. A user site is a
personal website that is associated with your Github account, while a project
site is associated with a specific repository. To create a new repository, click
the "+" icon in the top right corner of the Github homepage and select "New
repository". Give your repository a name and select "Public" for visibility. You
can also choose to initialize the repository with a README file. 

- If you name your repository `<username>.github.io`, it will be a user site.
- If you name your repository anything else, it will be a project site.

A user site has a URL like: 

    https://ericbusboom.github.io


A project site has a URL like:

    https://league-curriculum.github.io/Portfolio-jekyll-barebones/


## 3. Creating Your Website

For the next few steps, we will follow the [Github Pages Quickstart](https://docs.github.com/en/pages/quickstart) guide.

1. In the upper-right corner of any page on Github, select the new repository button,
   then click **New Repository**.

2. Enter `username.github.io` as the repository name. Replace `username` with
   your Github username. For example, if your username is `octocat`, the
   repository name should be `octocat.github.io`.

3. Choose a repository visibility. For more information, see [About Repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories#about-repository-visibility).

4. Select **Initialize This Repository With a README**.

5. Click **Create Repository**.

6. Under your repository name, click **Settings**. If you cannot see the "Settings" tab, select the **⋯** dropdown menu, then click **Settings**.

7. In the "Code and Automation" section of the sidebar, click **Pages**.

8. Under "Build and Deployment", under "Source", select **Deploy From a Branch**.

9. Under "Build and Deployment", under "Branch", use the branch dropdown menu and select a publishing source.

10. Optionally, open the `README.md` file of your repository. The `README.md` file is where you will write the content for your site. You can edit the file or keep the default content for now.

11. Visit `username.github.io` to view your new website. Note that it can take up to 10 minutes for changes to your site to publish after you push the changes to Github.

## 4. Yea! Check your New Site!

If you do no other configuration, you will see a simple page with the title of your
repository and a link to the README file. You can edit the README file to add


## 5. Changing the Title and Description

By default, the title of your site is `username.github.io`. You can change the
title by editing the `_config.yml` file in your repository. You can also add a
description for your site.

1. Click the **Code** tab of your repository.

2. In the file list, click `_config.yml` to open the file.

3. Click the ✏️ (edit) icon to edit the file.

4. The `_config.yml` file already contains a line that specifies the theme for
   your site. Add a new line with `title:` followed by the title you want. Add a
   new line with `description:` followed by the description you want. For
   example:

   ```yaml
   theme: jekyll-theme-minimal
   title: Octocat's Homepage
   description: Bookmark this to keep an eye on my project updates!
   ```

## 6. Local Editing

You can run Jekyll locally on your computer to preview changes before pushing them
to Github. To do this, you need to install Ruby and Jekyll on your computer. However, we have
a codespace that is installed with Jekyll and Ruby. You can use the codespace to preview your changes
before pushing them to Github. To do this, follow these steps:

1. Click the **Code** tab of your repository.
2. Click the **Code** button and select **Open with Codespaces**.
3. Click **New codespace**.
4. Wait for the codespace to load.
5. In the terminal, run the following command to start the Jekyll server:

   ```bash
   jekyll serve
   ```
6. Open the ports tab on the bottom pane, and look for the port that is running on `4000`. Click the **Open in Browser** button to view your site, to open a new browser tab, or select ** Preview** to open a preview pane in the codespace.
7. Make changes to your site in the codespace, and refresh the browser tab to see the changes.

## 7. Commit and Publish

Once you are happy with your changes, you can commit them to your repository.
Committing and pushing changes to your repository is the same as any other
Github repository, and for a Github pages site, it will automatically publish
the changes to your site.

