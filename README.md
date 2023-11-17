# 42_INCEPTION

## How did we delevop applications before containers?

### Usually when you have a team of developers working at a project you would need to have to install most of the services on your OS directly.

BEFORE CONTAINERS:

-> Dev team produces artifacts and sets of instructions on how to install the applications.

PROBLEM: you need to configure and install everything on each device leading to a high chance of dependency version conflicts, misunderstandings, missing details and so on...

This leads to a lot of error happening because of the sheer amount of steps to install each service. Also, the process results tedious and time consuming

### With containers, you don't need to install any of the service because the container is its own layer of isolated environment

So as a developer, all you need to do is go ahead and check out the container repository to download the specific container to run in your machine with a specific command that installs all the programs you need, no bugs allowed.

With containers the process is highly simplified because now you have developers and application encapsulated in one single environment

All you do is run a Docker command to fetch the repository and you are good to go.


