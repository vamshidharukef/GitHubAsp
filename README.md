## Overview

![](http://bit.ly/2nh5uv1)

GitHub is a web-based Git or version control repository. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features but it doesn't have an integrated build server.

We can overcome this shortfall by using Visual Studio Team Services (VSTS) as a continuous integration platform for Github. This lab will demonstrate how to achieve this using the following steps:

- Fork project repository to your github account
- Link the GitHub account to VSTS
- Editing the existing Build Definition to include source code from GitHub
- Configure the Triggers
- Execute the Build