# Mission_Files_Webpage

I have extracted this webpage code from a private project as a code 
demonstrator. The unusual syntax in the html file is syntax for a 
python template generator tool named Jinja. The html essentially 
serves as a fillable slate for the JavaScript, which has the primary 
responsibility for constructing the page.

The current implementation stores mission file data as JSON objects, 
though this is expected to change later to pull from our backend 
database. Either way, the script uses the data to build formatted 
'cards' for each mission containing useful summary data and linked 
files with all of the mission's information. A table of contents 
allows quick browsing by title and links to the cards, while a 
searchbar above enables finding particular cards, or cards with 
particular characteristics in any of the summary fields. The script 
makes heavy use of the JQuery library.

The various css snippets are Bootstrap classes. Both Bootstrap and 
JQuery are part of the template Jinja imports in line 1 of the html.
