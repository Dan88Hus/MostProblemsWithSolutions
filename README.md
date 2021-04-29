# Most Problems With Solutions
NodeJS throws ENOSPC (Error no space) when there is not enough space available to run the application.
  
	-echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
How to turn back head in Github
  
	git reflog
  At this point, you only have to find the HEAD@{X} that you need, create a temporary branch and move to it like this:
  
	git checkout -b temp_branch HEAD@{X}
  
