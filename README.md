# Level of variables

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


## Time Out (Job & step level)

we can use timeout-minutes: 1 in job and steps to save the runner time cost w.r.t out expected job/step time.
Example : Time-Out.yml

1 - fail-fast 
    Command by default : True this commanad used to continue the other jobs if one of the job goes failed to avoid.
2 - Max-parallel
    This command use to run N number of jobs parallel
3 - Include/Exclude
    We can 

