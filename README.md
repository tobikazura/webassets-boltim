Sebagian merupakan isi untuk Webassets di CKAN

just do sudo docker cp placeholder.png ckan:/srv/app/src/ckan/ckan/public/base/images/

but deploy the container first

sudo docker cp layout1.html ckan:/srv/app/src/ckan/ckan/templates/home/


for featured section: ckan:/srv/app/src/ckan/ckan/templates/home/snippets/promoted.html

for less py : sudo docker cp less.py ckan:/srv/app/src/ckan/ckan/cli/
for search section: sudo docker cp search.html ckan:/srv/app/src/ckan/ckan/templates/home/snippets/search.html

for footer sudo docker cp footer.html ckan:/srv/app/src/ckan/ckan/templates/footer.html

for footer logo sudo docker cp ckan-logo-footer.png ckan:/srv/app/src/ckan/ckan/public/base/images/ckan-logo-footer.png
