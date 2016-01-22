# simulators

### simspark
 1 - Install the necessary tools: 
 
    sudo apt-get install build-essential synaptic subversion cmake gzip -y
 
 2 - Install the necessary libraries:
 
    sudo apt-get install ruby-dev libfreetype6-dev libboost1.55-dev libboost-system1.55-dev libboost-regex1.55-dev libboost-thread1.55-dev libdevil-dev libode-dev libglu1-mesa-dev libsdl1.2-dev libboost-atomic1.55-dev libboost-chrono1.55-dev libboost-date-time1.55-dev libboost-serialization1.55-dev -y
 
 3 - Download the SimSpark files:
 
    svn checkout svn://svn.code.sf.net/p/simspark/svn/trunk simspark
  
 4- Installing the SimSpark: 
 
    cd simspark/spark
    
    mkdir build
    
    cd build
    
    cmake ..
    
    make
    
    sudo make install

 4 - Installing the SimSpark Soccer Server:
 
    cd ../../rcssserver3d
    
    mkdir build
    
    cd build
    
    cmake ..
    
    make
    
    sudo make install
 5 - Testing:
 
    rcsoccersim3d
