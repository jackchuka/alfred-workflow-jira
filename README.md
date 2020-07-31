# Jiralfred - Alfred Workflow for [go-jira/jira](https://github.com/go-jira/jira)

<img src="./icon.png" alt="logo" width="130"/>

## Demo

![demo](./jialfred.gif)

## Installation

1. Install go-jira/jira by `GO111MODULE=on go get github.com/go-jira/jira/cmd/jira`.
2. Download [Jiralfred.alfredworkflow](Jiralfred.alfredworkflow) file and open the file.
3. Update Alfred workflow environment variable `PATH_TO_JIRA` to your jira executable ie. `{$GOPATH}/bin/jira`.
4. Run `jirasetup` command and enter Jira subdomain and your email (this is one time operation).
5. Create Jira API token from https://id.atlassian.com/manage-profile/security/api-tokens.
6. Register the token by `jiratoken {token}` .

*If something is goes wrong please refer to https://github.com/go-jira/jira#install.

## Usage

### Issue Operations

User `jiraf` keyword and enter an issue, ex. `PROJ-1`, followed by supported command.

Current supports:

* `labels add`
* `label remove`
* `move` - alias of transition
* `transitions` - list all possible transition state
* `browse` - open an issue on the web browser

### Bulk Transition

User `jirabt` keyword and enter issues divided by space, ex. `PROJ-1 PROJ-2`, followed by state.
