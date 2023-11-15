# Slacktion

This repository contains a simple example of a workflow to call the Slack API
and send messages to a Slack channel. In this example, reminders are sent to a
channel when users have open PRs that are more than 1, 3, and 5 days old.

Check it out [here](.github/workflows/slacktion.yml)!

## Slack Setup

This example makes use of a Slack app and webhook to post to a channel. For
information on setting this up, see the
[Slack documentation](https://slack.com/help/articles/13345326945043-Build-apps-with-Slacks-developer-tools).

## GitHub Setup

Create the following GitHub Actions secrets:

| Name                | Description     |
| ------------------- | --------------- | ---------------------------------------------- |
| `SLACK_WEBHOOK_URL` | The webhook URL | `https://hooks.slack.com/triggers/ABC/123/XYZ` |
| `SLACK_CHANNEL_ID`  | The channel ID  | `C123XYZ456DEF`                                |
