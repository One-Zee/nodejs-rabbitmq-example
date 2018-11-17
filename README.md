# nodejs-rabbitmq-example

# Requires

Install docker see official documentation at

https://docs.docker.com/install/


Install docker-compose see official documentation at

https://docs.docker.com/compose/install/

Install nodejs and npm package manager. See at

https://nodejs.org/en/download/package-manager/

# Run Project

Run rabbitmq and mongo docker container In project folder

$ docker-compose -f docker-compose.yml up

# Test producer

$ nodejs sender.js

# Verify

In rabbitmq management console login with admin/admin username and password at

http://localhost:15672

See in hello queue for a messages....
