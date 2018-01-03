BelarusBot init


/sbin/ip route|awk '/default/ { print $3 }'

cat ~/.ssh/id_rsa.pub | docker exec -i ssh-server /bin/bash -c "cat >> /root/.ssh/authorized_keys"