#### Trigger Github Actions on PR comments
There are several GHA events related to PR comments, most of which only run **IFF** the workflow file is in the default branch, 
typically `master`.` GHA documentation on [trigger issue_comment](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#issue_comment) or [events-that-trigger-workflows]https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows says:
```
Note: This event will only trigger a workflow run if the workflow file is on the default branch.
```

This repo develops an action that runs **IFF** in the default branch.
