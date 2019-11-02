# Hamster system

Boost productivity and reduce stress by organizing your documents, workflow and personal budget with an ultra-simple system loosely inspired in [GTD](http://en.wikipedia.org/wiki/Getting_Things_Done), [Todo.txt](https://github.com/todotxt/todo.txt), OBTF (One Big Text File), [Bullet journal](http://bulletjournal.com/) (notes on paper), spreadsheets, index cards, inbox zero and desktop zero.

### So, how can you start?

- [hamster folder](#hamster-folder): organize your (digital) documents
- [hamster flow](#hamster-flow): organize your workflow
- [hamster budget](#hamster-budget): organize your money

**TLDR:** 

- [What does this stuff solve?](#tldr)




---
## Hamster folder
### Organize your (digital) documents

*'Every document belongs to a project'.*

### Container:

- root folder: **YOUR NAME**

        First of all create a folder in a partition of your disk.
        ALL your stuff will be stored here.

- main folders: **PROJECT STATUS**

        Inside your superfolder there are 2 folders:

        INBOX (folder to store your active projects)
        ARCHIVE (folder to store your inactive projects - often organized in bundles)

---
### Project folders:

*[bundle] #project @subproject -folders*

- bundle of projects: **[ ]**

        Inside ARCHIVE folder you put [bundles of projects]:
        e.g: [large investor]

- project (derived from twitter hashtag): **#**  

        Inside INBOX, ARCHIVE or [bundle] folders you put #projects:
        e.g: #house in portugal    

- subproject (derived from twitter mention): **@**

        Inside #project folders you put @subprojects:
        e.g: @building permit

- storage folder: **-**

        Inside @subprojects you put -storage folders:
        e.g: -drawings
        e.g: -drawings-plans

---
### Naming:

- when reasonable reduce unnecessary nesting by merging folders. Hints:

        Prefer: #project@onlyOneSubproject
        Instead of: #project / @onlyOneSubproject

        Prefer: -drawings-details-wall
        Instead of: -drawings / -details / -wall

- hints for naming your folders:

        Use a prefix for temporary folders where you keep stuff before knowing what to do with them: _
        e.g: _standby

        Use a prefix for folders where you keep older versions of files: +

- name your files using a system that fits you<sup id="refnote1"> [1](#footnote1)</sup>. Hints:

        Use a prefix for standard / boilerplate files: $
        e.g: $curriculum

- great free tool for [batch renaming](http://www.bulkrenameutility.co.uk/Screenshots.php).

---
### Archiving:

- files by using a *change date* suffix<sup id="refnote6"> [6](#footnote6)</sup>: **date**

        Some possibilities:
        yourfile-2019-10-18
        yourfile+20191018

---
### How to navigate through your documents:

- you only need one *permanent* desktop shortcuts to navigate through your documents: 

        Shortcut to INBOX folder

        A shortcut to ARCHIVE is optional - only inactive projects are there.

- and/or a launcher-file finder<sup id="refnote2"> [2](#footnote2)</sup>. 




---
## Hamster flow
### Organize your workflow

*'Manage a collection of inputs'.*

- One text file on a cloud<sup id="refnote3"> [3](#footnote3)</sup> and a paper notebook collect all inputs:  
    - actionable inputs (todos) are managed in the paper notebook and in a section of the text file: *now* and *calendar*.
    - non-actionable inputs are managed in two sections of the text file: *bookmarks* and *notes*. One long file is easier to manage than many short files. See it as a *flat wiki* and use text editor's built-in search for navigation. However, this file is not *write-only*: review and *tree-shake* it periodically.<sup id="refnote4"> [4](#footnote5)</sup>

- todos listed in the *calendar* section of the text file have a due date: **[ ]**

        Dates are inserted before the task description (allowing chronological sorting):
        
        e.g. inserting a scheduled date: [year-month-day=hour]
        [2019-11-29=9h] Doctor appointment

        e.g. inserting a trigger/fuzzy date: [date >>]
        [2019-03-10 >>] Waiting for client feedback after this date

        e.g. inserting a deadline date: [date <<]
        [2019-10-22 <<] Pay electricity bill until this date

        e.g. without knowing the due date: [soon] or [someday]
        [soon] Call Mom
        [someday] Bungee jumping with friends

- resuming (check also [screenshots](#screenshots)):

        on a paper notebook:
            Now (collection of todos to be done ASAP)

        on a cloud, one text file with 3 sections:
            Calendar (collection of todos that can/must wait)
            Bookmarks (collection of bookmarks)
            Notes (collection of thoughts)

---
### Screenshots:

- *Calendar* section on Sublime text editor.<sup id="refnote5"> [5](#footnote5)</sup>

![superfolder-workflow-screenshot](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example.png)

- [YAML](https://www.json2yaml.com/convert-yaml-to-json) (for readability and possible data serialization) masked as markdown (for easier text-editor navigation).

![superfolder-workflow-screenshot-2](https://github.com/galfarragem/superfolder/blob/master/examples/superfolder-workflow_screenshot-example2.png)




---
## Hamster budget
### Organize your money

*'You may not need a personal budget'.*

Does it worth to spend cognitive bandwidth to know that last month you spent €312,23 on groceries? I already know that I spend *around* €300. **What I crave is to feel in control of my finances.**

How to do it in a practical way? Track your **net worth** in a spreadsheet:
 
- List all your assets (bank, ebank, stocks, funds, crypto, whatever) and sum them. List and sum your liabilities (if relevant). The difference is your net worth. You can even separate liquid from non-liquid assets (e.g. house, car). Every case is a case so you must build your template from zero.
- When your net worth is too risky (for your personality) get more tight.
- When you feel confortable with your number you can loosen up a bit.
- I used to track it every month. I loosen up to every quarter.




---
## TLDR:
*'What does this stuff solve?'*

#### hamster folder: organize your (digital) documents

- prediction (with acceptable accuracy) of filenames and where they are stored.<br>
A file finder<sup> [2](#footnote3)</sup> is great when you remember the filename but less useful when you don't.
- transmission of project folders with all project files and a predictable structure.

#### hamster flow: organize your workflow

- simple solution: use your favorite text editor and cloud, a paper notebook and almost no syntax. Minimum overhead.
- practical solution: mix the *good parts* of [many workflow management approaches](#hamster-system).
- future data exchange and serialization: [YAML](https://www.json2yaml.com/convert-yaml-to-json) notation saved as TXT files.

#### hamster budget: organize your money

- control your finances in a practical way.

*'Possible painpoint?'*

This system is not smartphone oriented. That's not even an issue for me but it might be for you.

*'Is this the truth?'*

Probably not but I don't know nothing that works better. I test new options and 'tree shake' existent ones agressively.

---
<sup>Notes:</sup><br>
<sup><a name="footnote1">1</a> - e.g: relevant [naming system for architects](https://github.com/galfarragem/gerbil-project). [↩](#refnote1)</sup><br>
<sup><a name="footnote2">2</a> - after having tried most options for Windows (win+type, Keypirinha, Everything, Cerebro, Wox, Zazu, Launchy, FARR), I'm using [Listary](http://www.listary.com/) Lite.<br>
Pros: Launch and file search without external software, low memory usage (less than 40k on win7), fast and configurable. Cons: No calculator function. [↩](#refnote2)</sup><br>
<sup><a name="footnote3">3</a> - Google Drive, Dropbox, etc. [↩](#refnote3)</sup><br>
<sup><a name="footnote4">4</a> - Try to keep it under 2K lines. If you can't, it means that some excerpts should live independently or even in a more suitable format (e.g. spreadsheet) [↩](#refnote4)</sup><br>
<sup><a name="footnote5">5</a> - hint: on Sublime press F9 (or F5 on Mac) to sort dates. [↩](#refnote5)</sup>
<sup><a name="footnote6">6</a> - After a long trial, "builds" were deprecated. "Change dates" are more practical and descriptive. [↩](#refnote6)</sup>

---
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Hamster-System</span> by Enio Ferreira is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
