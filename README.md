## Moving from theory to practice

This MarkdownProduction repository is part of the NOSTERIIHI effort at GitHub. [A guide to Markup editing](https://github.com/phdonner/Markdown/) for rural developers has been drafted. Here we are concerned with the practical task of editing, rendering and publishing those pages.

This is a personal undertaking which contributes to the NOSTERIIHI smart rural development project. It could be important to state an example of how bottom-up oriented, open-source, voluntary collaboration can be a smart concept which wins over passivating, profit-based and top-down controlled work. 

I would certainly like to collaborate with other developers, who are willing to contribute in transforming automation into a way of empowering rural developers. Welcome to the rural zero marginal cost collaborative community.

---

## How can Markdown pages be rendered and published on the World Wide Web?

Software development is in itself a conceptual activity. At best, it provides abstract tools which can facilitate production processes.  The information society should provide us with productive tools, which should improve our life quality. But they should do so without resorting to artificial income logic. 

It could be practical to start quite modestly by producing a straightforward case, which would prove that there is nothing very mystical about automation. The production of _HTML_ coded web pages has been a rather complicated and error prone process. _Markdown_ is a notation procedure which was invented in the early years of the millennium. However, it is only during the last few years that the technique has become widely popular among developers. One of the reasons, is that GitHub and some other developer resources adopted Markdown as a resource for quick production of Web pages. That is how a couple of resources were aligned to support the process of transforming Markdown to HTML.
 
This small NOSTERIIHI project will gradually evolve into a bilingual tutorial on methods of setting up a low-cost computer environment, which enables rural developers to produce HTML pages for use in the WWW. This task will be achieved without resorting to commercial services, such as Facebook or WhatsApp. Let's see where the project takes us.

<!-- Follow up with a breakdown of the basic concepts:   -->
<!-- HTML the marking language to make WWW pages         -->
<!-- TCP/IP HTTPMediator                                 -->
<!-- Markdown: A simple marking language                 -->
<!-- Automation tools: Git                               -->
<!-- The GitHub developer resource                       -->
<!-- Automation tools: PowerShell                        -->
<!-- VisualStudio Code                                   -->
<!-- My COM tool                                         -->

---

## The workflow

Planning is a conceptual activity. To be efficient, we could prepare an outline of the various workflows which can be followed in order to arrive at a solution to the problem. The following diagram will hopefully guide our work. 

```mermaid
%%{init: {'theme':'forest'}}%%
flowchart LR
    id1([Markdown])
    id2(GitHub)
    id3([WWW])
    id4(Git)
    id5(GitHub)
    id6(Visual Studio Code)
    id7(Powershell)
    id8(HTML)
    id1-->id2-->id3;
    id1-->id4-->id5-->id3;
    id1-->id6-->id7-->id8-->id3;
style id1 fill:#f9f;
style id3 fill:#f9f;
```

<!-- Also indicate various other output alternatives: WWW, Slide show, PDF, Email etc -->

<!-- Find out how the Mermaid nodes could be activated to become hyperlinks           -->

If you are curious to know how the above diagram was designed, check out the Markdown subtopic about [Mermaid](markdown.md#mermaid-diagrams-a-way-of-visualizing-conceptual-frameworks), which is a free diagram design and rendering tool. 

The next subheadings are a list of some of the topics and immediate tasks that we are facing right now.

---

## Markdown

Markdown is intended to be as easy-to-read and easy-to-write way of indicating style in a character coded environment. Although Markdown is easy to learn, it can still become a rather powerful resource in information society construction. Although Markdown is easy to learn, it can still become a powerful resource in information society construction. That is why Markdown was selected to be the test case for the use of automation in rural development.

### 🔗 Links to Markdown web resources

Please, have a closer look at the details of this topic by navigating the [Markdown section](markdown.md) of the NOSTERIIHI project.

---

## Git and GitHub

_Git_ is a command language for the safe creation and maintenance of documents. The command language was developed by Finnish Linus Torvalds as an aid in creating the Linux operating system. It provides an elegant mechanisms for _version control_. Git handles update history in an invisible file hidden in the file system. By documenting the various stages of the update history, the user will be able to easily retrieve earlier versions. _Collaboration_ is an other aspect of the development process that Git facilitates. Developers can work concurrently on various aspects of the content without the risk of colliding updates.

*GitHub* is a free resource, where developers of open-source code and documents can create and share new content. By paying a modest yearly fee, the subscriber gets access to a number of bonus features which are not available to the ordinary registered user. There or other similar services with varying focus. Let's try to discover how Git, GitHub and related open-source tools and services could be beneficial in information society construction. 

### 🔗 Links to Git and GitHub introductions

[Git and GitHub Tutorial – Version Control for Beginners](https://www.freecodecamp.org/news/git-and-github-for-beginners/)  
by Ihechikara Vincent Abba

[Git Tutorial](https://www.w3schools.com/git/)  
at w3schools.com

[Git GitHub Getting Started](https://www.w3schools.com/git/git_remote_getstarted.asp)  
at w3schools.com

### 📚 References on Git and GitHub

_GIT GITHUB Programming in 8 Hours, For Beginners_  
by Ray Yao, 2021.

---

## Publish Markdown WWW pages at GitHub

There is a special section of GitHub, located at pages.github.com which is dedicated to WWW publication. Navigate to the [GitHub pages](https://pages.github.com/), where you can find a tutorial which introduces ways of constructing a site for your personal use or for your organization. Alternatively the pages can become a forum for discussion of your project.

https://github.com/phdonner/ is an experimental site. So please, don't expect that the content would be static somehow. On the contrary: If the structure and the content develops dynamically, then that could be taken as a sign of active and perhaps even productive work.

### 🔗 Links to Markdown WWW pages at pages.github.com

[GitHub pages](https://pages.github.com/)

---

## Visual Studio Code

Before the appearance of the open-source Linux operating system, Microsoft Windows was by far the most appealing OS platform for software developers. With a low license fee, the entrance threshold was low. With the so called COM-based technologies MS made a leap into easy-going, script or machine language based development of automated systems. 

Dependency on proprietary arrangements is, however, in the long run a stumbling block for any non-profit oriented developer. Therefore, the initiative to place both the Visual Studio Integrated Development Environment (IDE) and the PowerShell scripting environment into the domain of open-source and cross-platform development were most welcome moves.

_Visual Studio_ (VS) is an extensible tool written by developers for the developer community. This implies that there is a plentitude of extensions, including many extensions which improve VS Markdown functionality. For instance, [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) is a Markdown linting and style checking tool which includes a library of rules to encourage standards and consistency for Markdown files. This improves the readability of the authors Markdown files.

### 📋 Tasks

Here are a few examples of the kind advantages that you can achieve with VS extensions:

- [ ] Create a slide show or a presentation from Markdown code and the Marp extension <!-- Add pointers to each of these extensions -->
- [x] Make a Markdown compatible diagram with the Mermaid extension
- [ ] Convert your Markdown document to PDF

<!-- Providing a spelling checker could be yet another useful extension -->

> [!TIP]
> If you are already a registered GitHub user, you can experience some aspects of Visual Studio Code functionality without delving into all intricacies of the tool. Replace the `.com` extension of your GitHub repository web address with `.dev`. Proceed like this: Change github.com/`<your GitHub name>` to github.dev/`<your GitHub name>`. This loads the contents of your page into a browser version of Visual Studio Code.

### 📹 Tutorial videos on use of Markdown with Visual Studio Code

[Note Taking with VS Code & Git](https://www.youtube.com/watch?v=Hgucu1ch3mo)  
by Reynald Adolphe‬.

---

## Render and transform Markdown into HTML with PowerShell 

_PowerShell_ is a scripting language created by developers at Microsoft, but nowadays maintained by a wide open-source community with MS support. A quite remarkable change of focus came about when this undertaking shook off its narrow roots and turned into a cross-platform language, which is nowadays available for Windows, Apple and Linux operating systems. Raspberry OS support was initially experimental, but since some time the Raspberry Pi installations have been quite stable. As an extension to the Visual Studio Code integrated development environment, PowerShell has become a viable tool for users and administrators with automation needs (perhaps even on a cross-platform basis).

### 🔗 Links to PowerShell documentation

Check out details of PowerShell Markdown automation by delving into the [PowerShell section](powershell.md) of the NOSTERIIHI report.

[PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
at learn.microsoft.com.

### 📚 References on PowerShell

_Windows PowerShell Cookbook 2e_  
by Lee Holmes, 2010.


<!-- Add a list of the best tutorials -->
