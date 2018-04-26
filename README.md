# ***  UNDER CONSTRUCTION - TO BE RELEASED WEEK 18  ***

# UVVM Contributions Repository

This repository was created to facilitate user contributions of user IPs, e.g. BFMs or complete Verification IPs (VIPs) with BFM and VVC.

# Contributor info
## Uploading IPs 
To submit your IP to the UVVM Contributions repository, please send an email with a link to the git-repository where the IP is uploaded to the UVVM team (support@bitvis.no).
We will then link to your IP as a submodule in the UVVM Contributions Git Repository. You can specify if you want us to link to a specific branch, or to the master branch of your repository.
Bitvis and the UVVM team will not verify or control the quality of submitted IPs, but some rules must be followed in order for the IP to be accepted.

## Rules
* VHDL only
* The standard UVVM directory structure shall be followed when applicable
* The IP shall be documented
* A completed submission form shall be uploaded with the IP (see submission_form.xls in the repository)
* The code shall compile with a version of UVVM specified in the submission form. This implies that it shall be possible to use the IP in the same testbench as any other of the UVVM components. 


# User info
## Downloading submodules
When using the Download ZIP function in Github, the submodules in the repository are not included. This will hopefully change with time. 
In the meantime, users can download the submodules in either of the following ways:
1. Open the submodule git-repositories in Github and download each of them one by one.
2. Use Git to clone the UVVM Contributions repository, but with the recursive flag. 
   For Git versions up to 2.12 use --recursive, for Git versions above 2.13 use --recursive-submodules. 
   For version of Git above 1.9 it is recommended to use the -j8 flag to improve performance.
   If the UVVM External repository has already been cloned without the recursive flag, the submodules can be fetched by using "git submodule update --init --recursive"


Our hope is that this repository will bring the community together in order to speed up the verification process for all users.

