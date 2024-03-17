# espanso_cenz with claude enable!

## Install Package
```shell
espanso install basic-emojis
```

## MacOS
```
cd /Users/cenzwong/Library/Application Support/espanso
git clone https://github.com/cenzwong/espanso_cenz.git .
```


# Espanso with Claude
1. Create a file called .env and put your claude API in it.
```bash
ANTHROPIC_API_KEY="sk-ant-api03--"
```
2. Make sure your bash could run `jq` and `tr`. The JSON Query Engine and the Trim utility.

## Usage

`:claude:` : This would pop up a formm ask you to type your prompt. This is good to asked generic question/ brain storming
`:claude-grammar` : This will read the sentence you stored in the clipbaord and help you to rewrite to make it look nicer.

> Using claude would incur cost

# Debug with espanso
You could run `espanso log` to see the output of the cmd