# Sentinel-LDK-Downloadable-Files

This directory includes all the files that are required for running sentinel LDK Samples. Eg. Runtime, Sample, libraries etc


==============

# Checkout branch Runtime to access the downldable runtime files

  git checkout Runtime


# This branch also includes the License Manager configuration file(hasplm.ini)


# Install the runtime useing command

  sudo dpkg -i <runtime_file_name>

  
# When you install the runtime, it also installs the license manager that can be accessed at 

  http://localhost:1947


# You need to copy the hasplm.ini file to /etc/hasplm if not already copied


# You can use the following credentials to log into the license manager

  Username  :  admin
  Password  : Admin@123
