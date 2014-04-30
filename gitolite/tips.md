# Gitolite

## Add Local Repo to Gitolite
1. First add an entry in your gitolite-admin/conf/gitolite.conf
> repo reponame  
> RW+ = @admins @oiraservs
    
2. Assuming you have a local repo all ready, then:  
> $ cd REPONAME    
> $ git init    
> $ git add .  
> $ git commit -m 'initial commit' -a  
> $ git remote add origin git@YOUR_SERVER_HOSTNAME:REPONAME  
> $ git push origin master

