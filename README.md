# Slack Bot Reporter

[![Test](https://github.com/Tim-Fronsee/slack-bot-reporter/actions/workflows/test.yaml/badge.svg)](https://github.com/Tim-Fronsee/slack-bot-reporter/actions/workflows/test.yaml)

Simplified GitHub Action for Reporting a completed job's status.
Output is a simple message with a color bar representing the status, and a link to the GitHub Actions Build.

### Required Inputs

`channel-id`
`title`

### Optional inputs

`job-status`

### Required Secrets

`SLACK_BOT_TOKEN`

### GitHub Actions Dependencies

[haya14busa/action-cond@v1.0.0](https://github.com/haya14busa/action-cond)

[slackapi/slack-github-action@v1.19.0](https://github.com/slackapi/slack-github-action)
