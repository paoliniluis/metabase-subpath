# Metabase embedded on a sub-path

## What is this

This is the SSO with JWT embedded demo but Metabase is being exposed in a sub-path (localhost:9090/metabase/) thanks to Nginx. This was done to test how Metabase and also the embedding works on this situation.

## How to run

Just 
- clone this repo 
- (set up your token if you want to test embedding)
- do a "docker compose up" on the root folder

Navigate to localhost:8080, click on the link and see te magic happen

## Just testing the normal Metabase in the sub-path?

Then go to localhost:9090/metabase/ and enter with the credentials admin@test.test/secretpass1 (instance gets auto-configured with the setup script at setup/metabase-setup.sh that runs as soon as Metabase is healthy)