git-rpg
=======

A minimal role-playing "game" for git. Grind out xp while you grind out bugfixes

Installation
------------

* Make sure you have ruby installed.
* Run 'make' as root to install the git-rpg executable.
* After that, in the git repo(s) you wish to use, run "git rpg init"
	* If you have an existing post-commit hook, you'll have to edit it yourself so that it runs "git rpg commit" in addition to whatever it did before

Use
---

* Use "git rpg" to see your character sheet
* Commit things normally to gain experience, levels, and hopefully something more interesting like skills or equipment one of these days.
* Use "git rpg reset" to clear all data in your git settings related to the game.
