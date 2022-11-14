start ./view.sh
open page on browser
when changes ok, then ./submit-to-git.sh

Add news
- go to content/home
- edit news.md

Update my bio and about me
- go to content/authors/mbarcell home
- edit _index.md

Changes to people
- go to "content/authors"
- to add student
	- add folder with name
	- add _index.md file
	- add photo with avatar.jpg
- edit student
	- go to corresponding folder
	- edit _index.md file
- remove student
	- remove folder (zip it)

Add publication
- go to "content/publications"
- to add paper
	- add folder with name yyyy-vehicle-surnamefirstauthor
	- add _index.md file
	- add photo with avatar.jpg
	
Change Teaching information
- go to content/home
- edit teaching.md

To create new menu
- go to to content
- copy service to newmenu
- edit _index.md to update title
- go to config/_default
- edit menus.toml to add the specific menu (order according to weight value) 
