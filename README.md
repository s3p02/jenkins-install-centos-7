# jenkins-install-centos-7
Installation of Jenkins on GCP-VM

```sudo yum install -y wget```


```sudo yum install -y git```


```git clone https://github.com/s3p02/jenkins-install-centos-7.git```


```bash prep.sh```

CHANGE PORT tp 38080
```sudo vim /etc/sysconfig/jenkins```

START SERVICE
```sudo service jenkins start```


```sudo chkconfig jenkins on```


```systemctl status jenkins```


```http://__IP__ADDRESS__:38080/```

PASSWORD IS IN ```/var/lib/jenkins/secrets/initialAdminPassword```

```sudo cat /var/lib/jenkins/secrets/initialAdminPassword```


