
# bLAM Class: GitHub and Open Source

Welcome! **By the end of this lesson**, you will…

- Create a **repository**
- Make a **commit** to a repository on GitHub
- Submit a **pull request** to a shared repository

--

## What do you need for this workshop?

- A computer (Mac/Windows)
- The ability to download and install software on the computer
- An internet connection that can support downloading software.

--

## How difficult is this workshop?

Beginner (we will not use the command line for this workshop).

--

## How did we design this workshop?

Note: I am planning to set up either a workshop website (e.g. [Software Carpentry template](https://github.com/swcarpentry/workshop-template)) or a more simple collection of Markdown files (e.g. [this CUNY workshop on Git/GitHub](https://github.com/mckinniburgh/gitWorkshop)) on the [bLAM collective account](https://github.com/blamcollective). We also need a repository or a place within the workshop repository for students to contribute (Software Carpentry [recommends setting up a separate repo](https://github.com/swcarpentry/workshop-template#setting-up-a-separate-repository-for-learners)).

Here are the models we looked at for this workshop:

- [Collaboration and Writing Workflows with Git and GitHub: A GC Digital Fellows Workshop, Spring 2016](https://github.com/mckinniburgh/gitWorkshop)
- [Building Static Websites with Jekyll and GitHub Pages](http://programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages), Programming Historian
- Library Carpentry. [Week 3: Git](https://github.com/LibraryCarpentry/week-three-library-carpentry/blob/master/Git_lesson.md)

---

## What should you do before the workshop?

1. [Set up a GitHub account](https://github.com/join)

###  Optional steps

2. Download and install [GitHub Desktop](https://desktop.github.com/) (available for Mac or Windows)
3. Download a terminal application (e.g. iTerm)
4. Download and install a desktop text editor (e.g. [Atom](https://atom.io/))

---

# Let's talk about GitHub

Note: This section is adapted from these [CUNY workshop materials](https://github.com/mckinniburgh/gitWorkshop/blob/master/2_conceptOverview.md).

---

## What is Git?

**Git** is a version control tool. It lives on your computer (is local), and is accessed through the command line.

Git is the **local** power behind _version control_.

---
## What is version control?

---

## What is GitHub?

**Github** is a hosting service for git repositories. You must first set up an account and configure it on your computer.

Once your local **git** repository and **Github** are connected, you can make copies of other users' repositories, edit them, and send your proposed changes back to the user who can then choose to incorporate your work into their repository.

Github _connects_ Git repositories remotely and is the power behind _collaboration_.

---

## Why use GitHub?

Here are three reasons that people and organizations are using GitHub.

- To use version control
- To share open-source projects
- To facilitate collaboration

Note: **Ask participants**: why are you here? Why do you want to use GitHub?
---

## Resources on Git and Version Control

- [Git Tutorials](https://www.atlassian.com/git/tutorials)
- [A Visual Guide to Version Control](http://betterexplained.com/articles/a-visual-guide-to-version-control/)

--
## How do I use git on the command line?

This workshop _does not_ teach you how to use git using the command line. Here are a few resources do teach git:

- [tryGit](https://try.github.io/levels/1/challenges/1) from [Code School](https://www.codeschool.com/courses/try-git)
- [Learn Git](https://www.codecademy.com/learn/learn-git) from Codecademy
- [Git It](https://github.com/jlord/git-it-electron) application

---
## How are GLAMs using GitHub?

Galleries, libraries, archives and museums are using GitHub to share and collaborate around a variety of things. These include:

- Code
- Data
- Maps or Geodata
- Writing
- Websites

Note: Ask participants – while we look at these examples, you can “star” any repositories that you find interesting or want to bookmark.

For logged-in users, your “stars” are available here [https://github.com/stars](https://github.com/stars)

You can find more interesting repositories at [https://github.com/explore](https://github.com/explore)

--

### Code
A variety of software projects used by libraries, galleries, archives and museums host their code on GitHub including [Zotero](https://github.com/zotero/zotero), [Omeka](https://github.com/omeka/Omeka), [CollectiveAccess](https://github.com/collectiveaccess) and [CollectionSpace](https://github.com/collectionspace). Sometimes

--

### Data
In 2012, the Smithsonian Cooper-Hewitt National Design Museum in New York published their [collection metadata](http://labs.cooperhewitt.org/2012/releasing-collection-github/) to GitHub using a Creative Commons Zero license. The [Tate Gallery](https://github.com/tategallery/collection) and [Museum of Modern Art](https://github.com/MuseumofModernArt/collection)soon followed.

--

### Maps and Geodata
In 2015, the New York Public Library published a [location dataset](https://github.com/NYPL-publicdomain/greenbooks) scraped from the digitized Negro Motorist Green Book travel guides. In 2016, the New York Public Library created [a website](http://publicdomain.nypl.org/greenbook-map/) to display the data (hosted [on GitHub](https://github.com/NYPL-publicdomain/greenbook-map)).

--

### Writing
In 2015, the Andy Warhol Museum drafted and published their [digital strategy documents on GitHub](https://thewarholmuseum.github.io/digital-strategy/) using a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://thewarholmuseum.github.io/digital-strategy/LICENSE.txt) license.

--

### Websites
In 2016, the City of Los Angeles Department of Cultural Affairs published their [WordPress child theme on GitHub](https://github.com/dcadigital/cultural-affairs-wp-theme). Recently, the Australian Center for the Moving Image created [a website template](https://github.com/ACMILabs/static-museum-audio-guide) using Jekyll to create a museum audio guide.

---

## Open Licensing
You may have noticed that many of these projects use Creative Commons or other **open licenses**.

--

### What is an open license?
A license is a document that specifies what can and cannot be done with a work (whether sound, text, image or multimedia). It grants permissions and states restrictions. Broadly speaking, an open license is one which grants permission to access, re-use and redistribute a work with few or no restrictions.

--

### Why use an open license?
Works that are published without an explicit license are usually subject to the copyright laws of the jurisdiction they are published in by default. Open licenses enable creators to allow more freedom in what others can do with their works.

--

### How do you choose a license?

Try [Choose a License](http://choosealicense.com/)

---

## Getting Started with GitHub

- [Getting Started with GitHub Desktop](https://help.github.com/desktop/guides/getting-started/)
- [GitHub for Beginners](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)

---

## Let's build something

---

## Why use plain text?

--

## What is Markdown?
This section is via the CUNY tutorial.

Markdown is a markup (I know!) style that allows you to annotate text for formatting in a quick and lightweight manner.
GitHub supports markdown, which renders more attractive files.

Markdown is also thought to be more sustainable over time, since it is a plain text file. You'll notice this file is in markdown--check out its extension!

For a cheat-sheet to get you started, read here: [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). I used this cheatsheet for reference in creating this repo.

For more: [Dennis Tenen and Grant Wythoff, "Sustainable Authorship in Plain Text Using Pandoc and Markdown."](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

--

## Resources on Markdown

- [Getting Started with Markdown](http://programminghistorian.org/lessons/getting-started-with-markdown), Programming Historian
- [Mastering Markdown – GitHub](https://guides.github.com/features/mastering-markdown/)
- [Sustainable Authorship in Plain Text using Pandoc and Markdown](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown), Programming Historian

[Markdown Tutorial](http://www.markdowntutorial.com/):
> Markdown is a way to write content for the web. It’s written in what nerds like to call “plaintext,” which is exactly the sort of text you’re used to writing and seeing. Plaintext is just the regular alphabet, with a few familiar symbols, like asterisks ( \* ) and backticks ( \` ). Unlike cumbersome word processing applications, text written in Markdown can be easily shared between computers, mobile phones, and people. It’s quickly becoming the writing standard for academics, scientists, writers, and many more. Websites like GitHub and reddit use Markdown to style their comments. If you have ten minutes, you can learn Markdown!

---

# More Fun Stuff with GitHub

- [Fork-n-go projects](http://jlord.us/forkngo/)
- [GitHub Pages](https://pages.github.com/)
- [prose.io](https://prose.io) (handy [Chrome extension](https://chrome.google.com/webstore/detail/prose/onippmookoohgjgccejcjmlpoohbjgjn))
- [geojson.io](http://geojson.io/) (handy [Chrome extension](https://chrome.google.com/webstore/detail/geojsonio/oibjgofbhldcajfamjganpeacipebckp))
- Images (about [rendering and diffing images](https://help.github.com/articles/rendering-and-diffing-images/))
- [Blocks](http://bl.ocks.org/-/about) (handy [browser extensions](https://github.com/mbostock/bl.ocks.org/blob/master/README.md))
