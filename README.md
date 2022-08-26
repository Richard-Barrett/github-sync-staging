# github-sync-staging

Staging Repo for GitHub Sync Master

[![Greetings](https://github.com/Richard-Barrett/github-sync-staging/actions/workflows/greetings.yml/badge.svg)](https://github.com/Richard-Barrett/github-sync-staging/actions/workflows/greetings.yml)
[![Sync to GitHub-Sync-Master](https://github.com/Richard-Barrett/github-sync-staging/actions/workflows/sync.yml/badge.svg)](https://github.com/Richard-Barrett/github-sync-staging/actions/workflows/sync.yml)

## How This Works

This repository always merges forcefully into a master remote repository, meaning you have two repositories that are always identical. It's kind of scary, and I don't recommend using this, you should have one repository and then it should make or publish changes to 3 different environments and then make changes only if the deployment succeeds not a direct sync to another repostiory, but if you are concerned about code drift...this always duplicates any changes to the remote repository by use of GitHub Actions.
