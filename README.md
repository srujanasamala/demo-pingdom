# demo-pingdom
This is a demo project.

build a microservice / app that runs on openshift (minishift for your local mac) the app needs to:
-poll a repository or file containing pingdom rules in a format of your choice (eg csv or json)
-parse these rules into something that can be sent to the pingdom api
-authenticate with the pingdom api and push changes to it from the parsed data
-handle new rules / changed ruls and deletion of rules.
Ideal scenario; developers can write rules for pingdom to test into a repo in stash/git following a normal pull request workflow and these rules end up being updated in pingdom with little to no delay.
