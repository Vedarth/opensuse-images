FROM vedarth/sles

RUN     zypper update -y && \
        zypper install -y python3-devel gcc gcc-c++ libzmq5
RUN     pip3 install jupyter
RUN     pip3 install notebook

WORKDIR /data