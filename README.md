- 👋 Hi, I’m @swapanGit
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
swapanGit/swapanGit is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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

<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; modified=\&quot;2021-11-16T16:48:00.167Z\&quot; agent=\&quot;5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/96.0.4664.45 Safari/537.36\&quot; etag=\&quot;6AH5dPtJidR5cRZCf3Yu\&quot; version=\&quot;15.7.4\&quot; type=\&quot;device\&quot;&gt;&lt;diagram name=\&quot;Page-1\&quot; id=\&quot;12e1b939-464a-85fe-373e-61e167be1490\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;,&quot;toolbar&quot;:&quot;pages zoom layers lightbox&quot;,&quot;page&quot;:0}"></div>
<script type="text/javascript" src="https://app.diagrams.net/js/viewer-static.min.js"></script>
