# my-gogs-selinux


This is the customized SELinux Policy Configuration for GOGS which is based on Red Hat Enterprise Linux 8.1 (Ootpa) by referencing https://github.com/rdvn/gogs-selinux. 

Prerequisities for this repositoy are,
 - install the following packages
   1.selinux-policy-devel 2.policycoreutils-python-utils 3.policycoreutils-devel 4.selinux-policy-doc 5.rpm-build 
 - enable the following SELinux Boolean
   1.nis_enabled 2.domain_can_mmap_files 3.mysql_connect_http 
 
 
