Note: mainPlatypus.txt will need to be renamed and put on master/main for the merge conflict demo

Demo 1:
  Files Concerned: mainwithTypo and mainWithoutTypo (will be renamed to main.cpp on demo but named differently here for clarity sake)
  Demo adding and comitting the mainWithTypo,
  Then realize mistake and add/commit new changes in mainWithoutTypo

Demo 2:
  Files Concerned: playtpus.txt and MainPlatypus.txt
  Create branch beaver and duck from main branch (should be identical)
  On beaver create the platypus.txt file and add/commit
  To demostrate a merge (without conflicts), move to duck branch which should not have platypus.txt
  Merge duck branch
      ### ls dir to demo that duck does not currently have the file
      ### git merge beaver
      ### git log and ls to show that the platypus file has been committed to the duck branch without merge conflicts

  Demo 3:
    Files Concerned: platypus.txt and mainPlatypus.txt
    Put DoNot.. on main.master and platypus.txt on beaver
    Merging beaver into main/master will have a merge conflict to demo
    Switch to main/master and ls vim into platypus.txt to show is differetn from beavers
    Do git merge
    Show the merge conflict message
    Vi into platypus.txt on main/master
    Show git annotations and fix conflict
    Exit file and do git add to file
    Do git commit (restarts merge)
    Do git log to show commit successful

Demo 4:
  Files Concerned:  DoNotAddContainsSensitiveData.txt
  
    

      
