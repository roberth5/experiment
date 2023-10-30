# Experiment

This project is an empty project that I am using 2023-10-26 to test upstreaming in multiple locations.

## What I Did

1. I created this project on my work GitHub account and cloned it to my computer.
	
	The project at this point only has the one remote (most likely titled "origin"). You can see the list of remotes by running the command ```git remote``` in your project's folder.

2. I created another Empty Project on a self-host GitLab server with no README (a *completely empty* project).

3. On my local copy of the GitHub project, I ran the following command:

	```
	git remote add backup https://gitlab.centralfireplace.com/path/whateverproject.git
	```

	Now if you run the ```git remote``` command, you'll see two remotes.

4. So GitHub Desktop sees the remote, but won't let me switch to it because "A branch with that name already exists". I tried VS Code and it has the option to "Push to..." a specific remote and it works, but it's just as easy to run ```git push backup```. The only problem is that it's a manual process and I'll need to *remember* to do it.

	There may be ways/work-arounds to do it though...

Nevermind, let's try something else!