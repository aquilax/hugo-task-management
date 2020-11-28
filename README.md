# Hugo task management

[![Netlify Status](https://api.netlify.com/api/v1/badges/0b3440bc-a273-493c-b081-b602f7bf741c/deploy-status)](https://app.netlify.com/sites/hugo-task-management/deploys)

This is an experiment to run task management system using the [Hugo](https://gohugo.io/) static site tool.

You can find a demo dashboard here: https://hugo-task-management.netlify.app/

## Configuration

### config.toml

```toml
[params]
  dashboardColumns = ["TODO", "Blocked", "In progress", "In Review", "Done"]
```

* `dashboardColumns` is a list of the columns that will be available on the home page dashboard


## TODO
* adding new task
* changing task status
* comment on task
* tasks assigned to user
* projects page