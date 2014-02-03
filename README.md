Issues
======

This repository is used to manage any and all issues relating to the [Codio](https://codio.com) platform.


## Workflow

1. A new issue is created.
2. The Issue Master assigns the issue one or more labels. For example, is it a bug, feature or improvement?
3. The issue is assigned to a developer, or a developer starts work on the issue and assigns it to himself.
4. Pull requests are created on the relevant repo and associated back to the issue via Github’s comment links. For example `Refs #123`. The `fixes` and `resolves` keywords should not be used, as that would close the issue when just one PR is merged. This is bad, as there may be more PR’s that make up the issue.
5. A `QA` label is assigned to the issue once development has completed and it is ready for QA.
6. QA adds comments, tasks and questions to the issue. Any bugs or todo items should be created using Github’s check boxes.
