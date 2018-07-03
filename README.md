<p align="center">
  <img src="https://cdn.rawgit.com/mesg-foundation/awesome/master/logo.svg" alt="MESG Awesome" height="120">
  <br/><br/>
</p>

[Website](https://mesg.com/) - [Docs](https://docs.mesg.com/) - [Chat](https://discordapp.com/invite/SaZ5HcE) - [Blog](https://medium.com/mesg)

List of Services and Applications developed with MESG

# Services

## Blockchain

- [Ethereum ERC20](https://github.com/mesg-foundation/service-ethereum-erc20) - MESG Service to interact with an Ethereum ERC20 token
- [Ethereum](https://github.com/mesg-foundation/service-ethereum) - Ethereum service for MESG

## Notification

- [MESG Discord Invitation](https://github.com/mesg-foundation/service-discord-invitation) - MESG Service to invite users to join our discord
- [Webhook](https://github.com/mesg-foundation/service-webhook) - Send and Receive Webhook through MESG
- [Slack](https://github.com/mesg-foundation/service-slack) - MESG service that permits to send a notification on Slack
- [Devcon update](https://github.com/mesg-foundation/service-devcon-update) - MESG Service that notify when there is an update on the Devcon website
- [Email Sendgrid](https://github.com/mesg-foundation/service-email-sendgrid.git) - Send emails through Sendgrid API

## Processing

- [JS function](https://github.com/mesg-foundation/service-js-function) - MESG Service that execute a javascript function

# Applications

- [Devcon update on Slack](https://github.com/mesg-foundation/application-devcon-update-on-slack) - MESG Application that send a slack notification when there is an update on the devcon website

# Contribution

### To add a new service:
- Create a fork of the project
- Update the `service.json` file by adding in the end your service with the attributes `name`, `description`, `url`, `lang` and `category`
- Generate the new readme running `node script/generateReadme.js`
- Create a pull request with your modifications (You should only have the `README.md` and `services.json` files updated)

### To add a new application:
- Fork of the project
- Add your application in the `applications.json` file by adding in the end your application with the attributes `name`, `description`, `url` and `lang`
- Generate the new readme running `node script/generateReadme.js`
- Create a pull request with your modifications (You should only have the `README.md` and `applications.json` files updated)

### Want a new service created but don’t know how to code it?
- Create a [new issue](https://github.com/mesg-foundation/awesome/issues/new)
- Write the name of the service
- Write a description of what the service will do, try to be as precise as possible, define the different tasks and the different events that this service needs to provide and with the data that will be exposed
- Describe why the service will be useful
- Add the service label
- Submit your issue
- **Bonus:** Come to the [Discord](https://discord.gg/SaZ5HcE) and share the issue with the rest of the community to try to find someone that might be interested in helping you for this

### Unsure of where to start?
- Combine some of the existing services above to solve issues [found here](https://github.com/mesg-foundation/awesome/issues/new)

### Need more help?
- Join us on [Discord](https://discord.gg/SaZ5HcE) - we’re available to answer your questions
- Check out how MESG works in the [documentation](https://docs.mesg.com)
- To learn how to connect services and applications, use the [tutorials](https://tutorials.mesg.com)

### Found a bug?
- For bugs related to Core, submit an issue [here](https://github.com/mesg-foundation/core/issues)
