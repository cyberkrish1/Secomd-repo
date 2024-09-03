<h1>Branch</h1>

<p>A branch is a version of the repository that diverges from the main working project.
It is a feature available in most modern version control systems. A Git project can have
more than one branch. These branches are a pointer to a snapshot of your changes. When you 
want to add a new feature or fix a bug, you spawn a new branch to summarize your changes. 
So, it is complex to merge the unstable code with the main code base and also facilitates
you to clean up your future history before merging with the main branch.
</p>

<h2>Operation On Branch</h2>

<p>We can perform various operations on Git branches. The git branch command allows you to create,
list, rename and delete branches. Many operations on branches are applied by git checkout and git
merge command. So, the git branch is tightly integrated with the git checkout and git merge commands.</p>

<h2>Commands</h2>
<p>To Check Branch: git branch</p>
<p>To rename branch:git branch -M main</p>
<p>To naviagte (move from one brnach to other):git checkout <-branch name-> </p>
<p>To create new branch: git -b<new branch> </p>
<p>To delete branch: git branch -d <branch name> </p>
<p>when we want to push to specific branch we use command git push origin feature name.</p>

<h2>Merging code</h2>
<p>To compare commits,branches,etc git diff <-branch name-></p>
<p>To Merge branches git merge <-branch name-></p>
<p>WE can also merge branches by PR request (Pull Request) using github</p>