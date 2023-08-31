<h1>Installation of Ansible, NGinx, and MariaDB on Web Servers and Database Servers</h1>

<h1 align="center">
 
<h2>Description</h2>
<b>Utilized script to install Ansible then NGinx and MariaDB. Ansible uses playbooks, to automate tasks like software installation, configuration changes, and file management across multiple systems. NGinx can act as a reverse proxy and load balancer, distributing incoming web traffic among backend servers. It's commonly used to improve website performance, scalability, and security. MariaDB is an open-source relational database management system (RDBMS) that is a drop-in replacement for MySQL. It offers data storage, retrieval, and management, making it suitable for various applications and websites. MariaDB is known for its high performance, reliability, and extensive features, while maintaining compatibility with MySQL databases.
</b>
<br />
<br />

<h2>Ansible Install</h2>
Installed Ansible using process found in the code file within this repository. After installing copy the ssh key from all the anisble hosts. In my scenario I copied from web1, web2, db1, and db2. 
<br />
<br />

Here is an example of copying the ssh key for DB2 then pinging it to ensure that there is connection
<p align="center"

![Ansible screenshot](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/1360cda2-553d-405e-874f-6a021939bc73)

Then I created a user named egoad on the WEB and DB servers after I made a group out of them (to make the process easier)
![Ansible User](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/e6f7d403-e9c8-4be3-b5b6-56a99178ea25)


</p>
<h2>Installing Nginx on WEB servers</h2>
- <b>Installed, Started, and Configured Nginx as well as include auto start at the system boot:</b>

![Nginx](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/a95da2af-cc53-492e-b74a-4ef0fa738715)
![Nginx Start](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/fb8a7b72-be09-4767-9295-ee061b4a037c)
![startup page nginx](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/3a07094c-094a-43fd-853c-9f10ff576a86)

<h2>Installing MariaDB</h2>
- <b>Installed, Started, and Configured MariaDB as well as include auto start at the system boot:</b>

![Mariadb](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/76f6920d-5c27-4577-a43c-d020a5a5d13d)
![Mariadb2](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/79310b86-ad13-4766-9c89-3a62f28ea0c8)
![MariaDB3](https://github.com/jlam744/Ansible_NGinx_MariaDB/assets/95711303/9db525de-bba9-4113-af5f-79fd8fab62d8)


<p align="center">

</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
