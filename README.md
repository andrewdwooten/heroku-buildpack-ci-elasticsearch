Heroku buildpack for running Elasticsearch inside a dyno

This is a fork of the official Heroku buildpack for Java.

After the regular installation of Java performed by the original buildpack, it downloads Elasticsearch, installs it and starts it. This buildpack is useful for CI, especially when using Heroku CI Parallel Test Runs. It makes use of the buildpack cache.

The ELASTICSEARCH_URL environment variable is exported for use in your application.

License
-------

Licensed under the MIT License. See LICENSE file.
