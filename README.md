# fischer_technik

This repository contains a description of the fischertechnik assembly line.
The document is written in LaTeX and contains functional design specification for the Siemens S7-1500 PLC and the digital twin as both interface with OPC-UA

The **workflow** to work within this repository
- **Fork** the [original repository](https://github.com/aparajita07/fischer_technik) to your own account.
- Clone the repository: ```git clone *accountURL*/fischer_technik```.
- Setup upstream repo: ```git remote add upstream https://github.com/aparajita07/fischer_technik``` (if you are in a subtask, use the account of the subtask leader).
- Make changes on your computer
	- `git add *`
	- `git commit`
	- `git push  origin devBranch`, where origin points to your forked repository.
- Make a pull request from the GitHub site.
- You should sync your copy of the original repository before making changes (so that you are up to date) with a ``` git pull upstream```, where upstream refers to the original cloud repository's *devBranch*.
