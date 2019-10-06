# FullLinuxBackup
a python script can make full Linux Os backup with all system file

## How it's work
the script exuctute some cmd to create archive tar file of your root.it can be restored using linux system.
it's like you execute the following comands:


  cd /


To create backup:


  sudo tar -cvpzf backup.tar.gz --exclude=/backup.tar.gz --one-file-system /
  
  
To restore:


  sudo tar -xvpzf /path/to/backup.tar.gz -C /restore/location --numeric-owner
