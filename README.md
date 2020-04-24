# Memo

Trigger an github action using [repository_dispatch](https://help.github.com/en/actions/reference/events-that-trigger-workflows#external-events-repository_dispatch) event.

```sh
curl -u lightyears1998:$MY_GITHUB_PERSONAL_ACCESS_TOEKN_WITH_REPO_SCOPE -H "Content-Type:application/json" -X POST -d '{"event_type": "fire-missile"}' https://api.github.com/repos/lightyears1998/test-github-actions-event-target/dispatches
```
