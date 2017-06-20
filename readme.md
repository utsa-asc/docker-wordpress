git clone --recursive -j8 git@bitbucket.org:utsaucm/docker-wordpress.git

mkdir mysql-data

git clone git@bitbucket.org:utsaucm/utsa-default-wordpress.git

cd utsa-default-wordpress

git clone git@bitbucket.org:utsaucm/utsa-wp-content.git wp-content
