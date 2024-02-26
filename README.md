This repository is another password manager. 


**INSTALL**

To use password-manager first you have to download it. Do so by running the following commands:

sudo apt install git
git clone https://github.com/SmallCoder13/password-manager

now that you have the files, go into the folder containing the files by running the following command:

cd password-manager

Next, we need to make the install file exucutable and run it. Do so by running the following command:

chmod +x install
./install

Now that we have password-manager install, we need to unzip the .zip file. Do so by running the following command:

unzip password-manager.zip

Now you should have a folder call password-manager-start. Go into this folder using the cd command used eariler. The last step is to run the password-manager. Do so by running the following command:

python3 main.py

If the above command returns python3: command not found. You can fix this by running the following command:

sudo apt install python3
