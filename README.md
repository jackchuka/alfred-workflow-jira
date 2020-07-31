# Jiralfred - Alfred Workflow for [go-jira/jira](https://github.com/go-jira/jira)

<img src="https://github.com/jackchuka/alfred-workflow-jira/blob/master/icon.png?raw=true/icon.png" alt="logo" width="130"/>

## Demo

![demo](https://github.com/jackchuka/alfred-workflow-jira/blob/master/jialfred.gif?raw=true)

## Installation

1. Download the workflow from [the latest release](https://github.com/jackchuka/alfred-workflow-jira/releases/latest), and open the file.
1. Run `jirasetup` command and enter Jira subdomain and your email.
1. Create Jira API token from https://id.atlassian.com/manage-profile/security/api-tokens.
1. Register the token by `jiratoken {token}` .

## Usage

### Issue Operations

User `jiraf` keyword and enter an issue, ex. `PROJ-1`, followed by supported command.

#### Current supports:

* `labels add`
* `label remove`
* `move` - alias of transition
* `transitions` - list all possible transition state
* `browse` - open an issue on the web browser

### Bulk Transition

User `jirabt` keyword and enter issues divided by space, ex. `PROJ-1 PROJ-2`, followed by state.
