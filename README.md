# some-protos
This is a monorepo containing protobufs.

It has a Github Actions pipeline that will dispatch events to various other 
repositories, one per target language.

You could imagine having these repos:
* some-protos-go
* some-protos-java
* some-protos-ruby
* etc.

I generated a personal access token with `repo` scope as [instructed](https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event).
I made a single environment [here](https://github.com/kevinmichaelchen/some-protos/settings/environments), with an `ACCESS_TOKEN` secret.
