# Context

Those bundles were created to support a seriess of posts published on Insights blog: 

* [Part 1](https://insights.ubuntu.com/2015/05/06/universal-modeling-language-for-service-oriented-architectures-part-1/)
* [Part 2](https://insights.ubuntu.com/2015/05/07/universal-modeling-language-for-service-oriented-architectures-part-2/)

Those explain the language of modeling SOA applications with Juju, and put it in practice. 

# How to use

You'll need [Juju](https://jujucharms.com/docs/stable/getting-started) of course. 

Once you're good to go, I'd recommend you use a public cloud for those examples, just because we will spin more than 10 units, which would burn your laptop to ashes if you ran it locally in containers. 

Then you can follow 2 paths: [Quickstart or Deployer](http://askubuntu.com/questions/597826/difference-between-deploying-bundle-with-quickstart-or-juju-deployer)

Don't forget that the app need to connect to Twitter, and your credentials as well as a hashtag is needed. You'll need to edit the YAML files by creating an app on [Twitter](https://apps.twitter.com/)


