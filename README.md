# 2021_django
I hace successfully created a POSTGRES database on Digitalocean ($15 per month). It allows
selected clients to connect, currently a few Digitalocean droplets. My plan is to develop
small django projects, living in subdirectories of this project. Some of these projects will
be deployed for public use. A major goal is to separate code from data. Data are handled
in the following ways:

1. Database using managed POSTGRES at Digitalocean
2. BLOBS (e.g. photos) stored at Amazon S3

Code is stored in separate directories together with all resources. Common resources, e.g. xls stylesheets
can eventually be stored in a special catalog.
