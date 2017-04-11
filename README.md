# smokeping-generic
Generic Smokeping Ansible Development


This ansible project will update the smokeping servers to the lastest repo version.  The goal of this project is to streamline the maintenance and backup of smokeping master and slave servers configurations.

Specifically this project will:

1. Synchronize with the remote repository
2. Parse hierarchy of files destined to each server
3. Decide which files are destined to which servers
4. Decide which files need to be updated
5. SCP the repo files local to the ansible server each smokeping server
6. Restart the smokeping service
