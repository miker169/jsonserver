###json server

JSONServer runs a JSON file database on your localhost,
this is the db.json file.

Then run the the tunnel which exposes the db to the public

internet over a secure tunnel.

###To get running

yarn install

yarn run db

yarn run tunnel

### Things to do after running

You'll need to use the baseUrl to pass into the blog application.

As it only lasts for 8 hours, before it needs renewing