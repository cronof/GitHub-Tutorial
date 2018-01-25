# GitHub-Tutorial :page_facing_up: :yum: :grey_exclamation:
---------------------------------
## create a new repository on the command line 
* ![alt text](http://student.coe.phuket.psu.ac.th/~s5635512088/images/github1.PNG)
* ![alt text](http://student.coe.phuket.psu.ac.th/~s5635512088/images/github2.PNG)
---------------------------------
## Text on command
<dl>
	<dt> (frist time) </dt>
		<dd>:one: git init</dd>
		<dd>:two: git config --global user.email "xxx"</dd>
		<dd>:three: git config --global user.name "xxx"</dd>
		<dd>:four: echo "# Something" >> README.md</dd>
		<dd>:five: git add README.md</dd>
		<dd>:six: git commit -m "first commit"</dd>
		<dd>:seven: git remote add origin Your link, Exam "https://github.com/cronof/GitHub-Tutorial.git"</dd>
		<dd>:eight: git push -u origin master</dd>
</dl>
<dl>
  	<dt> (next time) </dt>
  		<dd>:one: git add README.md</dd>
		<dd>:two: git commit -m "first commit"</dd>
		<dd>:three: git push</dd>
</dl>


## Homework 2
> create 2 branchs (dev/dev.md, feature/feature.md) and move all to master branch

<dl>
	<dt> (frist time) </dt>
		<dd>:one: git branch newBranchName            ;create a new branch.</dd> 
		<dd> .....or git checkout -b newBranchName    ;create and move to new branch</dd>
		<dd>:two: make file.md in 2 branchs your created </dd>
		<dd>:three: git add .                    ;choose all in branch </dd>
		<dd>:four: git commit -m "..."		 ;make all file your added to local repository</dd>
		<dd>:five: git push -u origin branchName	 ;push file to github server or your target </dd>
		<dd>:six: git checkout master           ;switch to master branch</dd>
		<dd>:seven: git merge branchName          ;get all file in branchName to master branch</dd>
		<dd>:eight: repeat step 3-5 </dd>
		
</dl>



| ID             | NAME             | FACUTY               |
| -------------- |:----------------:| -------------------- |
| 5635512088     | Mr.Apinun Konru  | Computer Engineering |



> GitHub-Tutorial is a textbook or webpage
> for learn by your self.
> Goodluck.