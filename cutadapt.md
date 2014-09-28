Install cutadapt
================

The latest version (__1.5__ when I wrote this) is available at: 
<https://github.com/marcelm/cutadapt>


Dependencies
------------

    sudo apt-get install python-dev
    sudo apt-get install cython 
    sudo apt-get install cython-dbg cython-doc   # I am not sure this is needed 


Build
----------------

    tar -xzvf cutadapt-1.5.tar.gz 
    cd cutadapt-1.5/
    
    python setup.py build
    python setup.py build_ext -i
    
    cp bin/_preamble.py build/scripts-2.7/

