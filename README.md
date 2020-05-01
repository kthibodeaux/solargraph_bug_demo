Run `docker-compose up` to initalize docker and install gems (see entrypoint.sh:10)

Once Puma is serving you can Ctrl+C to stop docker, we do not need it running anymore.

Locally run `gem install solargraph`

Locally run `solargraph typecheck app/helpers/application_helper.rb`
