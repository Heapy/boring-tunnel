# Boring Tunnel

Simple tunneling solution for personal use.

## Server Configuration

| Parameter | Default | Required | Description                                                                             |
|-----------|---------|----------|-----------------------------------------------------------------------------------------|
| MODE      | client  | true     | Describes mode in which application running, set to `server` to run as tunneling server |
| TOKEN     | none    | true     | Token to authenticate listening requests                                                |
| PORT      | 8080    | false    | Port on which application will be listening                                             |
| HOST      | 0.0.0.0 | false    | Host on which application will be listening                                             |

## Client Configuration

| Parameter  | Default | Required | Description                                                                                     |
|------------|---------|----------|-------------------------------------------------------------------------------------------------|
| MODE       | client  | false    | Describes mode in which application running, omit or set to `client` to run as tunneling client |
| TOKEN      | none    | true     | Token to access tunneling server API                                                            |
| SERVER_URL | none    | true     | URL to tunneling server API                                                                     |
| LOCAL_URL  | none    | true     | URL to local application                                                                        |
