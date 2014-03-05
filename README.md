[Norton Imperial Labs](http://nortonimperiallabs.org/):  An imperial proclamation for creative collaboration
==========================================================================

Norton Imperial Laboratories exists to provide a space where interesting
people collaborate to write on the world in the ink of their
imagination.

NIL strives to inspire collaboration, creativity, and passion in the San Francisco community by:

* Fostering an open, collaborative space 
* Providing a safe, clean and inclusive work environment
* Teaching and helping others

Current avenues of communication:
---------------------------------

* [Weekly meatspace meetings](https://github.com/nortonimperiallabs/nortonimperiallabs/blob/master/announcements/weeklyMeetings.md) for decision-making
* ##\#SFNIL on freenode for real-time discussion
* [Google group](https://groups.google.com/forum/#!forum/sfhackerspace) for asynchronous discussion
* [Wiki](http://wiki.nortonimperiallabs.org/) for asynchronous temporary content
* [@NIL/NIL github repository](https://github.com/nortonimperiallabs/nortonimperiallabs) for persistent content

Getting started:
================

Branching rules for this repo:
----------------------------------

**Note: Temporary as of 2014 03 04, needed as interim before finalizing at next weekly meeting.**  Rules adapted from [this post](http://nvie.com/posts/a-successful-git-branching-model/).  These are not currently enforced by hooks.

* Commits to master should represent finalized content.  Please do not commit working copies to master.  **Changes to master should be discussed at weekly meetings prior to merging.**
* For changes relating to specific action items from weekly meetings, create a private branch in @NIL/NIL/dev/ for your work.  For example, Badg created @NIL/NIL/dev/bylaws to work on his assigned action items from the 2014 03 03 meeting.
	* Collaborators should submit suggestions to private branches.  For example, rrix might add suggestions in @NIL/NIL/dev/bylaws/rrix
	* The action item assignee (in this example, Badg) is free to adopt or ignore those suggestions
	* Specific action-item development branches may be merged directly to master
* For changes unrelated to specific action items, create a private branch in @NIL/NIL/unassigned/ for your work.  For example, Badg might create @NIL/NIL/unassigned/procedures to draft a procedure for lathe access control.
	* Unassigned branches *may* be **courteously** merged into by others.  The creator of the branch has every right to revert those commits.
	* Unassigned branches should not be merged directly into master, but should first be merged into the intermediate @NIL/NIL/development branch
	* Pending changes on the catch-all @NIL/NIL/development branch will be discussed at weekly meetings.