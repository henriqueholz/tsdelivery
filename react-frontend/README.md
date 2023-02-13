React (Frontend)

Configuring /etc/hosts
The communication between the applications is through the machine network. It is necessary to configure a address that all containers have access.

Add inside /etc/hosts:

127.0.0.1 host.docker.internal
Inside all operational systems is necessary to open the program to edit the hosts as admin or root.

Running the application:

docker-compose up

http://localhost:3001
