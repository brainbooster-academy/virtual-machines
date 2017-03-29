# Virtual machine for development

## Instructions

To run virtual machines for development, you should have following
prerequisites installed:

### Prerequisites

- official Docker app
- docker-compose installed (usually bundled in Docker app)

### How to run

Execute next code

```
docker-compose build
docker-compose run
```

And in another terminal execute

```
docker attach virtualmachines_web_1
```

and press Enter - you'll be logged into dedicated docker development
instance.

Your code will be mounted at `/code` directory

## Services

This virtual machine has next services inside:

- redis
- postgresql
- mysql
- mongo

They are accessible using same host names and default ports

## Special notes

- MySQL uses empty root password

## Contribution

Feel free to contribute to this project and ask for extension via github
issues. 
