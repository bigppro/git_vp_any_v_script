# git_vp_ov12_script
Git odoo v12 instalation personalized script

#!/bin/bash
################################################################################
# Script for installing Odoo on Ubuntu 14.04, 15.04, 16.04 and 18.04 (could be used for other version too)
# Author: Yenthe Van Ginneken
#-------------------------------------------------------------------------------
# This script will install Odoo on your Ubuntu 16.04 server. It can install multiple Odoo instances
# in one Ubuntu because of the different xmlrpc_ports
#-------------------------------------------------------------------------------
# Make a new file:
# sudo nano git_odoo_install.sh
# Place this content in it and then make the file executable:
# sudo chmod +x git_odoo_install.sh
# Execute the script to install Odoo:
# ./git_odoo_install.sh

# answer for odoo version, webpage and mail.
