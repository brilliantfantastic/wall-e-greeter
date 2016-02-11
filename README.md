wall-e-greeter
==============

The friendly Slack bot that introduces a new member to your team.

## DESCRIPTION

There are a lot of public Slack rooms and new users should feel welcome to those Slack rooms. Hell, all Slack rooms.

wall-e-greeter is a bot that introduces the new user to your team. Here is how it works.

1. You install the bot on Slack
1. The bot will ask you via a DM how you would like to introduce new users to your team
1. You tell the bot and invite it to the #general room (or any room you want to introduce new users)
1. A new user joins the room
1. The bot DMs the new user and asks a little bit about them
1. The new user answers
1. The bot introduces the new user to the team

## INSTALLATION

1. Create a new bot integration in Slack
1. Deploy this bot to Heroku (or your choice of hosting)
1. Update the `SLACK_API_TOKEN` to your API token you received from the integration
1. Add this bot to your Slack team
1. Enjoy the smiles

## CONTRIBUTING

1. Clone the repository `git clone https://github.com/brilliantfantastic/wall-e-greeter`
1. Create a feature branch `git checkout -b my-awesome-feature`
1. Codez!
1. Commit your changes (small commits please)
1. Push your new branch `git push origin my-awesome-feature`
1. Create a pull request `hub pull-request -b brilliantfantastic:master -h brilliantfantastic:my-awesome-feature`

## LICENSE

Copyright (c) 2016, [Brilliant Fantastic, LLC](http://brilliantfantastic.com).

This project is licensed under the [MIT License](LICENSE.md).
