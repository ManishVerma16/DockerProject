# Joomla_MYSQL-Database_Complete_Setup_Docker_Project_IIEC_RISE

Joomla is an open source Content Management System (CMS), which is used to build websites and online applications. It is free and extendable which is separated into front-end templates and back-end templates (administrator). Joomla is developed using PHP, Object Oriented Programming, software design patterns and MySQL (used for storing the data). This Docker_Compose file will provide you a complete environment in which you can create websites with backend support by a single command in less than one second.

Using this repository you can do these things automatically:-

    Download images from DockerHub Community. 
    Create Docker volumes for permanent storage of your data.
    Set Up MySQl Database for data storage.
    Set up Joomla framework for creating websites.

## This Compose file build on these technologies:
* Redhat Enterprise Linux Version 8
* Docker
* Joomla 
* MYSQL

# Pre-requisites for Installations
First of all install Redhat_Enterprise_Linux_Version_8 and configure yum properly make sure you have installed the latest, stable and compatible versions of Docker, Joomla, MYSQL server, Docker Compose.

# If you dont have go this way:

* Docker install on Redhat8:

Configure yum by adding docker.repo:

    $ cd /etc/yum.repos.d 
    $ gedit docker.repo
        here add these lines:
        
        [docker_repo]
        name=docker_repo
        baseurl=https://download.docker.com/linux/centos/docker-ce.repo
        gpgcheck=0
        
        save it.
    $ yum install docker-ce --nobest

