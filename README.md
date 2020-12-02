# resource-core

Collection of Go packages and utilities for creating Concourse Resources in Go

## History

It was originally developed by @christophermancini while employed by DigitalOcean @ [digitalocean/concourse-resource-library](https://github.com/digitalocean/concourse-resource-library). It was updated to make it more generic (removed Artifactory packages and other changes) and rereleased @ [concourse-contributors/resource-core](https://github.com/concourse-contributors/resource-core).

## Resource Bootstrapping

This library contains a simple utility for bootstrapping new resources written in Go. It assumes the directory for the resource has not been created.

```bash
go run main.go new -r git@github.com:christophermancini/artifactory-resource.git -m github.com/christophermancini/artifactory-resource ../artifactory-resource
```
