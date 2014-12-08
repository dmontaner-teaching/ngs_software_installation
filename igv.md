IGV
====

It may be installed using `apt` ([see here](http://www.broadinstitute.org/igv/node/152)):

    sudo apt-get install igv

----

You can also download the binaries for the latest version form 
<http://www.broadinstitute.org/igv> 
(You will need to sign up the agreement)

Download the __Binary Distribution__, decompress and run `./igv.sh`.

Ad the file to your path.

You may also want to include an _alias_ into your `.profile` file... copying this line to it

    alias igv="igv.sh"

Alternatively you can create a symbolic link to the igv.sh file. 
Go to the uncompressed folder and type the shell command: 

    ln -s igv.sh igv
