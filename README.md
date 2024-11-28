# assignment_three_part_one_acit2420

Download both generate_index and serversetup.sh.

1. Change the permission of serversetup.sh and generate_index script.
    ```bash
    chmod +x serversetup.sh
    chmod +x generate_index
    ```

2. Run the serversetup.sh script with root privelage or sudo
    ```bash
    sudo ./serversetup.sh
    ```

Digital Ocean IP Address: http://64.23.190.247/


NOTE: The command 'ufw' to setup firewall does not work due to issues with iptable in Linux kernel I have in the Digital ocean droplet. Comment out the commands under Task-5 in serversetup.sh to ignore the Firewall setup.

