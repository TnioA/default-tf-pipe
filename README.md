# default-tf-pipe


Workflow

DEV:

PR -> develop -> gh_actions -> deploy -> provider(ENV=DEV) -> state -> S3 bucket

PROD:

PR -> main -> gh_actions -> deploy -> provider(ENV=PROD) -> state -> S3 bucket