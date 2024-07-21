- 👋 Hi, I’m @swapanGit
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
swapanGit/swapanGit is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
Resume [Swapan.pdf](https://github.com/swapanGit/swapanGit/files/11301846/Swapan.pdf)
--->

---
[My Resume](https://github.com/swapanGit/swapanGit/blob/main/Swapan_Kumar_Soren_Cloud-DevOps.pdf) </br>
[My Works on Devops "click here"](https://docs.google.com/presentation/d/1soDCTaRNuK_DgZpONGe_3Rn3f6NVzOOmJJQz0OmgNbE/edit#slide=id.gfa0e6a291f_0_18)
---

---
MTLS works:
---
![alt text](https://cloud.google.com/static/load-balancing/images/mtls_l7xlb.svg)
https://cloud.google.com/load-balancing/docs/mtls






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

