# gh-create

A bash script that creates a repo on Github from the command line

## Installation

### wget
`wget -O - https://raw.githubusercontent.com/AhmedBoustani/gh-create/master/gh-create > gh-create`  
`chmod +x gh-create`  
`sudo ln -s gh-create /usr/bin`

## Set up
1. Generate Github token https://docs.cachethq.io/v1.0/docs/github-oauth-token
2. `git config --global github.token <token>`

## Usage
`gh-create <repo_name (optional)>`  
Then follow prompt.  
Note: Make sure that the repository name is unique inside your 

## Dependencies
- curl
