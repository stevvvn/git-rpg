git-rpg
=======

A minimal role-playing "game" for git. Grind out xp while you grind out bugfixes

Installation
------------

* Make sure you have ruby installed.
* Run 'make' as root to install the git-rpg executable.
* After that, in the git repo(s) you wish to use, run "git rpg init"
	* If you have an existing post-commit hook, you'll have to edit it yourself so that it runs "git rpg commit" in addition to whatever it did before
* If you wish to have one character for all the repos you use on a system, run "git rpg init --global"
* You must still run "git rpg init" in every repo you would like to use so the hook can be installed
* If you have configured a global character and you would also like one that is local to a repo, run "git rpg init --local" (both characters will receive experience for commits)

Use
---

* Use "git rpg [--global]" to see your character sheet
* Commit things normally to gain experience, levels, and hopefully something more interesting like skills or equipment one of these days.
* Use "git rpg reset [--global]" to clear data in your git settings related to the game.
