# The Skybert Dashboard

## Usage

```perl
$ skybert-dash > ~/www/index.html
```

Here's an example `~/.skybert-dash.conf`, reading the password from
the [pass Unix password manager](https://www.passwordstore.org/) under
the path `jira/lisa`:

```ini
SD_JIRA_BASE_URI=https://jira.example.com
SD_JIRA_USER=lisa
SD_JIRA_ISSUE_COUNT=15
SD_JIRA_AUTH=${SD_JIRA_USER}:$(pass jira/lisa)
```

The settings can also be set as Unix environment variables.
