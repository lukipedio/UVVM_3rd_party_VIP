# ***  UNDER CONSTRUCTION - TO BE RELEASED WEEK 18  ***

# UVVM 3rd party VIP (Verification IP) Repository

## Type of verification IP
This repository is provided to give an overview of all available UVVM compatible Verification IP (VIP).
- BFM: BFM packages only (with no VVC)
- VVC: Complete VVCs, with built-in BFMs for interface/protocol oriented interfaces
- Any other verification IP that could be useful.

## Opens source and commercial
This overview will include free, open source VIP, but also commercial VIP. The intention here to get a full overview. The users can make their choice whether they want commercial or Open source VIP

## Submitting VIPs 
To submit your VIP to this repository, please send an email with a link to the VIP to the UVVM team (support@bitvis.no).
We will then link to your VIP in the list below. If you link to a Git Repository, you can choose whether to link to a specific branch, or to the master branch of your repository.
Bitvis and the UVVM team will not verify or control the quality of submitted VIP as we are not experts on every single interface or protocol ;-)   
It will be up to the community to give feedback on the various VIP.

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

