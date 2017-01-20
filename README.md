# GTM960

sudo apt-add-repository ppa:graphics-drivers/ppa                                                                                                 
sudo apt-get update                                                                                                                                                                                                                  
sudo apt-get install nvidia-364 nvidia-prime

software and updates

nvidia-xconfig                                                                             
nvidia-settings                                                                            

sudo apt-get install mesa-utils                                                                
 
glxdemo   glxgears  glxheads  glxinfo 

$lspci | grep -i nvidia
------------------------------------------------------------------------------------------

http://docs.nvidia.com/cuda/cuda-quick-start-guide/#ubuntu-ppc64le
------------------------------------------------------------------------------------------------------------
$ sudo dpkg --install cuda-repo-<distro>-<version>.<architecture>.deb                                                                           
$ sudo apt-get update                                                                           

$ sudo apt-get install cuda                                                                           

Reboot the system to load the NVIDIA drivers.
Set up the development environment by modifying the PATH and LD_LIBRARY_PATH variables:                                                                           

$ export PATH=/usr/local/cuda-8.0/bin${PATH:+:${PATH}}                                                                           

$ export LD_LIBRARY_PATH=/usr/local/cuda-8.0/lib64\
                         ${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}                                                                           

Install a writable copy of the samples then build and run the vectorAdd sample:                                                                           

$ cuda-install-samples-8.0.sh ~                                                                           

$ cd ~/NVIDIA_CUDA-8.0_Samples/0_Simple/vectorAdd                                                                           

$ make                                                                           

$ ./vectorAdd                                                                           



Read more at: http://docs.nvidia.com/cuda/cuda-quick-start-guide/index.html#ixzz4VYncmuwr 
Follow us: @GPUComputing on Twitter | NVIDIA on Facebook


