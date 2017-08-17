# OpenMCT CoSE Bot

> a GitHub App built with [probot](https://github.com/probot/probot) that automatically labels pull requests in the OpenMCT Repository.

Pull requests are automatically labelled according to where along in the merge process a pr is: `Needs: Author Checklist`, `Needs: Reviewer Checklist`, `Needs: Merge`.

## Setup

rough draft of setup:
1. deploy this repository on a heroku instance.
  You need the url of the heroku instance, which will be listening to your webhooks.
  Create a webhook secret, which will be stored on the bot server and the github repo.
2. install the githup app on the repository.
3. configure bot (installation id), initialize set up. set password for the bot interface

change the repo, owner values in the index.js file.
