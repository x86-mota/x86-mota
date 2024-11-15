### Tools & Technologies

<div style="display: inline_block">
    <a href="https://www.kernel.org/" title="Linux">
        <img align="center" alt="Linux" height="48" width="48" src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg">
    </a>
    <img align="center" alt="Shell script" height="48" width="48" src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg">
    <a href="https://www.python.org" title="Python">
        <img align="center" alt="Python" height="48" width="48" src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg">
    </a>
    <img align="center" alt="Git" height="48" width="48" src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg">
    <img align="center" alt="Docker" height="72" width="72" src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg">
    <img align="center" alt="Ansible" height="48" width="48" src="https://github.com/devicons/devicon/blob/master/icons/ansible/ansible-original.svg">
</div>

---

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
