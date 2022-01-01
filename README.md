# Testar Jenkins Theme

TeStar - Solution for Automated System Tests.

## How to apply this style to Jenkins

Simply copy this repository to Jenkins user content path, e.g. _/var/lib/jenkins/userContent/_.
Finally add the path _/userContent/css/testar-theme.css_ of that theme file to the Jenkins theme configuration in 'Configure System'.

By default the _userContent_ folder has just permissions for the user _jenkins_, therefore the user
_jenkins-admin_ should be added to group _jenkins_ and the write permissions for group members of _jenkins_
should be added too.
