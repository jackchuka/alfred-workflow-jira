# Jiralfred - Alfred Workflow for [go-jira/jira](https://github.com/go-jira/jira)

<img src="./icon.png" alt="logo" width="130"/>

## Demo

![demo](./jialfred.gif)

## Installation

1. Follow https://github.com/go-jira/jira#install installation and login to your jira server
2. download [Jiralfred.alfredworkflow](Jiralfred.alfredworkflow) file
3. update environment variable `PATH_TO_JIRA` ie. `/Users/username/bin/jira`

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
