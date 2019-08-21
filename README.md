# Feature-Branch-Example

This repository is a part of the GitHub Workflow project in the 2nd period AP CSA classroom. 

The finished document should read:
Hey, this is the project.

Hello!

Feature(D):
    This is the fourth feature of the Feature-Branch-Example project.

Feature(B):
    Hello World!
    This is Feature B! WOW!
    This is more stuff on Feature B! MORE WOW!
    Feature B is now done! YAYYYYY!

Feature(C):
    random stuff idk what this is; 

    help me;

    ap physics makes me late to csa pls dont blame me;


Feature(A)
    Blah; 
    Help;
    Me; 

    Hello;

    I don't know how to git; 
    feature(a)-commit1 what 
    
    The completed template, as on the Shared doc, is:
    
    Team Names:  Ethan Lau, Samiksha Yelthimar, Harini Gurusankar, Ritviksiddha Penchala

The completed template is:

Name of Workflow:  Feature Branch 

Description of Basic Git workflow: 
The basic Git workflow is a recommendation for how to use GIT to complete projects in a consistent and productive manner. It dictates the type of branches to set up and how to merge them. GIT Workflow uses 2 branches to record the history of a project instead of a single master branch.The develop branch serves as an integration branch to add and develop features


Description of Feature Branch workflow: (as summarized by your group)
The Feature Branch workflow focuses on features, with each feature having its own branch, independent of other features. All “Feature” branches are merged to master as they are completed. The “master” branch will never have broken code as only completed features are added to master. All features are branched from the latest update to master branch. Features are combined as they are added to master


Key Differences from basic workflow, and key use cases
While the basic git workflow allows updates through commits of the development branch, it requires strict control of the two branches since all collaborators are committing directly to the development branch. The use of the feature branch workflow allows for the rapid deployment of code as individuals work in separate features to be merged later. 

Link to your Git example repository: 
https://github.com/ritvikpen/Feature-Branch-Example/blob/master/main.txt
Note: Track main.txt

Diagram or Diagrams of workflow:


Documentation of git commands used, and annotated sample sequence of commands used in creating your repository

git init     //Initializes git
git clone https://github.com/ritvikpen/Feature-Branch-Example  //Clones repository
git fetch     //pulls changes from remote to local
git merge origin/master     //implements changes
git branch featureA         //creates branch featureA
git checkout featureA    //changes branch to featureA
git add main.txt    //adds main.txt to staging area
git commit -m “message” //commits
git push origin featureA    //pushes changes to remote origin 
