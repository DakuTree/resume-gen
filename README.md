# resume generator
This is a html resume generator built with grunt.

## how to use
(Using build/ as root dir)

1. RUN: "npm install" (Install grunt modules)
2. RUN: "grunt setup" (Setup user files & get libs via bower)
3. Edit .ftppass, files/config/profile.json & files/config/settings.json with your own settings.
4. Replace files/img/profilePhoto.jpg with your own photo (size: 246x246)
5. RUN: grunt prod (Generate page)
6. Your generated resume should now be found in ../prod.
7. <OPTIONAL> RUN: "grunt deploy" (This deploys your website via FTP to the location specified in settings.json)

## misc
Originally wrote this after finding out the original project wasn't exactly easy to customize. It outputs more or less the exactly the same HTML as the PHP version, with some odd changes here and there.  

Personally I've moved to using careers.stackoverflow, but maybe someone will find some use for this :)

## thanks
Design is taken from resume by Pascal van Gemert - https://github.com/pascalvgemert/resume  
Further thanks @ [humans.txt](build/files/misc/humans.txt).
