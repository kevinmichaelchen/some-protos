# some-protos
Monorepo containing protobufs.

The Github Actions build should trigger builds of other repos, using a `repository_dispatch` event.

I generated a personal access token with `repo` scope as [instructed](https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event).
I made a single environment [here](https://github.com/kevinmichaelchen/some-protos/settings/environments), with an `ACCESS_TOKEN` secret.
