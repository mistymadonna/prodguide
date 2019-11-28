# Visual Studio Productivity Guide
By Misty Hays

## EXECUTIVE SUMMARY
***Why a Productivity Guide?***

*The Productivity Guide serves as a tool for developers to save time when writing code. Instead of searching for documentation, shortcuts, and other resources, developers can find useful information in **one place**. This guide focuses on Visual Studio in the following areas: general tips, navigation and layout, debugging and error handling, refactoring, cloud, keybindings and shortcuts, performance, extensions, and others. It is a living document.*

### General
* Learn Shortcuts with [**Ctrl+Q**](https://aka.ms/prodguide-gen1) 
* [**Vertical tabs are now in Preview**](https://aka.ms/prodguide-gen2)
* [**Organize recent templates**](https://aka.ms/prodguide-gen3) by pinning, unpinning in New Project Dialog
* See quick locations of recently used projects/solutions/folders in [**search box in the start window**](https://aka.ms/prodguide-gen4)
* Newly installed project templates are indicated with a [**"New" label**](https://aka.ms/prodguide-gen5) *(after 5 times it goes away)*
* [**Tutorials and resources**](https://aka.ms/prodguide-gen6) based on your workload
* Not enough requirements to complete a piece of code? Mock it using [**task list**](https://aka.ms/prodguide-gen7)
* [**Solution Explorer shortcuts**](https://aka.ms/prodguide-gen8)
* [**Set bookmarks in code**](https://aka.ms/prodguide-gen9)
* [**IntelliSense**](https://docs.microsoft.com/en-us/visualstudio/ide/using-intellisense?view=vs-2019) code suggestions
* Understand your code structure then: use [**code map**](https://aka.ms/prodguide-gen10)
* [**Shortcut tips for Visual Studio**](https://aka.ms/prodguide-gen11)
* [**Creating code snippets**](https://aka.ms/prodguide-gen12)
* Use 'git diff -w' to ignore whitespace modifications caused by the document formatting
* [**How saved window layouts can save you time**](https://aka.ms/prodguide-gen14)
* [**Visual Studio productivity tips**](https://aka.ms/prodguide-gen15)
* **Track Active Item** in Solution Explorer ![Image](\assets\track-item.png)

### Navigation, layout
* Jump to location in file then: use [**map mode**](https://aka.ms/prodguide-nav1)
* See frequently used files then: use [**Edit/Go To Recent File**](https://aka.ms/prodguide-nav2)
* Move [**Properties window**](https://aka.ms/prodguide-nav3) to the right-side
* Move Solution Explorer and tabs to the left-side (less distance to move the mouse, less eye movement from Solution Explorer -> Test Explorer -> Team Explorer
* Detach/undock the “Changes” tab from Team Explorer and keep it as a subtab of the Solution Explorer group. That way, you can see the number of pending changes and quickly get the diffs.
* Default position of the debugging buttons can be docked using **“debug.toolBarLocation”: “docked”**

### Debugging, errors
* Display certain errors then: use [**Error List**](https://aka.ms/prodguide-debug1)
* Fix errors inline then: use [**light bulbs**](https://aka.ms/prodguide-debug2)
* [**See what changes have been made**](https://aka.ms/prodguide-debug3) to your code and the impact of those changes
* Use [**Live Share**](https://aka.ms/prodguide-debug4) to debug together in real time, no matter the language or platform
* Use [**Interactive Window**](https://aka.ms/prodguide-debug5) to write and test small code
* [**Visual Studio Debugger**](https://aka.ms/prodguide-debug6)
* [**Save time debugging**](https://aka.ms/prodguide-debug7)

### Refactoring
* Adjust fonts with [**Fonts and Colors**](https://aka.ms/prodguide-refac1)
* Change brace formatting with [**Formatting/New Lines**](https://aka.ms/prodguide-refac2)
* Change your indentation with [**Tabs**](https://aka.ms/prodguide-refac3)
* Copy JSON fragments with [**Paste Special**](https://aka.ms/prodguide-refac4)
* [**Use Scope to This**](https://aka.ms/prodguide-refac5) to declutter large projects ![Image](\assets\scope-to-this.gif)

### Cloud
* [**Build for the cloud**](https://aka.ms/prodguide-cloud1)
* [**Azure project templates**](https://aka.ms/prodguide-cloud2)
* [**Easy deployment**](https://aka.ms/prodguide-cloud3)
* [**If you’re dealing with an issue that is hard to reproduce locally on your machine**](https://aka.ms/prodguide-cloud4)
* Manage your Azure resources and resource groups with [**Cloud Explorer**](https://aka.ms/prodguide-cloud5)
* [**Azure Repos Git tutorial**](https://aka.ms/prodguide-cloud6)
* [**Kubernetes: Up and Running**](https://aka.ms/prodguide-cloud7)

### Keybindings
* Configure keyboard shortcuts using [**Options dialog box**](https://aka.ms/prodguide-keybi1)
* **Multiple cursors**: Alt+Shift+arrow (or down)
* **Alt+click+drag** selecting instead of copy/paste

### Performance
* [**Disable WPF designer**](https://aka.ms/prodguide-perf1) if you prefer to only see the XAML
* Disable the JavaScript analysis if unnecessary for your work

### Extensions
* [**GitHub Flow with Visual Studio**](https://aka.ms/prodguide-ext1) 
* [**C/C++ and C# that improves IDE features**](https://aka.ms/prodguide-ext2) 
* [**Trailing Whitespace Visualizer**](https://aka.ms/prodguide-ext3)
* [**Markdown Editor**](https://aka.ms/prodguide-ext4)
* [**Tools to optimize any JPEG, PNG and GIFs**](https://aka.ms/prodguide-ext5) 
* [**VsVim**](https://aka.ms/prodguide-ext6)
* [**C# productivity enhancer**](https://aka.ms/prodguide-ext7)
* [**Generate XML Comments from your code, maintain clean and up-to-date documentation**](https://aka.ms/prodguide-ext8)
* [**Full support for static HTML, Razor and WebForms**](https://aka.ms/prodguide-ext9)
* [**Arduino IDE for Visual Studio**](https://aka.ms/prodguide-ext10) 
* [**Color output for build and debug windows**](https://aka.ms/prodguide-ext11) *(makes it easier to focus on the important parts of the code)*
* [**Productivity Power Tools 2017/2019**](https://aka.ms/prodguide-ext12)
* [**Code alignment**](https://aka.ms/prodguide-ext13)
* [**SpellChecker**](https://aka.ms/prodguide-ext14) 
* [**Provides ZenCoding for the HTML Editor - full support for static HTML, Razor and WebForms**](https://aka.ms/prodguide-ext15)
* [**Color Theme Editor**](https://aka.ms/prodguide-ext16)
* [**Generate TypeScript files from C# code files using TypeScript Templates**](https://aka.ms/prodguide-ext17) 
* [**SuperCharger**](https://aka.ms/prodguide-ext18) 
* [**Switch between themes and window layouts quickly**](https://aka.ms/prodguide-ext19)
* [**MatchMargin**](https://aka.ms/prodguide-ext20) 
* [**Add color to your Visual Studio Text Editor88**](https://aka.ms/prodguide-ext21)
* [**Roslynator**](https://aka.ms/prodguide-ext22)

### Other Docs, resources
* [**Accessibility tips and tricks**](https://aka.ms/prodguide-other1)
* [**10/28 Release Notes**](https://aka.ms/prodguide-other2)
* [**Visual Studio 2019 documentation**](https://aka.ms/prodguide-other3)
* [**Install and manage Nuget packages**](https://aka.ms/prodguide-other4) in Visual Studio
* [**Code like Scott Hanselman**](https://aka.ms/prodguide-other5)
* [**Code like Mads Kristensen**](https://aka.ms/prodguide-other6)
* [**Create a new Git repo**](https://aka.ms/prodguide-other7)
* [**VS Product Lifecycle and Servicing**](https://aka.ms/prodguide-other8)
* [**How to modify your workload**](https://aka.ms/prodguide-other9)
* [**Visual Studio main**](https://aka.ms/prodguide-other10)
* Customizing [**CMake**](https://aka.ms/prodguide-other11) settings



