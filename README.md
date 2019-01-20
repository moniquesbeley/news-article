At the start of the coding bootcamp I enrolled in, we were tasked with emulating a basic CSS and HTML news article. Below I will walk you through the steps I took to acchomplish this and also, I have attached a link to view the "finished" product.

The first thing I did was navigate to my apporpreiate folder via terminal, 
$ cd /applications/mamp/htdocs
Clone the news-article assignment into your htdocs folder with the following command:
$ git clone https://github.com/SJCCodeTalk/news-article.git
Change your directory to the project folder.
$ cd news-article
Remove Codetalk as the origin of the project with the following command.
$ git remote rm origin
Navigate to github.com's main page and select "Start a project". Name your project "news-article" and select, "Create repository." Copy and paste the commands from the following page to get your repository connected.

Create your project

Upload your project by taking the following steps

$ git add .
NOTE: "." is a wildcard meaning add all changes that have happened rather than stating one specific file.

$ git commit -m "add message here"
NOTE: "add message here" should be updated to give a description as to what you did, such as, "completed assignment", "updated readme", "made changes to header"

$ git push
Updated the readme file with a description of your project so that future employers or other students know what your objective for this project was.
click here to view final project http://htmlpreview.github.io/?https://github.com/moniquesbeley/news-article/blob/master/news-article.html
