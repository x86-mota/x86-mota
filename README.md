[x86mota@falcon ~]$ vi ./profile.sh

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
```