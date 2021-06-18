## PORT NUMBER
Currently docker-compose.yml is set to listen on port 3001. This must be updated to the same port number to which frontend applications are trying to send socket connection request to.
This can be found on the client side socket io configuration, in the code.

## RUN
Run the following command `docker-compose up` to run the project inside VM. And, `docker-compose down` to close the project inside VM

## VM FIREWALL
If 3001 is the listening port number for the virtual machine. Then, the firewall rules for that VM must allow PORT 3001 in the Firewall inbound rules.

Also, open port 3000 for outbound traffic in firewall settings.