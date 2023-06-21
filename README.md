# README-explaination


The Readme file is often the first file that the users read. 
It is a text file that contains information for the user about the software, project, code, or game, or it might contain instructions, help, or details about the patches or updates.

Therefore, READMEs are useful for who reads them.

From Wikipedia's README article:
In software development, a README file contains information about the other files in a directory or archive of computer software. | Example                | Description                         |
|----------------|-------------------------------|
|"hello world" | A string            |
|'' "multi \n line \n string" '' | "A multi-line string. Strips common prefixed whitespace. \n Evaluates to multi\\n line\\n string." |
A form of documentation, it is usually a simple plain text file called README, Read Me, READ.ME, README.TXT, README.md (to indicate the use of Markdown), or README.1ST.

The file's name is generally written in uppercase. 
On Unix-like systems in particular, this causes it to stand out – both because lowercase filenames are more common, and because the ls command commonly sorts and displays files in ASCII-code order, in which uppercase filenames will appear first.


Contents:
A README file typically encompasses:

    Configuration instructions
    Installation instructions
    Operating instructions
    A file manifest (a list of files in the directory or archive)
    Copyright and licensing information
    Contact information for the distributor or author
    A list of known bugs
    Troubleshooting instructions
    Credits and acknowledgments
    A changelog (usually aimed at fellow programmers)
    A news section (usually aimed at end users)


History:
This section needs expansion. You can help by adding to it. (February 2015)

It is unclear when the convention of including a README file began, but examples dating to the mid-1970s have been found. 
Early Macintosh system software installed a Read Me on the Startup Disk, and README files commonly accompanied third-party software.

In particular, there is a long history of free software and open-source software including a README file; the GNU Coding Standards encourage including one to provide "a general overview of the package".

Since the advent of the web as a de facto standard platform for software distribution, many software packages have moved (or occasionally, copied) some of the above ancillary files and pieces of information to a website or wiki, sometimes including the README itself, or sometimes leaving behind only a brief README file without all of the information required by a new user of the software.

The popular source code hosting website GitHub strongly encourages the creation of a README file – if one exists in the main (top-level) directory of a repository, it is automatically presented on the repository's front page. 
In addition to plain text, various other formats and file extensions are also supported,[11] and HTML conversion takes extensions into account – in particular a README.md is treated as GitHub Flavored Markdown. 


As a generic term:

The expression "readme file" is also sometimes used generically, for other files with a similar purpose.
For example, the source-code distributions of many free software packages (especially those following the Gnits Standards or those produced with GNU Autotools) include a standard set of readme files:

    README 	General information
    AUTHORS 	Credits
    THANKS 	Acknowledgments
    CHANGELOG 	A detailed changelog, intended for programmers
    NEWS 	A basic changelog, intended for users
    INSTALL 	Installation instructions
    COPYING / LICENSE 	Copyright and licensing information
    BUGS 	Known bugs and instructions on reporting new ones
    CONTRIBUTING / HACKING 	Guide for prospective contributors to the project

Also commonly distributed with software packages are an FAQ file and a TODO file, which lists planned improvements. 


As far as for those who write READMEs, there are tools that read and render READMEs. 
Those who write them often use a markdown language to format READMEs.
Github will automatically render file named README.md.


Here is an example found at https://stackedit.io/app#:

# Welcome to StackEdit!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


# Files

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|

| Example                | Description                         |
|----------------|-------------------------------|
|"hello world" | A string            |
|'' "multi \n line \n string" '' | "A multi-line string. Strips common prefixed whitespace. \n Evaluates to multi\\n line\\n string." |
| "hello ${ { a = "world"; }.a }" \n "1 2 ${toString 3}" \n "${pkgs.bash}/bin/sh" | String interpolation (expands to "hello world", "1 2 3", "/nix/store/\<hash\>-bash-\<version\>/bin/sh") |
| true, false | Booleans |
| null | Null value |
| 123 | An integer |
| 3.141 | A floating point number |
| /etc | An absolute path |
| ./foo.png | A path relative to the file containing this Nix expression |
| ~/.config | A home path. Evaluates to the "<user's home directory>/.config". |
| <nixpkgs> | Search path for Nix files. Value determined by $NIX_PATH environment variable |
| Compound values |


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

