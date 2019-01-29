# Setup

<figure>
    <p>
        <a href="{{site.baseurl}}/index.html">Home</a> |
        <a href="{{site.baseurl}}/pages/setup.html">Setup</a> |
        <a href="{{site.baseurl}}/pages/lessons.html">Lessons</a> |
        <a href="{{site.baseurl}}/pages/files.html">Files</a> |
        <a href="{{site.baseurl}}/pages/project.html">Project</a> |
        <a href="{{site.baseurl}}/pages/toolkit.html">Toolkit</a>
    </p>
</figure>

---

This page contains brief instructions on how to install the core applications that we will use in this course. During the course, these tools will be introduced slowly, and you will not be expected to become proficient in all or even most of these tools.

You can install them all at once, or gradually over the course. Feel free to play around with any of these tools

1. [GitHub Repository Manager](#1-github-repository-manager)
2. [Atom Text Editor](#2-atom-text-editor)
3. [Slack Team Messenger](#3-slack-team-messenger)
4. [Tableau Visualization Platform](#4-tableau-visualization-platform)
5. [Optional Atom Packages & Themes](#6-atom-packages-and-themes)

---

## IMPORTANT NOTE

Some of the following passages refer to your 'Terminal', to access it, follow the directions for your operating system...

**(Windows)**

Go to your 'Start Menu', then the' Windows PowerShell' folder, and click Windows PowerShell.

*FOR ADMIN PRIVILEGES:* If you need admin privileges, instead of left-clicking, **RIGHT-CLICK** the 'Windows PowerShell' application and Choose 'Launch as Administrator' (or something like that). Enter your password when prompted.

**(OSX)**

Go to your Applications folder, then the Utilities folder. Then, click the 'Terminal' application.

*FOR ADMIN PRIVILEGES:* <br> If you need admin privileges, start your command with 'sudo'. For example, `fakecommand --fake-option "some/fake/path"` would become `sudo fakecommand --fake-option "some/fake/path"`. You will be asked to enter your password, and then the command will run.

To learn the basics of command line, try the [free course at Codecademy](https://www.codecademy.com/)!

---

## 1 GitHub Repository Manager

1. [Sign up for a GitHub Account](https://github.com)
2. [Install GitHub Desktop](https://desktop.github.com/)

---

## 2 Atom Text Editor

1. [Install Atom](https://atom.io/)
2. Configure Atom
    1. Either [follow this configuration guide](http://www.marinamele.com/install-and-configure-atom-editor-for-python)
    2. Or follow the TLDR summary below...


3. **(OSX ONLY)** Then restart Atom and click 'Hack on the Init Script' at the Welcome Guide (or go to the File menu and choose 'init script'), and paste the following on the last line...
```coffee

process.env.PATH = ['/usr/local/bin/', process.env.PATH].join(':')
```

4. Then restart Atom, open the Preferences windows. Click the 'Editor' tab. Scroll down and Tab Length to 4 spaces and click Automatic PEP8 Validation

---

## 3 Slack Team Messenger

1. [Download and install](https://slack.com/downloads/) a copy of Slack messenger (or use their web interface)
2. Register an account at our course's Slack channel, [hacking-history.slack.com](https://hacking-history.slack.com/).

* For those interested, you can also register an account with the main Digital Humanities slack channel, [hacking-history.slack.com](https://digitalhumanities.slack.com/)

---

## 4 Tableau Visualization Platform

1. [Sign up for a student account](https://www.tableau.com/academic) (assuming you are a student), and then follow the instructions to install Tableau Desktop.
2. You will be able to use a 14-day trial, during which they will contact you with details for free access for a *full year.*

---

## 5 Atom Packages and Themes

1. To customize Atom.io, open the file menu, if on Windows choose 'Settings', if on OSX (Mac) choose 'Preferences'
    2. To **change** important settings, choose 'Core' or 'Editor'
    3. To **alter** settings of installed items, choose either 'Packages' or 'Themes'
3. To add new themes and packages, open your settings/preferences and click the 'Install' tab
    1. Type the name of a package or search term
    2. Choose 'Packages' or 'Themes', depending on your needs
3. Recommended Theme
    1. [atom-material-ui](https://atom.io/themes/atom-material-ui) (styles backgrounds, menus, and interface)
    2. [atom-material-syntax](https://atom.io/themes/atom-material-syntax) (sets colors for syntax highlighting)
4. Recommended Packages (* indicates highly recommended)
    1. General
        1. [file-icons](https://atom.io/packages/file-icons) (colors and styles icons based upon filetype in tree view)*
        2. [highlight-selected](https://atom.io/packages/highlight-selected) (highlights all instances of a word when you double-click it)*
        3. [ask-stack](https://atom.io/packages/ask-stack) (quickly search for answers to problems on StackOverflow.com)*
        3. [autoclose-html](https://atom.io/packages/autoclose-html) (automatically adds closing tags when you write html)
        4. [autocomplete-paths](https://atom.io/packages/autocomplete-paths) (automatically suggests locations when you type in paths)
    2. Markdown
        1. [language-markdown](https://atom.io/packages/language-markdown) (adds sytax highlighting and grammar support for Markdown)*
        2. [markdown-preview](https://atom.io/packages/markdown-preview) (opens a rendered preview of your Markdown document)*
        3. [markdown-pdf](https://atom.io/packages/markdown-pdf) (converts a Markdown file to a PDF on the fly)
    3. Git/GitHub
        1. [tree-view-git-status](https://atom.io/packages/tree-view-git-status) (shows current status of git repo in your tree view)*
        2. [git-time-machine](https://atom.io/packages/git-time-machine) (visually see history of a file)
        3. [git-plus](https://atom.io/packages/git-plus) (allows you to do git terminal commands inside Atom)
    4. Python (only for those who want it)
        1. Error Checking (all packages are required to work)
            1. [linter](https://atom.io/packages/linter) (base package which enables error-checking in multiple langauges)
            2. [linter-ui-default](https://atom.io/packages/linter-ui-default) (mid-level package which gives a user-interface for error-checking in multiple languages)
            3. [linter-flake8](https://atom.io/packages/linter-flake8) (top-level package which implements the rules specific to Python)
