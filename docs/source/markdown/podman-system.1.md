% podman-system(1)

## NAME
podman\-system - Manage podman

## SYNOPSIS
**podman system** *subcommand*

## DESCRIPTION
The system command allows you to manage the podman systems

## COMMANDS

| Command    | Man Page                                                     | Description                                                                  |
| -------    | ---------------------------------------------------          | ---------------------------------------------------------------------------- |
| df         | [podman-system-df(1)](podman-system-df.1.md)                 | Show podman disk usage.                                                      |
| connection | [podman-system-connection(1)](podman-system-connection.1.md) | Record ssh destination for remote podman service.                            |
| info       | [podman-system-info(1)](podman-info.1.md)                    | Displays Podman related system information.                                  |
| migrate    | [podman-system-migrate(1)](podman-system-migrate.1.md)       | Migrate existing containers to a new podman version.                         |
| prune      | [podman-system-prune(1)](podman-system-prune.1.md)           | Remove all unused container, image and volume data.                          |
| renumber   | [podman-system-renumber(1)](podman-system-renumber.1.md)     | Migrate lock numbers to handle a change in maximum number of locks.          |
| reset      | [podman-system-reset(1)](podman-system-reset.1.md)           | Reset storage back to initial state.                                         |
| service    | [podman-service(1)](podman-system-service.1.md)              | Run an API service                                                           |


## SEE ALSO
podman(1)