FROM almalinux:9
RUN curl -o /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/rpm-stable/jenkins.repo
RUN dnf install fontconfig java-21-openjdk -y
RUN dnf install jenkins -y
RUN systemctl enable jenkins

