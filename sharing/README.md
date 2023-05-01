Kotosiro Sharing
==============================

 To deploy the latest image of Kotoshiro Sharing using docker-compose:

 1. Edit the `docker-compose.yaml` file to include [your desired configurations](https://github.com/kotosiro/sharing#kotosiro-sharing-configuration)
	for the Kotoshiro Sharing image.
 2. Run `docker-compose up -d` to start the container in detached mode:
 
```bash
 $ docker compose -f docker-compose.yaml up -d
```
 
 3. To view the logs of the container, run:
 
```bash
 $ docker-compose logs
```

