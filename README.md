ngs_software_installation
=========================

Some tips to install NGS data analysis software



Adding files in a folder to your path
--------------------------------------

Include this line in your __.profle__ file (in your home directory)

    export PATH=path/to/the/directory/containing/binaries:$PATH

Add the new folder __at the begining__ the $PATH variable as commands are sought in left to right order in all indicated folders.

After modifying the file you will need to "reload" it doing:

    source .profile

(just up to the next time you restart your computer)


__Remarks__

- Remember that, besides being reacheable (in your path) the files to be executed have to have __execute permissions__.
- You can use the command `which` to find out the path to executable you are running and make sure that it is the appropriated version.
