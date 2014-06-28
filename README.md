# What is it?

A quick and dirty script that exports your TripIt trip information to an XML file.

# Installation and usage

Follow these steps:

1. Install Git,Ruby, Ruby Gems, and Bundler if you haven't already.
1. Go to https://www.tripit.com/developer/create and create a full API application. You will need the API Key and API Secret later
1. Then clone this git repo: `git clone git@github.com:muness/tripit-export-trips-to-xml.git`
1. Go to the checked out directory and `cp creds.yml.skel creds.yml`
1. Edit creds.yml, putting in your own API key and API Secret
1. `bundle install`
1. `bundle exec ./export-trips-to-xml` . This will authorize your app, download your trip data and save it to trips.xml

