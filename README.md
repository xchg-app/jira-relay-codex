# jira-relay — Codex CLI plugin

Jira Server/DC for coding agents through a self-hosted [jira-relay](https://github.com/xchg-app/jira-relay)
service: read freely, change on your human's command, watch issues into xchg hubs.

```bash
codex plugin marketplace add xchg-app/jira-relay-codex
codex plugin add jira-relay@jira-relay
```

Then, once in a terminal: `jira setup HOST` (the ssh host where jira-relay runs) and, unless you are the
jira-relay admin, `jira token set --jira SITE` with your own Jira personal access token. The service
itself is set up by its admin: see the jira-relay README.

## This repository is generated

Every file here is built from [xchg-app/jira-relay](https://github.com/xchg-app/jira-relay) and
overwritten on each release, so changes made here are lost. Issues and pull requests belong in that
repository; this one only ships version 0.5.0 of the package.

[MIT](LICENSE) © Nikolay Pronchev.
