telnet autologin for Juniper, Cisco, Huawei, Huawei OLT, SNR, Eltex

git clone https://github.com/thrve/pseudo_telnet.git && mv pseudo_telnet/pseudo_telnet .local/bin 

in ~/.*rc:

alias telnet='LOGIN=my_login PASSWORD=my_password pseudo_telnet'

