- š Hi, Iām @swapanGit
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
swapanGit/swapanGit is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

##make your own script##</br>
##install java## </br>
wget https://download.java.net/openjdk/jdk11/ri/openjdk-11+28_linux-x64_bin.tar.gz </br>
tar -xvf openjdk-11+28_linux-x64_bin.tar.gz </br>
mv jdk-11 /opt </br></br></br></br>

##install maven## </br>
wget https://dlcdn.apache.org/maven/maven-3/3.8.2/binaries/apache-maven-3.8.2-bin.tar.gz </br>
tar -xvf apache-maven-3.8.2-bin.tar.gz </br>
mv apache-maven-3.8.2 /opt/ </br></br></br></br>

##configure java and maven## </br>
echo " </br>
JAVA_HOME='/opt/jdk-11' </br>
MAVEN_HOME='/opt/apache-maven-3.8.2' </br>
PATH="$JAVA_HOME/bin:$MAVEN_HOME/bin:$PATH" </br>
export PATH" >> .bashrc </br>
</br></br></br></br>

##configure docker## </br>
apt update
apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
apt update
apt-cache policy docker-ce
apt install docker-ce
systemctl status docker

