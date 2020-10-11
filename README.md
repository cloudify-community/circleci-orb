# CircleCI Orb

This repository contains Cloudify's Orb definition for CircleCI.

## Prerequisites

Your CircleCI project must have the following environment variables defined, containing
DockerHub authentication information:

* `DOCKERHUB_USERNAME`
* `DOCKERHUB_PASSWORD`

These can be set at the project level, or through a CircleCI Context.

## More Information

Refer to the [official product documentation](https://docs.cloudify.co/latest/working_with/integration/)
for information about Cloudify's integration with CI/CD tools, including information that pertains
to CircleCI.
