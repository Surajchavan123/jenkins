steps:
1) run, wget -O /usr/share/keyrings/jenkins-keyring.asc \
    https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
2) run, sudo apt-get update
3) run, apt-get install fontconfig openjdk-17-jre
4) then run,  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null
5) run, apt-get install jenkins
6) cat /var/lib/jenkins/secrets/initialAdminPassword      
