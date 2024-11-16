[x86_mota@falcon ~]$ nano profile.sh

```bash
#!/usr/bin/bash

#                       ,,    ,,                                                       ,,    
#`7MMF'  `7MMF'       `7MM  `7MM             `7MMF'     A     `7MF'                  `7MM  OO
#  MM      MM           MM    MM               `MA     ,MA     ,V                      MM  88
#  MM      MM  .gP"Ya   MM    MM  ,pW"Wq.       VM:   ,VVM:   ,V ,pW"Wq.`7Mb,od8  ,M""bMM  ||
#  MMmmmmmmMM ,M'   Yb  MM    MM 6W'   `Wb       MM.  M' MM.  M'6W'   `Wb MM' "',AP    MM  ||
#  MM      MM 8M""""""  MM    MM 8M     M8       `MM A'  `MM A' 8M     M8 MM    8MI    MM  `'
#  MM      MM YM.    ,  MM    MM YA.   ,A9 ,,     :MM;    :MM;  YA.   ,A9 MM    `Mb    MM  ,,
#.JMML.  .JMML.`Mbmmd'.JMML..JMML.`Ybmd9'  dg      VF      VF    `Ybmd9'.JMML.   `Wbmd"MML.db
#                                          ,j                                                     
#  

# ======================================================================
# Defining constants
# ======================================================================
declare -r NAME="Felipe Cruz"
declare -r CURRENT_ROLE="Business Central Developer"
declare -r LOCATION="São Paulo, Brazil"
declare -r LINKEDIN="felipecruzit"
declare -r DISCORD="x86_mota"

# ======================================================================
# Description: Displays basic information about the user
# ======================================================================
function about_me() {
    echo "Hello there. I'm $1!
    I'm currently job as a $2 living in $3.

    I'm a Linux enthusiast, and my preferred distro is Arch Linux.
    I enjoy exploring new tools and customizing my experience on the system.

    Currently, I'm focusing on expanding my knowledge to become a DevOps Engineer.
    I'm diving deep into, containerization, Kubernetes, cloud platforms, CI/CD and infrastructure automation.
    " | sed 's/^[ \t]*//'
}

# ======================================================================
# Description: Displays contact information about the user
# ======================================================================
function find_me() {
   echo "You can find me on: 
   LinkedIn: $1
   Discord: $2
   " | sed 's/^[ \t]*//'
}

# ======================================================================
# Description: Orchestrates presentation and contact functions
# ======================================================================
function main() {
    about_me "${NAME}" "${CURRENT_ROLE}" "${LOCATION}" 

    find_me "${LINKEDIN}" "${DISCORD}" 
}

# ======================================================================
# Description: Starts script execution by calling the main function
# ======================================================================
main
```
---

### Tools & Technologies

<table>
    <td align="center" width="150px">
        <a href="https://www.debian.org/">
            <img 
                align="center" 
                alt="Debian" 
                height="48" 
                width="48" 
                src="https://github.com/devicons/devicon/blob/master/icons/debian/debian-original.svg"
            />
            <br />
            <strong>Debian</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://archlinux.org/">
            <img 
                align="center" 
                alt="Archlinux" 
                height="48" 
                width="48" 
                src="https://github.com/devicons/devicon/blob/master/icons/archlinux/archlinux-original.svg"
            />
            <br />
            <strong>Archlinux</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://fedoraproject.org/">
            <img 
                align="center" 
                alt="Fedora" 
                height="48" 
                width="48" 
                src="https://github.com/devicons/devicon/blob/master/icons/fedora/fedora-original.svg"
            />
            <br />
            <strong>Fedora</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://www.suse.com/">
            <img 
                align="center" 
                alt="SUSE" 
                height="48" 
                width="48" 
                src="https://github.com/devicons/devicon/blob/master/icons/opensuse/opensuse-original.svg"
            />
            <br />
            <strong>SUSE</strong>
        </a>
    </td>
<table>
    <td align="center" width="150px">
        <a href="https://git-scm.com/">
            <img
                align="center"
                alt="Git"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg"
            />
            <br />
            <strong>Git</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html">
            <img
                align="center"
                alt="Shell Script"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg"
            />
            <br />
            <strong>Shell Scripting</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://www.python.org">
            <img
                align="center"
                alt="Python"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg"
            />
            <br />
            <strong>Python</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/">
            <img
                align="center"
                alt="Microsoft C/AL"
                height="48"
                width="48"
                src="https://github.com/x86-mota/x86-mota/blob/main/icons/BusinessCentral.svg"
            />
            <br />
            <strong>Microsoft C/AL</strong>
        </a>
    </td>
</table>
<table>
    <td align="center" width="150px">
        <a href="https://www.docker.com/">
            <img
                align="center"
                alt="Docker"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg"
            />
            <br />
            <strong>Docker</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://kubernetes.io/">
            <img
                align="center"
                alt="Kubernetes"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/kubernetes/kubernetes-original.svg"
            />
            <br />
            <strong>Kubernetes</strong>
        </a>
    </td>
</table>
<table>
    <td align="center" width="150px">
        <a href="https://www.ansible.com/">
            <img
                align="center"
                alt="Ansible"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/ansible/ansible-original.svg"
            />
            <br />
            <strong>Ansible</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://www.terraform.io/">
            <img
                align="center"
                alt="Terraform"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/terraform/terraform-original.svg"
            />
            <br />
            <strong>Terraform</strong>
        </a>
    </td>
</table>
<table>
    <td align="center" width="150px">
        <a href="https://www.mysql.com/">
            <img
                align="center"
                alt="MySQL"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original.svg"
            />
            <br />
            <strong>MySQL</strong>
        </a>
    </td>
    <td align="center" width="150px">
        <a href="https://mariadb.org/">
            <img
                align="center"
                alt="MariaDB"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/mariadb/mariadb-original.svg"
            />
            <br />
            <strong>MariaDB</strong>
        </a>
    </td>
        <td align="center" width="150px">
        <a href="https://www.postgresql.org/">
            <img
                align="center"
                alt="PostgreSQL"
                height="48"
                width="48"
                src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg"
            />
            <br />
            <strong>PostgreSQL</strong>
        </a>
    </td>
</table>