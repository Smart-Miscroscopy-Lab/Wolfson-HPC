# Wolfson-HPC
How to run and get set up on the wolfson HPC

1) Login to HPC through thinlinc

2) **Install Conda with**
   wget https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh

   **then run**
   
   bash Anaconda3-2022.05-Linux-x86_64.sh
   
   **then grab the file from the source**
   
   source /home/<profile-name>/anaconda3/bin/activate

3) **Create a conda env**

   conda create --name <what name you want to call it>

   **Activate you enviroment**

   conda activate <env_name>

4) **Install what packages you want**

   conda install numpy ......
   
