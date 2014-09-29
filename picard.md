Picard tools
============

May be installed using `apt`: 

    sudo apt-get install picard-tools


Then you can use it as:

    picard-tools COMMAND [OPTION]...


for instance: 

    piccard-tools AddOrReplaceReadGroups INPUTFILE


----

You can download all __java__ executables form  
<https://github.com/broadinstitute/picard/releases>

and execute each of them doing:

    java -jar NAME_OF_THE_EXECUTABLE

for instance:

    java -jar AddCommentsToBam.jar

