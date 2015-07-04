## Setup

### Local repository

Clone the repository to a local working directory

### Install gems

* ``gem install bundler``
* From the repository root, run ``bundle install``

### For all non-css development

From the repository root, run:
``bundle exec jekyll serve``

If you get an 'address is already in use' conflict, change the port in _config.yml or specify a port as ``bundle exec jekyll serve --port 7890`` for example

### For CSS development

In addition to the above, run this to watch the compass build if you need to change the styles:

``bundle exec compass watch``

It will watch for changes to the sass files.
