FROM almalinux:9
RUN sudo dnf -y install dnf-plugins-core
RUN sudo dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo
RUN sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y
RUN sudo systemctl start docker
RUN sudo systemctl enable docker
RUN sudo dnf module enable nodejs:20 -y
RUN sudo dnf install nodejs –y

