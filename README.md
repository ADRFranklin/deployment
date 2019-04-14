# open.mp/burgershot deployment configuration

This repo contains the production manifests and configuration for burgershot.gg and open.mp related services.

## Contributing

Use the `example.env` file by renaming it to `.env` then run `docker-compose up` to spin up all the services. This will
give you a development environment however you will need to open a port into the nginx container yourself by adding a
port definition or running a local instance of Traefik.

Please open a pull request with a detailed description of the change your making and why it's necessary for the
operation of the live services.
