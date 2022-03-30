# some-protos
This is a monorepo containing protobufs.

It has a Github Actions pipeline that will dispatch events to various other 
repositories, one per target language.

For this proof-of-concept, I only have repos for Go and TypeScript:
* [some-protos-go](https://github.com/kevinmichaelchen/some-protos-go)
* [some-protos-ts](https://github.com/kevinmichaelchen/some-protos-ts)

But you could imagine having additional repos for whatever languages you use.

## Personal Access Token
I generated a personal access token with `repo` scope as [instructed](https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event).
I made a single environment [here](https://github.com/kevinmichaelchen/some-protos/settings/environments), with an `ACCESS_TOKEN` secret.
