# server_from_scratch

to run Flask and Pyramid, use virtualenv:

$ [sudo] pip install virtualenv
$ mkdir ~/envs
$ virtualenv ~/envs/lsbaws/
$ cd ~/envs/lsbaws/
$ ls
bin  include  lib
$ source bin/activate
(lsbaws) $ pip install pyramid
(lsbaws) $ pip install flask
(lsbaws) $ pip install django

no need to reinstall pyramid/flask/django if it's already been done...

then navigate back to the directory and run the run_x.sh scripts