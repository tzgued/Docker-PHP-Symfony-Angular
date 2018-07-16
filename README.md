
# Starter setup for Symfony 4 and Angular 6 Dockerized Project


## **Presentation**

This is a docker composed project that can be used to quickly start a SF4 Angular 6 Project.
PS:

 - The ports used in the [docker-compose.yml](https://github.com/tzgued/dockerPHP/blob/master/docker-compose.yml) maybe not the ones you would love to setup expecially the NGINX on port 81.
 - For developping on Angular I prefer to [ng-serve](https://github.com/angular/angular-cli/wiki/serve) on my machine. It is perfectly fine if you want to add another container based on node and run your dev on it. I may push another version with that.
 - It's my first time doing such contribution to the github community, so feel free to interact in any way you like.

## Docker containers:

		DataBase:
		 1. MySQL
		 2. PhpMyAdmin
		
		Server Code:
		 1. PHP
		 2. Apache
	 
		 Front End Code:
		 1. NGINX
