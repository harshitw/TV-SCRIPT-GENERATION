# TV-SCRIPT-GENERATION

# Udacity Project 3
Generation of tv scripts using rnn's of simpsons tv show.

# Setup for the project 

1. cd ~/Desktop/
2. ssh -i yourkeyname ubuntu@ip_address
3. jupyter notebook --generate-config 
4. sed -ie "s/#c.NotebookApp.ip = 'localhost'/#c.NotebookApp.ip = '*'/g" ~/.jupyter/jupyter_notebook_config.py
5. git clone https://github.com/udacity/deep-learning.git
6. cd tv-script-generation
7. conda create -n script python=3.5
8. source activate script 
9. conda install pandas matplotlib jupyter notebook scipy scikit-learn 
10. conda install -c conda-forge tensorflow-gpu=1.1
11. conda install -c conda-forge tqdm 


Before step 7, if you don't have anaconda installed and you are using aws to for GPU usage, then install conda from this site:
https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-16-04

Follow the following steps :
cd /tmp
curl -O https://repo.continuum.io/archive/Anaconda3-5.0.1-Linux-x86_64.sh
sha256sum Anaconda3-5.0.1-Linux-x86_64.sh
bash Anaconda3-5.0.1-Linux-x86_64.sh
press enter to continue
To approve the liscence press yes
Press enter
Press yes so that you can use conda command 
source ~/.bashrc // this command is used for activating installation

Open in new terminal to see the changes, and repeat the above setup and subsequently create virtual environment for your system.
