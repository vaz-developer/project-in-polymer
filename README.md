# My first project with bower #

1. Create a new folder in htdocs with the name of project
2. Open terminal
3. In terminal,position in the folder of project
4. Create a new element with termination .html, in my case index.html
5. If to use POLYMER go to the link https://elements.polymer-project.org
6. For my project, I will use paper element --> paper-drawer-panel 
7. Copy the second section of the component paper-drawer
8. Also, copy bower command that is to the left in the bar
9. Paste in the body of the index.html
10. If to use, material design paste in the head and in the body: "https://code.getmdl.io/1.2.1/material.indigo-pink.min.css" and "https://code.getmdl.io/1.2.1/material.min.js"
13. Create folder with the command: bower init 
14. NOTE: will be create a folder called bower.json
15. Save material design in bower with the command: bower install material-design-lite --save
16. NOTE: will be save in bower.json
17. Link in the index.html file from the bower_components folder as we take the element in the polymer with rel="import"
18. To create a toolbar, search in the page of polymer, paper elements --> paper tool
19. Copy the first option
20. Copy in the toolbar main
21. Link the corresponding librarys in the head
22. Go to the terminal 

### HEAD CLEAN ###
1. Create a new element .html with the name elements
2. Put all imports in this new element
3. Redirect in the head of the index.html

### INSTALL EXTRAS DEPENDENCIES(BOOSTRAP,JQUERY,ETC.) ###
1.  bower install (package) --save
  
### CUSTOM STYLES IN POLYMER ###
1. with is="custom-style" styles applies to polymer
 <style is="custom-style"></style>

### RESOURCES ###
1. https://getmdl.io/components/index.html#layout-section
2. https://getmdl.io/started/
3. https://bower.io/docs/creating-packages/
