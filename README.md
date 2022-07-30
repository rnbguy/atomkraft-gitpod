# atomkraft [![Try on Gitpod](https://img.shields.io/badge/Atomkraft-Try%20on%20Gitpod-FFB45B?logo=gitpod)](https://gitpod.io/#https://github.com/rnbguy/atomkraft-gitpod)

Sets up [`atomkraft`](https://github.com/informalsystems/atomkraft) in a Gitpod workspace.

## Instruction

When the workspace is ready, you may execute the following commands to initialize a project.

```
atomkraft init my_project
cd my_project
```

This will initialize a Poetry project with a boilerplate. Now you can continue to add your code to complete the project.

But if you want to kick-start a sample token-transfer project, you may execute,

```
poetry run bash ../samples/transfer.sh
```

This will complete the project with a model, ten traces, and a complete reactor.

You may want to look inside `samples/transfer.sh` to understand the necessary parts to complete a project.
