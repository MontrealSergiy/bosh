Bootstrap: docker
From: ubuntu:latest

%post
    apt-get update -y
    apt-get install python3-pip -y
    pip3 install --no-cache-dir --upgrade pip
  
    # delete cache and tmp files
    apt-get clean
    apt-get autoclean 
    rm -rf /var/cache/* 
    rm -rf /tmp/* 
    rm -rf /var/tmp/*
    rm -rf /var/lib/apt/lists/* 
    
    pip install boutiques
