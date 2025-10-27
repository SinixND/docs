# General information
Github Actions provide automated execution of an event triggered `workflow` (aka. pipeline), consisting of serial and/or parallel `Jobs` which itself consists of `steps` executed by a `runner` provided by github. These steps can eg. also run scripts.

Defined in a `.yaml` file per workflow in .github/workflows.
**Find example in the respective folder within this repo**

# Events
Workflows can be triggered manually (`workflow_dispatch`)or by events, eg. pushes, create/update pull requests, cron schedules and many more

# Steps
Steps can have different types:
- `inline/local` ("run")
- `actions` ("uses")

# Jobs
Jobs can be run parallel (default) or serialized (if needed) by specifying dependencies 

# Resources
[Simple CI/CD - artful bytes](https:/youtube.com/watch?v=dh1NFAIoZCI)
