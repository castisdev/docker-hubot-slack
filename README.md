# hubot-slack

Dockerfile for [Hubot](https://hubot.github.com) using [Slack-Adapter](https://github.com/slackhq/hubot-slack),
including some custom hubot-scripts(e.g. [hubot-scripts-kor](https://github.com/castisdev/hubot-scripts-kor))





### Base Docker Image

- node:0.10

### Usage

#### Pull

```
$ sudo docker pull castis/hubot-slack
```

#### Run

```
$ sudo docker run -it --rm -p 9009:9009 castis/hubot-slack
```

#### Run as a daemon with env variables

```
$ sudo docker run -d -p 9009:9009 -e HUBOT_JENKINS_AUTH=yourid:password -e HUBOT_SLACK_TOKEN=token castis/hubot-slack
```
