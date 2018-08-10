Sublime Text 3 optimized for Python Develompent
-------------------------------------------------

PACKAGES
----------
1) SideBarEnhancements
2) NeoVintageous (for Vim emulation)
3) SublimeLinter
4) SublimeLinter-flake8
5) Material Theme (used part of it)
6) SpaceGray Theme (my favorite)
7) A file icon (icons in the sidebar)
8) BracketHighlighter
9) PackageResourceViewer
10) Dayle Rees Colorschemes


If you want to use my settings feel free to do so .
Just place them in your  /Packages/User folder , restart Sublime and  that's it.
The only file that must be placed in /Packages/Python is the Completion Rules.tmPreferences .
That is so because Anaconda had the "import" keyword in the regex inside the file and many users have problems with autocompletion after using the import keyword.
 Also i use a custom Python3 build system so i can set the settings i want through the building process.
 Of course python interpreter path is different so this is the only modification you need according to your system path (system, virtualenv).


