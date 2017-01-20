# building

    sudo apt install build-essential git make cmake
    sudo apt install autoconf automake libtool
    
    sudo apt install libblas-dev liblapack-dev
    sudo apt install libsndfile1-dev
    
    git clone 
    cd dsd_build

    cd itpp
    mkdir build; cd build; cmake ..
    make
    
    cd ../../mbelib
    mkdir build; cd build; cmake ..
    make

    cd ../../dsd
    mkdir build; cd build; cmake .. -dLIBMBE_LIBRARY=../../../../mbelib/
    make
    
    
