cat ~/.ssh/id_dsa.pub | ssh root@xxxx "umask 077; mkdir -p .ssh ; cat >> .ssh/authorized_keys"
