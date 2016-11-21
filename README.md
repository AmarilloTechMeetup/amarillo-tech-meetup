# serverless-slack-join

An automated way for your team members to sign-up for your [Slack](https://slack.com).

## Installation

* [Install node](https://nodejs.org/en/download/)
* Install [Serverless](https://serverless.com/)
```
npm install -g serverless
```
* Setup your [AWS keys](https://serverless.com/framework/docs/providers/aws/guide/credentials/)
* Clone this repository
```
git clone https://github.com/ScriptGadget/serverless-slack-join
```
* Change into that directory
```
cd serverless-slack-join
```
* Run npm Install
```
npm install
```
* Get your [Slack test credentials](https://api.slack.com/docs/oauth-test-tokens). You will need to be logged in as an admin or owner in your slack.
* create a .env file
```
cp .envexample .env
```
* edit .env to add your own slack
* deploy
```
severless deploy
```
* Note your shiny new endpoint and use it from a webform. For a simple example, see [amarillo-tech-meetup](https://github.com/ScriptGadget/amarillo-tech-meetup)

## Contributing
If you have a fix, or a suggestion, please create a pull request.

## Todo
This was a quick, weekend hack with a framework I didn't know, so there's probably a better way to do all of this. This at least has the virtue of simplicity.
* Explore using the new [AWS Environment Variables](http://docs.aws.amazon.com/lambda/latest/dg/env_variables.html)
* Atone for my scandalous lack of test cases. I'd love to see some examples of good Serverless testing.

## Credits

* This was inspired by [serverless-slack-invite-api](https://github.com/amv/serverless-slack-invite-api) by Antti Vähäkotamäki, but I needed something that worked with [Serverless](https://github.com/serverless/serverless) v1.0
* built with [Serverless](https://www.serverless.com)
