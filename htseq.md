HTSeq
=====

Dependencies
------------

    sudo apt-get install python-setuptools # needed for the installation
    sudo apt-get install build-essential python2.7-dev python-numpy python-matplotlib

The [htseq-count](http://www-huber.embl.de/users/anders/HTSeq/doc/count.html) script can be used as a standalone tool to compute read counts.
It is dependent on [pysam](https://github.com/pysam-developers/pysam), a Python wrapper to [SAMtools](http://samtools.sourceforge.net/).

`pysam` can be installed doing: 

    sudo apt-get install python-pip 
    sudo pip install pysam

Note: The first of this lines installs [pip](https://pypi.python.org/pypi/pip)
_a tool for installing and managing Python packages_.






Form repositories
-----------------

    sudo apt-get install python-htseq python-htseq-doc


Form sources
------------

Download form <https://pypi.python.org/pypi/HTSeq> and compress.

Then 

    python setup.py install --user

This will create the folder `builds/cripts-2.7/`. Add it to your path.


See 
<http://www-huber.embl.de/HTSeq/doc/install.html#install>
for further details.
