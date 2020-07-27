# Testing git commands

 * git push to origin master:whyisntthisworking ----> branch 'whyisntthisworking' created on remote repo and master got pushed to it successfully

 * git pull --rebase origin master ----> workaround for 
 
    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/SyntaxError843/MyWebsite.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally.

    pastes origin's master over local master when 'git pull origin master' fails

 * learned to never use --allow-unrelated-histories...

To be continued... 
