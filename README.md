# panda.yml

This repo contains the yml config files to be used in $projectadmin and $serveradmin, please read through each of them to determine what you need to do

## $projectadmin

This command allows you to set up your project with the correct meta data so it can come up in the relevant searches.

We currently support projects with and without their own currency, you will have the choice when you run $register

Once a project is registered, the Admin can set corresponding information with $projectadmin

The meta section should be mostly links to project resources such as website, announcements etc. Some fields may or may not be relevant, ie. for a project without its own currency you may not need to set explorer or exchange etc.

The blockchain section should give a summary of the chain specs, content is used to sort and search by users

All details are displayed when the $info command is run

## $serveradmin

This command allows you to customize how panda-bot works on your server

Currently Discord is supported

Any Discord server admin can run $serveradmin to configure how panda-bot works in their server

As of now you can set the channels which you'd like panda-bot to work in as well as the currency/currencies allowed in the server, you can also set welcome messages and ticker channels

You can indicate whether this is a public server by setting a public invite and set a number of metrics to ensure your server can be shown up in the correct search results

## Support

If you'd like some help on how to write your panda.yml please [contact us via Discord](https://discord.gg/Hs57Jg4) and let us know
