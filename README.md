# Quality of life scripts

```shell
git clone git@github.com:tracphil/.bin.git ~/.bin
```

## `awsinfo`

Prerequisite: `python3`, `boto3`

Returns account number, region, account alias

## `decode-message`

Prerequisite: `awscli`, `jq`

Use when Amazon gives you an _"Encoded authorization failure message"_ and you need to turn it into something readable.

## `latest-python`

Prerequisite: `pyenv`

Downloads, compiles and installs the latest python and sets global python version to use.
