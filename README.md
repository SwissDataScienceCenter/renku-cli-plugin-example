# Renku CLI plugin example

This repository contains an MVP for creating a Renku CLI plugin. It simply extends the `renku` CLI with the `foo` sub-command.

After forking this repository make sure that you fill out the following fields:
 * `setup.py`
	- author
	- author_email
	- name
	- description
	- entry_points: this defines the entry point for a CLI plugin.
	  Make sure that it points to the correct module and function name.
