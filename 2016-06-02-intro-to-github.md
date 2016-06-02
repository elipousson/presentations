
# bLAM Class
## Introduction to GitHub
[Eli Pousson](https://elipousson.github.io), [Baltimore Heritage](http://baltimoreheritage.org/) | 2016 June 2

[@blamcollective](https://twitter.com/blamcollective) | [bLAM Collective](https://blamcollective.wordpress.com)

---

## Welcome!

By the **end of this lesson**, you will:

- Learn about **git** and **GitHub**
- Create a **repository**
- Make a **commit** to a repository on GitHub
- Learn to format text with **Markdown**
- Learn how to make a site with **GitHub Pages**

--

## What do you need for this workshop?

- A computer (Mac/Windows)
- The ability to download and install software on the computer
- An internet connection that can support downloading software

--

## How difficult is this workshop?
Beginner friendly!

--

[![Join GitHub](/presentations/images/2016-06-01-join-github.png)](https://github.com/join)

Make sure to [join GitHub](https://github.com/join) before we get started.

---

![git logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

## What is git?
**Git** is a version control tool. Git lives locally on your computer and you access it through the command line. Git is the **local** power behind _version control_.

Note: Excerpt from [CUNY workshop materials](https://github.com/mckinniburgh/gitWorkshop/blob/master/2_conceptOverview.md). Library Carpentry: "Git is a 'free and open source distributed version control system'. We probably know what free and open source means but we might be less sure about what a 'distributed version control system is'. One way to understand what Git and version control systems do is to look at the types of problems they are built to address."

---

## What is version control?

It’s why we use “Save As”.

Note: [Library Carpentry](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md): "Many of us will have had an experience similar to this. We are working on an important piece of work and we attempt to maintain multiple version of this document in different stages of completeness.Version control addresses this problem by recording the changes we make to a document as we proceed. Each of the 'commits' we make is recorded and we can go back across a document or a set of documents and look at what changes have been made. Version control allow us to take this one step further and not only record changes to a document one person is working on but allows multiple people to work on a document and record the changes they make. It is then possible to merge these multiple documents. This developed out of a need for groups writing code together to be able to work on coding projects together without having to wait for someone else to finish working on something or having to manually compare changes that are made."

---

[![PhD Comics - "Final".doc](/presentations/images/phd101212s.gif)](http://www.phdcomics.com/comics/archive.php?comicid=1531)

---

![GitHub logo](https://assets-cdn.github.com/images/modules/logos_page/GitHub-Logo.png)

## What is GitHub?
**GitHub** is a hosting service for git repositories. You can use GitHub using your browser, desktop applications, or the command line. GitHub connects Git repositories **remotely** and is the power behind _collaboration_.

Note: From the [CUNY workshop materials](https://github.com/mckinniburgh/gitWorkshop/blob/master/2_conceptOverview.md): Once your local **git** repository and **Github** are connected, you can make copies of other users' repositories, edit them, and send your proposed changes back to the user who can then choose to incorporate your work into their repository.  [Library Carpentry](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md): "We often hear the terms Git and Github used interchangeably but the are slightly different things. Git refers to the software and principles used for a particular flavour of version control (there are other systems like mercurial and SVN). Github is a popular site which hosts git repositories. The majority of the content that Github hosts is open source software though increasingly it is being used for other projects such as open access journals and constantly updated text books. Github is a great place to learn how to use Git but once you have learned the ideas and processes behind github you can used Git on other storage systems or host repositories on your own server if you wanted to keep code private or you wanted to encrypt your repository."

---

## Why use GitHub?
Here are three reasons that people and organizations are using GitHub.

- To use version control
- To share open-source projects
- To facilitate collaboration
- To keep a record of changes

Note: **Ask participants**: why are you here? Why do you want to use GitHub?

---

## How are GLAMs using GitHub?

- Code
- Data
- Maps
- Writing
- Websites

You can _star_ any repository to save it to [your account](https://github.com/stars). Give it a try!

--

[![Zotero website](/presentations/images/2016-06-01-zotero.png)](https://github.com/zotero/zotero)

--

### Code
Open source software projects developed for and by GLAMs host code on GitHub. Examples include [Zotero](https://github.com/zotero/zotero), [Omeka](https://github.com/omeka/Omeka), [CollectiveAccess](https://github.com/collectiveaccess) and [CollectionSpace](https://github.com/collectionspace).

--

[![Cooper-Hewitt collection repository](/presentations/images/2016-06-01-cooperhewitt-collection.png)](https://github.com/cooperhewitt/collection)

--

### Data
In 2012, the Smithsonian Cooper-Hewitt National Design Museum in New York [published their collection metadata](http://labs.cooperhewitt.org/2012/releasing-collection-github/) to [GitHub](https://github.com/cooperhewitt/collection) using a Creative Commons Zero license. The [Tate Gallery](https://github.com/tategallery/collection) and [Museum of Modern Art](https://github.com/MuseumofModernArt/collection) released their metadata soon after.

--

[![New York Public Library Negro Motorist Green Book Web Map ](/presentations/images/2016-06-01-nypl-greenbook-map.png)](http://publicdomain.nypl.org/greenbook-map/)

--

### Maps
In 2015, the New York Public Library published a [location dataset](https://github.com/NYPL-publicdomain/greenbooks) scraped from the digitized Negro Motorist Green Book travel guides. In 2016, the New York Public Library created [a website](http://publicdomain.nypl.org/greenbook-map/) to display the data (hosted [on GitHub](https://github.com/NYPL-publicdomain/greenbook-map) and published with a Creative Commons Zero License).

--

[![Andy Warhol Museum Digital Strategy ](/presentations/images/2016-06-01-warholmuseum-digitalstrategy.png)](https://thewarholmuseum.github.io/digital-strategy/)

--

### Writing
In 2015, the Andy Warhol Museum drafted and published their [digital strategy documents on GitHub](https://thewarholmuseum.github.io/digital-strategy/) using a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://thewarholmuseum.github.io/digital-strategy/LICENSE.txt) license.

--

[![ACMI Labs static museum audio guide](/presentations/images/2016-06-01-static-museum-audio-guide.png)](https://github.com/ACMILabs/static-museum-audio-guide

--

### Websites
Last week, the Australian Center for the Moving Image created [a Jekyll website template](https://github.com/ACMILabs/static-museum-audio-guide) to create a museum audio guide published a MIT license.

Note: In 2016, the City of Los Angeles Department of Cultural Affairs published their [WordPress child theme on GitHub](https://github.com/dcadigital/cultural-affairs-wp-theme).

--

![Explore GitHub](/presentations/images/2016-06-01-explore-github.png)

---

## Open Licensing
You may have noticed that many of these projects use Creative Commons or other **open licenses**.

--

### What is an open license?
A license is a document that specifies what can and cannot be done with a work (whether sound, text, image or multimedia). It grants permissions and states restrictions. Broadly speaking, an open license is one which grants permission to access, re-use and redistribute a work with few or no restrictions.

Note: Following definitions are from the [Guide to Open Licensing – Open Definition](http://opendefinition.org/guide/)

--

### Why use an open license?
Works that are published without an explicit license are usually subject to the copyright laws of the jurisdiction they are published in by default. Open licenses enable creators to allow more freedom in what others can do with their works.

--

[![choosealicense.com](/presentations/images/2016-06-01-choosealicense.png)](http://choosealicense.com/)

You can use [Choose a License](http://choosealicense.com/) to learn more about different open source licenses or take self-guided lessons on "openness" from the [School of Open](http://schoolofopen.org/).

---

## How is GitHub organized?

- Users
- Organizations
- Repositories

--

[![GitHub user page for elipousson](/presentations/images/2016-06-01-elipousson-github.png)](https://github.com/elipousson)

### Users

--

[![GitHub organization page for baltimoreheritage](/presentations/images/2016-06-01-baltimoreheritage-github.png)](https://github.com/baltimoreheritage)

### Organizations

--

[![GitHub repostitory page for bLAM Class](/presentations/images/2016-06-01-blamclass-github.png)](https://github.com/blamcollective/blamclass)

### Repositories

---

## Creating a repository with git on the command line

We are now going to create a repository using [tryGit](https://try.github.io/levels/1/challenges/1) from [Code School](https://www.codeschool.com/courses/try-git). Other interactive tutorials to learn git on the command line include:

- [Learn Git](https://www.codecademy.com/learn/learn-git) from Codecademy
- [Git It](https://github.com/jlord/git-it-electron) application

Note:  [Library Carpentry](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md): A repository is the place where are projects and associated changes are stored. Repositories can contain one single readme file or hundreds of different folders making up the source code for extensive projects. We can create repositories in a number of different ways; we can make our own from scratch, we can fork (copy) an existing repository or we can create a git repository from an existing folder we have been working on.

--

[![tryGit from Code School](/presentations/images/2016-06-01-trygit.png)](https://try.github.io/levels/1/challenges/1)

---

## What do you find on a repository page?

- Name
- Description
- Code
- Branches
- Commits
- Pull Requests
- Issues
- Wikis

Read the [18F Open Source Style Guide](https://pages.18f.gov/open-source-guide/) to learn more about writing short and clear repo descriptions, readable READMEs, and clear and concise issues.

---

## What files you find in a repository?

- README.md
- CONTRIBUTING.md
- LICENSE
- .gitignore

---

## Creating a repository using the browser

Create a [new repository](https://github.com/new).

--

[![Create a new repository](/presentations/images/2016-06-02-github-new.png)](https://github.com/new)

--

## Creating a repository using the browser

- Name the "repo (your-username).github.io"
- Add a short description, e.g. "My website."
- Check the box labeled "Initialize this repository with a README"
- Select Jekyll for .gitignore
- Select Creative Commons Zero for license

---

## What is Markdown?

You may notice that the README.md and CONTRIBUTING.md are written using a plain text markup known as **Markdown**.

Note: From [Markdown Tutorial](http://www.markdowntutorial.com/): Markdown is a way to write content for the web. It’s written in what nerds like to call “plaintext,” which is exactly the sort of text you’re used to writing and seeing. Plaintext is just the regular alphabet, with a few familiar symbols, like asterisks ( \* ) and backticks ( \` ). Unlike cumbersome word processing applications, text written in Markdown can be easily shared between computers, mobile phones, and people. It’s quickly becoming the writing standard for academics, scientists, writers, and many more. Websites like GitHub and reddit use Markdown to style their comments. If you have ten minutes, you can learn Markdown!

--

[![Markdown Tutorial](/presentations/images/2016-06-01-markdown-tutorial.png)](http://markdown-tutorial.com/)

Note: This section is via the CUNY tutorial. Markdown is a markup (I know!) style that allows you to annotate text for formatting in a quick and lightweight manner. GitHub supports markdown, which renders more attractive files. Markdown is also thought to be more sustainable over time, since it is a plain text file. You'll notice this file is in markdown--check out its extension! For a cheat-sheet to get you started, read here: [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). I used this cheatsheet for reference in creating this repo.

--

## Learn more about Markdown

- [Getting Started with Markdown](http://programminghistorian.org/lessons/getting-started-with-markdown), Programming Historian
- [Mastering Markdown from GitHub](https://guides.github.com/features/mastering-markdown/)
- [Dennis Tenen and Grant Wythoff, "Sustainable Authorship in Plain Text Using Pandoc and Markdown."](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

---

## Using GitHub Pages

- You can upload files, fork an existing repository, or use the [automatic page generator]( https://help.github.com/articles/creating-pages-with-the-automatic-generator/)
- To upload files or use the automatic page generator, create a new repository named your-username.github.io, where username is your username (or organization name) on GitHub.
- Here is a simple theme we can use to build a site [Minimal: A Theme for GitHub Pages](https://github.com/orderedlist/minimal)

Note: [Library Carpentry](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md): Github pages allow you to version control your website. This is useful for a lot different reasons. It allows you to keep a record of what changes you have made. It allows people to reference your website at a particular point in time and (if you make you're source open) to see what it was like at that particular point in time. This is very useful for academic citations. Most people have had the experience of following up a reference to a website and either getting a 404 error or seeing something completely different. Although using version on your site doesn't guarantee this won't happen it does make it easier to manage old versions of your site.

---

## Tools to try with GitHub

You can use free web applications and services to create or edit files hosted on GitHub.

--

### prose.io

![prose.io](/presentations/images/2016-06-01-prose-io.png)

[prose.io](https://prose.io) (works well with this [Chrome extension](https://chrome.google.com/webstore/detail/prose/onippmookoohgjgccejcjmlpoohbjgjn))

--

### geojson.io

[geojson.io](http://geojson.io/) (works well with this [Chrome extension](https://chrome.google.com/webstore/detail/geojsonio/oibjgofbhldcajfamjganpeacipebckp))

---
## More things to try!

- Use a [fork-n-go project](http://jlord.us/forkngo/)
- Try saving images to GitHub (about [rendering and diffing images](https://help.github.com/articles/rendering-and-diffing-images/))
- Play with displaying [gists](https://gist.github.com/) with [blocks](http://bl.ocks.org/-/about) (handy [browser extensions](https://github.com/mbostock/bl.ocks.org/blob/master/README.md))

---

# What do you next?

After the workshop, you may want to download and install:

- [GitHub Desktop](https://desktop.github.com/)
- A terminal application (try [iTerm2](http://iterm2.com/) for OS X or [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/) for Windows)
- A desktop text editor (try [Atom](https://atom.io/))

You can also apply for a non-profit account through [GitHub for Good](https://github.com/nonprofit).

--

[![GitHub Desktop](/presentations/images/2016-06-02-github-desktop.png)](https://desktop.github.com/)

--

[![iTerm2](/presentations/images/2016-06-02-iterm2.png)](http://iterm2.com/)

--

[![Atom](/presentations/images/2016-06-02-atom-io.png)](https://atom.io/)

--

[![GitHub for Good](/presentations/images/2016-06-02-github-nonprofit.png)](https://github.com/nonprofit).

---

## How did we design this workshop?

Note: I am planning to set up either a workshop website (e.g. [Software Carpentry template](https://github.com/swcarpentry/workshop-template)) or a more simple collection of Markdown files (e.g. [this CUNY workshop on Git/GitHub](https://github.com/mckinniburgh/gitWorkshop)) on the [bLAM collective account](https://github.com/blamcollective). We also need a repository or a place within the workshop repository for students to contribute (Software Carpentry [recommends setting up a separate repo](https://github.com/swcarpentry/workshop-template#setting-up-a-separate-repository-for-learners)).

Here are the models we looked at for this workshop:

- [Collaboration and Writing Workflows with Git and GitHub: A GC Digital Fellows Workshop, Spring 2016](https://github.com/mckinniburgh/gitWorkshop)
- [Building Static Websites with Jekyll and GitHub Pages](http://programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages), Programming Historian
- Library Carpentry. [Week 3: Git](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md)
- [Resources for learning git](https://help.github.com/articles/good-resources-for-learning-git-and-github/)

---

## Resources on Git, GitHub, and Version Control

- [Git Tutorials](https://www.atlassian.com/git/tutorials)
- [A Visual Guide to Version Control](http://betterexplained.com/articles/a-visual-guide-to-version-control/)
- [Getting Started with GitHub Desktop](https://help.github.com/desktop/guides/getting-started/)
- [GitHub for Beginners](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
