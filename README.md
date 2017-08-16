# OpenMCT CoSE Bot

> a GitHub App built with [probot](https://github.com/probot/probot) that automatically labels pull requests in the OpenMCT Repository.

Pull requests are automatically labelled according to where along in the merge process a pr is: `Needs: Author Checklist`, `Needs: Reviewer Checklist`, `Needs: Merge`.

## Setup

```
# Install dependencies
npm install

# Run the bot
npm start
```

rough draft of setup:
1. deploy this repository on a heroku instance.
2. install the githup app on the repository.
3. configure bot (installation id), initialize set up. set password for the bot interface

