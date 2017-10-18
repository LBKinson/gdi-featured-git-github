## History
# Concurrent Version Systems (1990s)
+ developed by Dick Grune in 1986 as a series of shell scripts
+ was released as a Revision Control System that managed individual files but not whole projects
+ latest release was May 8, 2008

# SVN (Apache Subversion, 2000s)
+ developed by CollabNet, a software and devops company, in 2000 and publically released in 2004 and every year since then
+ because CollabNet owns and operates SVN (vs Git which is opensource), legacy problems snuck up like size (SVN used to be huge compared to Git, now they're about the same), spacing (SVN branches can be a bit more costly than Git's), and dexterity (you're required to manually specify a lot more details than with Git)
+ latest release was July 26, 2017 so this one is still a viable option!

# Git (2005)
+ open source! what does this mean? developed in a collaborative and public manner -- holds contributors accountable and allows anyone to change and update code
+ free software distributed under the terms of the GNU General Public License which promotes the creation and use of free software
+ development began in 2005 after a popular version control system, BitKeeper, was withdrawn from free use by the copyright holder, Larry McVoy

# Linus Torvalds
+ creator and long-time principal developer of the Linux kernel, which became the kernel for operating systems such as Linux OS, Android, and Chrome
+ wanted a distributed system that he could use like BitKeeper, but couldn't find an available free service that met his needs
+ had three tenets of developing Git, one of which was "Take CVS as an example of what not to do; if in doubt, make the exact opposite decision"
+ decided on the name Git, which means unpleasant person in British English slang, by saying that, "[he is] an egotistical bastard, and [he names] all [his] projects after [hisself], first Linux, now Git"
+ began development on April 3, 2005; announced the project on April 6; it became self-hosting on April 7; first merge of multiple branches occurred on April 18
+ Torvalds turned over maintenance on July 26, 2005 to Junio Hamano, a major contributor to the project, who remains the project's maintainer


## Version Control Types
# Centralized Version Control: CVS, SVN, Perforce

# Distributed Version Control: Git, Mercurial

# Main differences
+ Centralized VCSs keep the history of changes on a central server from which everyone requests the latest version of the work and pushes the latest changes to
+ Centralized: This means that everyone sharing the server also shares everyone’s work
+ on a Distributed VCS, everyone has a local copy of the entire work’s history. This means that it is not necessary to be online to change revisions or add changes to the work. “Distributed” comes from the fact that there isn’t a central entity in charge of the work’s history, so that anyone can sync with any other team member.
+ Distributed:  This helps avoid failure due to a crash of the central versioning server. 
