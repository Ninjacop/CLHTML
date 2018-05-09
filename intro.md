

# HOW TO GO ABOUT THE HTML GENERATOR

## Basics

### Create 1 .html file in your Home folder

(page 'name "title" "text")

The " ' " (quote) before "name" HAS to be there or else you will get an error

## Site Creation

### Create multiple Pages
(defitem name "title" "text") - same thing as "page", but you can make them in bulk

### Create a Section to store all your Pages
(defsection name item1 item2... ) - groups item(s) declared by "defitem"

### Create a Site that bundles up all the Sections
(defsite section1 section2...) - groups section(s) declared by "defsection"

## Generate your Site - All the linked .html pages will be in your Home directory
(gen-site) 


If you want to move the site to a different folder, you have to change the path by going inside the html files and changing the paths there. 


Thanks for using my Generator!