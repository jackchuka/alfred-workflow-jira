# Jiralfred - Alfred Workflow for [go-jira/jira](https://github.com/go-jira/jira)

<img src="./icon.png" alt="logo" width="130"/>

## Demo

![demo](./jialfred.gif)

## Installation

1. Follow https://github.com/go-jira/jira#install installation and login to your jira server
2. download [Jiralfred.alfredworkflow](Jiralfred.alfredworkflow) file
3. update environment variable PATH_TO_JIRA ie. `/Users/username/bin/jira`

## Usage

User `jiraf` keyword and enter an issue number, ex. `PROJ-1`, followed by supported command. 

Current supports:
* `labels add`
* `label remove`
* `move` - alias of transition
* `transitions` - list all possible transition state
* `browse` - open an issue on the web browser
