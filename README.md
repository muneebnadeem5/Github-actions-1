#Level of variables

## Step Level 

Workflow fileEnv variable Repo level.yml

## Job Level 

Workflow file Env variable JOB level.yml

## Job Level 

Workflow fileEnv variable Workflow level.yml


## JOB concurrency

### By group or Cancel-in-progress
Group: is just a name to control concurrency by the name
------------------------
Cancel-in-progress:
If we pass "True" in the Cancel-in-progress the current running job will stop and new take place".
If we pass "False" in the Cancel-in-progress the current running job will continue and new job will PAUSE till the first Workflow.
