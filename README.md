ngs_software_installation
=========================

Some tips to install NGS data analysis software



Adding files in a folder to your path
--------------------------------------

Include this line in your __.profle__ file (in your home directory)

    export PATH=path/to/the/directory/containing/binaries:$PATH

After modifying the file you will need to "reload" it doing:

    source .profile

(just up to the next time you restart your computer)


Remember that, besides being reacheable (in your path) the files to be executed have to have __execute permissions__.
