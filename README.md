# watchbuild-ci-runner

This repo is just provides a Gemfile pointing to a custom implementation of watchbuild with slack integration.
A CI system can pull this repo and run `bundle exec watchbuild -a <app-id> -u <itc-user-id> -n <slack-webhook-url>`

See my fork of [watchbuild](https://github.com/alihen/watchbuild) for more information.
