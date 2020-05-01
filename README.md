Run `docker-compose up` to initalize docker and install gems (see entrypoint.sh:10)

Once Puma is serving you can Ctrl+C to stop docker, we do not need it running anymore.

Locally run `gem install solargraph`

Locally run `solargraph typecheck app/helpers/application_helper.rb` # get error

Locally run `gem uninstall solargraph; gem install solargraph --version 0.38.6`

Locally run `solargraph typecheck app/helpers/application_helper.rb` # do not get error
