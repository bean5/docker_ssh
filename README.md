# docker_ssh

A docker wrapper that maps your `~/.ssh` to a an alpine-based SSH container.

## Requirements

* docker
* docker-compose

## Use

This project uses docker-compose to mount your `~/.ssh/` to the container as read-only. It then copies that, modifies the permissions, and you are ready to go!

`docker-compose run ssh`

Then use ssh as you normally would. Enjoy!

## License

See LICENSE file. I chose MIT because I didn't do much here except glue awesome code together. License selected using <https://choosealicense.com/> -- a very handy tool!
