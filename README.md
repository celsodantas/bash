# Bash

These are my bash scripts for daily usage.

Just clone this repository to `~/.bash` and
add the following line to your `~/.bash_profile`
or equivalent file:

  source ~/.bash/init.sh

# Git config

Cool thing to add is some Git colors. Just copy this to your `~/.gitconfig` file:


	[color]
		branch = auto
		diff = auto
		status = auto
	[color "branch"]
		current = yellow reverse
		local = yellow
		remote = green
	[color "diff"]
		meta = yellow bold
		frag = magenta bold
		old = red
		new = cyan
	[color "status"]
		added = yellow
		changed = green
		untracked = cyan