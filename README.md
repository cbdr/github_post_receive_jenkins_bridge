# GitHub Post Commit Jenkins Bridge
This is a small ruby app that will listen for github callbacks and parse out certain parameters that are required for our jenkins builds.  Why not use the github jenkins plugin?  I could not reliably get information about the branch durring certain kinds of fast forward merges.  This server will parse the last commit and use that as the basis of the branch (the git command to the equivilant does not lists in alpahbetical order where github posts to me in date order)

For more details please see the following guide on GitHub:
http://help.github.com/post-receive-hooks

And please, take a look at the source, that's what it's there for.
