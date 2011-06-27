## USAGE  
        
# Steps:

[1] Clone this repo in your local machine and then checkout the 'gh-pages' branch :
		
		git clone git@github.com:sprout/sprout.github.com.git
		cd sprout.github.com
		git checkout -t origin/gh-pages

[2] Install the jekyll gem `gem install jekyll rdiscount` if not already installed in your system and Fire up the server
		
		jekyll --server --auto
		
[3] Start working/changing the content. 

[4] Check the changes in your local browser.

		localhost:4000

[5] Add the changes to git then commit.

		git add .
		git commit -m "<message>" 
		
[6] Push the changes to the 'gh-pages' branches.
		
		git push origin gh-pages  
		
		




