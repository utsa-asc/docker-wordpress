git clone --recursive -j8 git@bitbucket.org:utsaucm/docker-wordpress.git

cd docker-wordpress

mkdir mysql-data

git clone git@bitbucket.org:utsaucm/utsa-default-wordpress.git

cd utsa-default-wordpress

git clone git@bitbucket.org:utsaucm/utsa-wp-content.git wp-content

docker-compose up

#finish install at localhost:8000/wp-admin/install.php
http://localhost:8000/wp-admin/install.php
