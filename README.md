<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/64286155-c485af80-cf11-11e9-903f-201622cf6ead.png">
  <br />
  buildah
</h1>

<p align="center"><b>This is the snap for  buildah, a tool that facilitates building OCI images.</p>

## Install Snapd

    Ubuntu/Debian: sudo snap install snapd
    
    Fedora: sudo dnf install snapd
       
To enable classic snap support for Fedora, enter the following to create a 
symbolic link between /var/lib/snapd/snap and /snap: 

     sudo ln -s /var/lib/snapd/snap /snap

## Install Snap

    Ubuntu/Debian: sudo snap snap install buildah --edge --classic
     
    Fedora: sudo snap install buildah --classic 
    
    
