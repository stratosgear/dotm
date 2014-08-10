#Dot File Manager
The Dot File Manager is a tool to keep track of all or some of the dot files stored in a users home directory or sub directories. This is accomplished by putting all files that need to be tracked in a specific version controlled directory (~/dotfiles by default). Then symlinks are created in the users home directory to point to all of the files in the specified dot directory. For more information about this approach I suggest reading [Using Git to Manage Your Dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/) which gives a basic overview of the approach used here.


## Example setup
For an explanation of how to use this script file look at a [skeleton project repo](https://github.com/stratosgear/dotm_skeleton) that you can clone/fork and use it as a base for your github backed up dotfiles.

### Origin of this script
This script is shamellesly copied from another github project from https://github.com/brettbatie/dotfiles.

This is my attempt to extract the script from the dotfiles directory structure (once again, look at the dotm_skeleton project on how it is used) and have an easy way to externally update the script, using standard git practices, while still using it in my dotfiles projects.

Hopefully the dotm script should be released and maintained by [Brett Batie](https://github.com/brettbatie) himself, as the original author, if he thinks that the current setup is to his liking.

I claim absolutely NO credit for the nice work he has done.  I only did some minor repackaging.