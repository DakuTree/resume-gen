# html resume generator
This is a html resume generator built with grunt.

## how to use
(Using build/ as root dir)
1. RUN: "npm install" (Install grunt modules)
2. RUN: "grunt setup" (Setup user files & get libs via bower)
3. Edit .ftppass, files/config/profile.json & files/config/settings.json with your own settings.
4. RUN: grunt prod (Generate page)
5. Your generated resume should now be found in ../prod.
6. <OPTIONAL> RUN: "grunt deploy" (This deploys your website via FTP to the location specified in settings.json)

##thanks
Design is based on resume by Pascal van Gemert - https://github.com/pascalvgemert/resume  
Further thanks @ [humans.txt](build/files/misc/humans.txt).
