# Tool-Box
all coomand related to cmd and terminal








less file_name  -
ll
ls










Composer 
========


          - composer.json vs composer.lock
          - composer install vs composer update
                      
              composer update
              ===============
                       - When you do composer update it will check for the composer.json 
                         file and updates all the packages/libraries that are listed in it
                         & once the packages are updated it will rewrite new updates in composer.json
                         & composer.lock file by deleting old package updates.


            composer install
            ================
                        - When you do composer install it will check for composer.lock 
                          file and install all the packages/libraries that are listed in composer.lock file.

