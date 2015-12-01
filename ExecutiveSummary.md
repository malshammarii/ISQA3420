Thomas Jorgensen
Mohammed Alshammari

Executive Summary

# Problem

Open source software allows developers to share code that they have written with each other through online repositories. These repositories can be found on websites like Github.com or Sourceforge.com. Lately, there has been in increase of corporate presence in the open-source community. Companies are able to cut down on their development staff by looking to open-source communities for help. In our situation, we are acquiring digital assets through the open-source community, which have individual licenses attached to them, as well as vulnerabilities. When someone uses open-source code created by another person, they must abide by those licenses. Whether this is a copy-left license or a beer license, when it is triggered the user needs to abide by the licenses. Vulnerabilities in the code are also a problem that comes with attaining digital assets. Our company wants to address these issues so that we may fix them and abide by the rules set in place for the code.

# Solution

The purpose of our software is not to fix the vulnerabilities and automatically make sure the code is abiding by the licenses. It is to bring raise awareness of the issues and risks, so that developers may fix them. Within our system, we can use resources such as FOSSology or the NIST database to check code for licenses known vulnerabilities in the code. In its current state, the software runs the asset through these databases to check for licenses or known vulnerabilities. Our system also allows for the code to be checked through our own database, after being encrypted with a SHA1 Hash. By encrypting this code and sending it through our database to check if it exists, we can skip the process of checking it against FOSSology or the NIST Database. After code has been committed we added a process so that the Corporate Manager can send a notification to the Corporate Developer to upload the code to an online repository, if the license requires it.

#References
