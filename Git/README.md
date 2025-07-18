/*
 * @author "Somya Vats"
 *
 * This contains basic understandable content for 
 * introductory Git workings.
 * Follow this if and only if new to git workflow. 
 * Else Skip (for intermediate User's)
 *
 * @License "Copyleft License"
 *
 * <b>Author is not resposible for redestribution of the Files.</b>
 *
 *****************************/

 This file includes:

 1.1  Internals
 1.2  Config
 1.3  Branching 
 1.4  Merge 
 1.5  Rebase
 1.6  Reset 
 1.7  Remote
 1.8  Github
 1.9  Gitignore

 For more Informations, use Manual:
        $ man git

        Shortcuts (while using Linux man pages):
            q       (quits the manual)
            j       (one line down)
            k       (one line up)
            d       (Half page down)
            u       (Half page up)
            /<term> (Search for "term")
            n       (Next Search term)
            N       (Previous Search term)


 system ( /etc/gitconfig ):          all users on the system
 ------

 global ( ~/.gitconfig ):            for all projects
 ------

 local ( .git/config ):              for a specific project
 -----

 worktree ( .git/config.worktree ):  for a part of the project
 --------

 Tip: Always add "init.defaultBranch" to either main, master or trunk etc.