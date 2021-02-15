# dev_JenksinH7
Jeknisn Development and Configuration for RHEL 7.x

#### Add Jenkins Repo
http://pkg.jenkins.io/redhat-stable/jenkins.repo<br/>

`$sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins.io/redhat-stable/jenkins.repo`<br/>

Import Key<br/>

` $sudo rpm --import http://pkg.jenkins.io/redhat-stable/jenkins.io.key`<br/>

#### Once Installation Completed
Goto http://\<IP Address\>:8080, install plugins and create admin user <br/>
  
Install Git, as Jenkins uses git command to pull Github code<br/>

#### Chrome Policy File Ifformation
[Linux Quick Start](https://sites.google.com/a/chromium.org/dev/administrators/linux-quick-start)<br/>

