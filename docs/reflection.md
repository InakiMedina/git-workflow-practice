first PR: 
feature/initial-structure -> main
https://github.com/InakiMedina/git-workflow-practice/pull/1
![alt text](<Screenshot 2026-08-31 182744.png>)

second PR
feature/add-content -> main
https://github.com/InakiMedina/git-workflow-practice/pull/2
![alt text](image.png)

note: in second pr, i forgot to push two commits, so i tried to revert second pr. Which was a very bad idea. 

third PR
revert second PR
https://github.com/InakiMedina/git-workflow-practice/pull/3
![alt text](image-1.png)

fourth PR
feature/add-content -> main (redo second PR)
https://github.com/InakiMedina/git-workflow-practice/pull/4
![alt text](image-2.png)

note: this pr was never accepted, since the main had reverted to a wrong commit and both branches couldn't be merged. To fix this, i reseted the feature branch to the correct commit and the reseted main to the feature branch



