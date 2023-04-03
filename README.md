# git actions

Jobs Features:
- Workflows must have at least one job.
- Each job must have a unique identifier.
- Job identifiers must start with the letter or underscore.
- Jobs run in parallel by default.

Runners:
- runs-on: os name to be used for building a job.

Steps:
- Steps are tasks within a job.
- Steps run as processes on the compute resource.
- Steps can run commands or actions.
- Steps are arrays.

Adding Dependencies:
- needs: Identifies one or more jobs that must complete successfully before a job will run.