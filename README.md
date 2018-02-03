# Olecae

An ambitious multi-player RPG

This project is common dev environment tying together
backend an frontend of the project, and is not meant
to be put into production as is.


## Steps to run

Do a recursive `git clone` of this repo, then run
`docker-compose up` and you should be golden.


## What does it do?

Backend and frontend lives in separate repos (one per
docker image) - so all this repo does is pull them in
and provide them with compose configuration. (Which
also adds in a web server.)

## License

This project is (C) by *Pixie Coder AB* 2018
