## deployment-git-phpunit-scp.xml

### Synopsis

> phing build

> Project directory [] ? name_or_path_to_directory (relative or absolute)

### Usage

This script get source on your git and create tow directory, 'build' and 'deploy', first directory is temporary just to get files from git, the seconde directory it use for scp transfert;
If directory name 'test' in your project path, this script execute all file with extention php present in this with phpunit and if test is OK, go to deployment.

### Requirement 
The deployment use SCP transfert you must install SCP for phing : http://www.phing.info/docs/stable/webhelp/ScpTask.html
The test use phpunit : http://www.phing.info/docs/guide/trunk/apcs56.html
