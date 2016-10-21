# Dockerfiles used on `archivebot.at.ninjawedding.org`

This repository contains Dockerfiles used on the [ArchiveTeam ArchiveBot](https://github.com/ArchiveTeam/ArchiveBot) deployment at `archivebot.at.ninjawedding.org`.

It exists mostly for my convenience and is unlikely to be useful anywhere else.

## Contents

* `certbot`: A Docker image based on Alpine Linux containing the `certbot` Let's Encrypt client
* `ssh-tunnel`: A Docker image based on Alpine Linux containing an `sshd` for connecting to the ArchiveBot Redis instance
* `stunnel`: A Docker image based on Alpine Linux containing an `stunnel` installation
