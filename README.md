registration-app  TEST99
<br>

#Jenkins Plugins

BitbucketVersion
Artifactory
JFrog
Eclipse Temurin installer
SonarQube Scanner
Sonar Quality Gates
Docker* #ALL


<br>
tar -zcvf jenkins-backup.tar.gz /var/lib/jenkins/
<br>
aws s3 cp jenkins-backup.tar.gz s3://jenkins-s3bucket//jenkins-backup.tar.gz
<br>
Download
aws s3 cp s3://jenkins-s3bucket//jenkins-backup.tar.gz jenkins-backup.tar.gz
<br>
rm -rf /var/lib/jenkins

tar -zxvf jenkins-backup.tar.gz -C /





