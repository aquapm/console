# <%= @project_name_camel_case %>

**TODO: Add description**

## Usage

Project can be built using:

```bash
$ mix escript.build
```

command.

It will generate `./<%= @project_name_camel_case %>` executable, that can be then called as common executable:

```bash
$ ./<%= @project_name_camel_case %>
```

This executable can be moved across entire system, or even be passed to another computers.

```bash
$ cp ./<%= @project_name_camel_case %> ~
$ ~/<%= @project_name_camel_case %>
```

**NOTE!**: This executable requires installed **Erlang Virtual Machins** to be installed on the execution system.