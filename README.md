# Hugo task management

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