# ember-cli-deploy-kayako-pack

> An EmberCLI Deploy Plugin Pack for Kayako's Ember apps

This plugin pack is prepared for internal use by Kayako and is open-sourced for
educational purposes but will not be supported for shared community use.

## Installation

- Install ember-cli-deploy

```bash
$ ember install ember-cli-deploy
```

- Install this plugin pack

```bash
$ ember install ember-cli-deploy-kayako-pack
```

## What is an ember-cli-deploy plugin?

A "plugin pack" is a concept supported by ember-cli-deploy that allows a single
addon to make multiple plugins available by adding a single direct depedency to
your project. See the [Plugin Pack documentation][1] for more details.

## What plugins are made available?

- [ember-cli-deploy/ember-cli-deploy-build](https://github.com/ember-cli-deploy/ember-cli-deploy-build)
- [ember-cli-deploy/ember-cli-deploy-gzip](https://github.com/ember-cli-deploy/ember-cli-deploy-gzip)
- [ember-cli-deploy/ember-cli-deploy-manifest](https://github.com/ember-cli-deploy/ember-cli-deploy-manifest)
- [ember-cli-deploy/ember-cli-deploy-s3](https://github.com/ember-cli-deploy/ember-cli-deploy-s3)
- [achambers/ember-cli-deploy-git-revision-data](https://github.com/achambers/ember-cli-deploy-git-revision-data)
- [kayako/ember-cli-deploy-consul-config](https://github.com/kayako/ember-cli-deploy-consul-config)
- [kayako/ember-cli-deploy-consul-kv-index](https://github.com/kayako/ember-cli-deploy-consul-kv-index)
- [kayako/ember-cli-deploy-github-deployment-status](https://github.com/kayako/ember-cli-deploy-github-deployment-status)

<p align="center"><sub>Made with :heart: by The Kayako Engineering
Team</sub></p>

[1]: http://ember-cli-deploy.com/docs/v1.0.0-beta.1/plugin-packs/ "Plugin Packs"
