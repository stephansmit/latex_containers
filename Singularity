Bootstrap: docker
From: ubuntu:16.04

%post
    apt-get update && apt-get install -y texlive-full texmaker

%apprun texmaker
    exec /usr/bin/texmaker

%runscript
    exec '$@' 
