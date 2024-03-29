## *Sean Hall the Diet Dark Knight*

Hello one and all! My name is Hall, Sean Hall.

I am a Washington boy born and raised. I was born in Everett in the year 1991 and from there I've lived in Lake Stevens, Mukilteo, Granite Falls and most importantly Everett! Along the way I've made many fond memories with my family and friends but once September of 2011 came around I had to say, "Good bye!" to my regular way of life. I enlisted into the United States Air Force. I learned how to become a C-130 Crew Cheif and gained experience in the "H Model" with two variet types, Shadows and Talons, along with the "J Model". During my seven year enlistment I saw more of the world then I ever thought I would. In the United States, for the first time, I saw Texas, Ohio, Kentucky, Tennessee, Kansas and Arkansas then overseas I visited England, Whales, Scotland, Germany, Spain, Czech Republic and a few others. During this time I gained so many more relationships and bonds that I will forever be greatful for but I finally reached a point where I desperatley needed something different for my over all life. Which is what eventually lead me to where I am now, Code Fellows 102!

### Learning Journal

Growth Learning (Lab 01)

```markdown
"Growth Learning" in the most simple of my terms is being easy on yourself while having a positive outlook on challenging problems.

Staying in a Growth Mindset

1. My skill in coding will progress at a pace that is meant for me, others skill progression is not related to me.
2. It takes a lot to make me lose my temper with a problem and sometimes completely give up on the task. So, I need to take a deep breath before I arrive at that stage and ask for help or whatever could lead to a solution.
3. Don't be so critical on yourself, do the best work that **YOU** can do.
```

The following will be detailing what I personally learned and found useful in Code 102 on the second day of June 25th 2019.

```markdown
# Notes
- **Git**
  -It is the "Stupid Content Tracker"
  -Able to check changes between files
  -It is a **version control system**
  -View, Apply, & Remove changes
  -Rollback = If something has gone wrong you are able to go back to before it became corrupted
  -Lives on the computer
  -Used inside of GitHub
  -Completely different from GitHub
- **GitHub**
  -Share code w/ others
  -Online place to store code (back up is good!)
  -Uses Git to help manage team's work:
    -Version tracking
    -Reviewing changes
    -Keep changes seperate until you want to add them together
- **Repository**
  -Collection of files thatg you've told Git to pay attention to
  -1 project = 1 repository
  -Large projects = multiple repos for different parts of system (ie. front end & back end)
  -Repos can live on GitHub &/or computer

##Key Concepts
###Git
1. Base code
2. "clone" -> pulls down a copy of the remote repo
3. "add" -> stages a file for commit
4. "commit" -> **locks** in your changes
5. "push" -> put my changes in GitHub

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

```
Revisions and the Cloud (Read 03)
```markdown
Git Tutorial: A Comprehensive Guide - Notes
-Prerequisites
  -Understand Command Line for Windows and Linux
-Version Control
  -A system that allows a user to visit various areas where changes were made so that mistakes can easily be rectified
  -Local Version Control = one database on hard disk that stores changes to files
  -DVCS = Distributed Version Control systems
  -DVCS has multiple mirrored repositories so it allows for steamlined teamwork with multiple people
  -Three states of GIT
    1. Commited
    2. Modified
    3. Staged
-Getting Started  
  -GIT includes inherent Graphical User Interface (GUI) tools
  -Three ways to get more info on  particular command, by accessing the manual:
   1. git help command
   2. git command --help
   3. man git-command
-Setting up a Git Repository
  -Importing
  -Cloning
 -Workflow
  -Local Repository Structure
    -Local Git repo has three components:
      1. Working Directory: Actual files reside here
      2. Index: Area used for staging
      3. Head: Points to most recent commit
  -Committing a File
    -once one or multiple files are staged -> commit the changes & record what was done -> input: git commit -m "made change x,y,z"
  -Commiting All Changes
    -input: git commit -a
  -Pushing Changes
    -input: git push origin master
```

```
Structure web pages with HTML (Read 04)
```markdown
HTML & CSS - Chapter 18 - Process & Desgin
-Process used when creating a new website
-Websites need to be created with the Target Audience in mind
  -Age range?
  -Men, Women, or Both?
  -Average Income?
  -How often do they use the web?
  -Size of company or relevant department?
  -How large is the budget they control?
  -Core things to know:
    1.Name
    2.Gender
    3.Age
    4.Location
    5.Ocupation
    6.Income
    7.Web use
-Know why people are using your website
  -Two basic categories to determin the "Why?"
    -Key Motivations: General entertainment or specific goal?
    -Specific Goals: Wanting to get something ASAP
-Having a site map allows plan a structure for a site
-Wireframes = organize information for each page
-Communication is heavily reliant on good desgin
-Size, Color, & Style = Easily differentiate between pieces of info
-Grouping & Similarity = helps simplify presented info
```

Design web pages with CSS (Read 05)
```markdown
HTML & CSS - Chapter 11 - Color
-There are three ways to specify color in CSS:
  1.RGB (Red, Green, Blue): 100,100,90
  2.Hex Code: #ee3e80
  3.Color Names: DarkCyan (this type isn't used often
-CSS treats each HTML element as if it appears in a box = the bacground-color property sets color of background for specfic box
-Background color can be specified in same three ways: RGB, Hex Code, & Color Names
-Background color not specified = transparent
-Color on a computer screen is always made with mixing an amount of red, green, & blue
-With foreground & background colors there should be enough contrast for text to be legible
-High Contrast = the easiest way to read but if for long period of time Medium Contast is best
-CSS3: Opacity; a property which allows you to specify opacity of an element & any of it's child
  -Value is number between 0.0 & 1.0 : 0.5 = 50% or  0.15 = 15%
  -CSS3 rgba: allows to specify a color similar to RGB value but adds fourth value indicating opacity
    -Fourth value is an alpha value & is a number between 0.0 & 1.0
-CSS3: HSL Colors; new & intuitive way to specify colors using hue, saturation, and lightness values
-CSS3: HSL & HSLA; alternate way to specify colors
-Color brings site to life, helps convey mood, & evokes reaction
-Color pickers help find color I want
```
Activate web pages with JavaScript (Read 06)
```markdown
JavaScript & jQuery - Pages 43-69
-Do Along: Pages 46-49
-The three major languages in creating web pages: HTML, CSS, & JavaScript
-These three languages popular way to approach building web pages = progressive enhancement
-JavaScript written in plain text like HTML & CSS
-Object = Represents entire web page
-Method = The write() method of document object allows new content to be written into page where the <script> element sits
-When browser comes across <script> element, it stops yo load script & checks to see if it needs to do anything else
-Best to keep JavaScript code in own JavaScript file = filename.js
-Sriptis series of instructions that a computer can follow one-by-one
  -Each individual instruction or step is known as a statement = statements should end w/ semicolon
-Write comments for each section of code to clearly explain what that code's function is  
-Use variables to remember values
-To use a variable = announce you want to use it  
-Need to assign a value to a variable  
-Data Types
  1.Numeric Data Type
  2.String Data Type
  3.Boolean Data Type
-Following are 6 rules to always follow when giving a variable a name:
  1.Must begin w/ letter, dollar sign ($), or an underscore(_)
  2.Name can contain letters, numbers, dollar sign ($), or an underscore(_) / Can Not Use: (-) or (.)
  3.Cannot use keywords or reserved words
  4.All variables are case sensitive
  5.Make a name that is related to the information stored by the variable
  6.Camel Case: if variable made of more that one word, use capital letter for first letter ofevery word after the first word = firstName
```

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/seankhall/github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
