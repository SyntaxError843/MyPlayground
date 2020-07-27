# Testing git commands

 * git push to origin master:whyisntthisworking ----> branch 'whyisntthisworking' created on remote repo and master got pushed to it successfully

 * git pull --rebase origin master ----> workaround for 
 
    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/SyntaxError843/MyWebsite.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally.

    pastes origin's master over local master when 'git pull origin master' fails
 
 * apparently --rebase makes a new branch that isnt master and cant get pushed anywhere
 
 * what
 
 * learned to never use --allow-unrelated-histories...
 
 * note: learn what --rebase does and dont copy paste off forms
 
 * what is even happening man
 
 * somehow merged new temp rebased branch with local master and successfully pushed to remote gitTest branch
 
      command looked smth like 'git push origin master:gitTest'
 
 * note to self: go to master and then git merge with other branches maybe? i dont know
 
 * pull request successful...?
