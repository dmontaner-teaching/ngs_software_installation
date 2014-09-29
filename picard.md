Picard tools
============

May be installed using `apt`: 

    sudo apt-get install picard-tools


Then you can use it as:

    picard-tools COMMAND [OPTION]...


for instance: 

    piccard-tools AddOrReplaceReadGroups INPUTFILE


that is why __THIS IS THE ONLY TOOL I PREFER TO INSTALL USING__ `apt` and not form sources or binaries.


----

You can download all __java__ executables form  
<https://github.com/broadinstitute/picard/releases>

and execute each of them doing:

    java -jar NAME_OF_THE_EXECUTABLE

for instance:

    java -jar AddCommentsToBam.jar

