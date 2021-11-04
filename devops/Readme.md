1. Take a simple nodejs server of your choosing (a nextjs server that shows a simple webpage is fine), make it installable on kubernetes, then write documentation for a user (in this case, me) to install that server on their own kubernetes.
2. Take a simple database of your choosing, make it installable on kubernetes, then write documentation for a user (in this case, me) to install that database on their own kubernetes -> the database and server do not need to connect.
3.
4. Describe how you will manage the following topics. You may not be able to implement it due to minikube restrictions, if not, please describe it in the documentation (it’s an exercise of planning more than implementing):
    * Take security into consideration, which configuration will you apply?
    * How do you will manage the storage in kubernetes? Assuming you’re not using minikube... which technology and configuration you’ll choose?
    * How do you will manage the configuration files in kubernetes? And the secrets? Do you will use an additional technology?
    * Regarding monitoring, how do you will ensure that the critical services (assuming the nodejs server is critical...) are always up and running? How do you will manage the monitoring of the entire system?
    * Make sure you define an ingress/egress policy to make the nodejs server available outside kubernetes. Which technology you would use?
5. You should assume that the user is technical, but isn’t knowledgeable on kubernetes.
6. The user (me), will only install this on their local machine.
7. The documentation does not need to be elaborate, but it should be clear and cover all the steps that the users need to do.
8. Please submit the project as a github repo.

As far as I can tell this shouldn’t take too long, please let me know if it’s alright!
