dockerfile-debade-master
========================

    docker pull pihizi/debade-master
    docker run --name pihizi-debade-master \
        --dns 172.17.42.1 \
        -v /dev/log:/dev/log \
        -v /var/log/debade:/var/log/debade \
        -p 9090:80 \
        -d pihizi/debade-master
