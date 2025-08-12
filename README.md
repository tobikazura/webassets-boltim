Sebagian merupakan isi untuk Webassets di CKAN

just do sudo docker cp placeholder.png ckan:/srv/app/src/ckan/ckan/public/base/images/

but deploy the container first

sudo docker cp layout1.html ckan:/srv/app/src/ckan/ckan/templates/home/


for featured section: ckan:/srv/app/src/ckan/ckan/templates/home/snippets/promoted.html

for less py : sudo docker cp less.py ckan:/srv/app/src/ckan/ckan/cli/