# Demo Django Docker NGINX Production Deployment

Demo of a Django deployment setup using Docker.
https://www.youtube.com/watch?v=nh1ynJGJuT8&ab_channel=LondonAppDeveloper

TODO: 
- For Deployment:
	- Add server url or ip address to docker-compose-deploy.yml
	- For Port adjustment: Change incoming port in docker-compose-deploy.yml at proxy
	- For changes within the app:
		docker-compose -f docker-compose-deploy.yml up --build
		[[docker-compose -f docker-compose-deploy.yml build
		docker-compose -f docker-compose-deploy.yml up -d]]
