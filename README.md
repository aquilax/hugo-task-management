# Hugo task management

[![Netlify Status](https://api.netlify.com/api/v1/badges/0b3440bc-a273-493c-b081-b602f7bf741c/deploy-status)](https://app.netlify.com/sites/hugo-task-management/deploys)

This is an experiment to run task management system using the [Hugo](https://gohugo.io/) static site tool.

You can find a demo dashboard here: https://hugo-task-management.netlify.app/

## Configuration

### config.toml

```toml
[params]
  dashboardColumns = ["TODO", "Blocked", "Progress", "Review", "Done"]
  paramsInTaskDetail = ["status", "date", "projects", "teams", "users", "tags", "completedAt"]
  defaultStatus = "TODO"
  defaultTeams = []
  defaultUsers = ["aquilax"]
  defaultProjects = ["Hugo Task Management"]
  defaultTags = []
```

* `dashboardColumns` is a list of the columns that will be available on the home page dashboard
* `paramsInTaskDetail` list of task parameters to be shown in task detail view
* `defaultStatus` default status to use when creating a new task
* `defaultTeams` default list of team names to set when creating a new task
* `defaultUsers` default list of user names to set when creating a new task
* `defaultProject` default list of projects to add the task to
* `defaultTags` default list of tags to add the task to

## Usage

### Creating a new task

```
hugo new task/PREFIX-0000001.md"
```
where `PREFIX-0000001` is the the identifier of the task
