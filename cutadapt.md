Build cutadapt
================

The latest version (__1.5__ when I wrote this) is available at: 
<https://github.com/marcelm/cutadapt>


It comes with a compiled `bin/cutadapt` which may be used directly. 
If it does not work you will need to _build_ it.


Dependencies
------------

    sudo apt-get install python-dev
    sudo apt-get install cython 
    sudo apt-get install cython-dbg cython-doc   # I am not sure this is needed 


<!--
http://cython.org/#download

-->


Build
----------------

    tar -xzvf cutadapt-1.5.tar.gz 
    cd cutadapt-1.5/
    
    python setup.py build
    python setup.py build_ext -i               # -i is just for verbose output
    
    cp bin/_preamble.py build/scripts-2.7/     # this is needed for a custom installation


Then the script 

    build/scripts-2.7/cutadapt
    
seems to work fine. 
You can direclty call it or include it in your path.



Note
--------------------

Do not remove the `bin/cutadapt` file in the original bin directory. It seems to be used during the `python setup.py`

