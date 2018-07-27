# watchbuild-ci-runner

This repo is just provides a Gemfile pointing to a custom implementation of watchbuild with slack integration.
A CI system can pull this repo and run `bundle exec watchbuild -a <app-id> -u <itc-user-id> -l <slack-webhook-url>`

See my fork of `watchbuild` for more information.
