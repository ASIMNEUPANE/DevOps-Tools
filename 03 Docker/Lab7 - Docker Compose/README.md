# <b>Lab7: Docker Compose</b>
- <b>`Compose`</b> is a tool for defining and running multi-container Docker applications.
- With <b>`Compose`</b>, you use a YAML file to configure your application’s services.
- Then, with a single command, you create and start all the services from your configuration.
- <b>`Compose`</b> works in all environments: 
    - <b>production</b>
    - <b>staging</b>
    - <b>development</b>
    - <b>testing</b>, <b>as well as CI workflows</b>.


## Docker Compose Installation
- In [Lab1](https://github.com/TheSpiritMan/DevOps-Tools/tree/main/03%20Docker/Lab1%20-%20Docker%20Installation) of Docker, we have already installed `Docker` and `Docker-Compose`.
- To install `Docker-Compose` in <b>Ubuntu</b>:
    ```
    sudo apt install docker-compose -y
    ```
- If you want to install `Docker-Compose` in other Operating System, visit this [link](https://docs.docker.com/compose/install/).


## Help Manual Of Docker-Compose
- Below is a help list of `docker-compose`:
    ```
    Usage:
    docker-compose [-f <arg>...] [--profile <name>...] [options] [--] [COMMAND] [ARGS...]
    docker-compose -h|--help

    Options:
    -f, --file FILE             Specify an alternate compose file
                                (default: docker-compose.yml)
    -p, --project-name NAME     Specify an alternate project name
                                (default: directory name)
    --profile NAME              Specify a profile to enable
    -c, --context NAME          Specify a context name
    --verbose                   Show more output
    --log-level LEVEL           Set log level (DEBUG, INFO, WARNING, ERROR, CRITICAL)
    --ansi (never|always|auto)  Control when to print ANSI control characters
    --no-ansi                   Do not print ANSI control characters (DEPRECATED)
    -v, --version               Print version and exit
    -H, --host HOST             Daemon socket to connect to

    --tls                       Use TLS; implied by --tlsverify
    --tlscacert CA_PATH         Trust certs signed only by this CA
    --tlscert CLIENT_CERT_PATH  Path to TLS certificate file
    --tlskey TLS_KEY_PATH       Path to TLS key file
    --tlsverify                 Use TLS and verify the remote
    --skip-hostname-check       Don't check the daemon's hostname against the
                                name specified in the client certificate
    --project-directory PATH    Specify an alternate working directory
                                (default: the path of the Compose file)
    --compatibility             If set, Compose will attempt to convert keys
                                in v3 files to their non-Swarm equivalent (DEPRECATED)
    --env-file PATH             Specify an alternate environment file

    Commands:
    build              Build or rebuild services
    config             Validate and view the Compose file
    create             Create services
    down               Stop and remove resources
    events             Receive real time events from containers
    exec               Execute a command in a running container
    help               Get help on a command
    images             List images
    kill               Kill containers
    logs               View output from containers
    pause              Pause services
    port               Print the public port for a port binding
    ps                 List containers
    pull               Pull service images
    push               Push service images
    restart            Restart services
    rm                 Remove stopped containers
    run                Run a one-off command
    scale              Set number of containers for a service
    start              Start services
    stop               Stop services
    top                Display the running processes
    unpause            Unpause services
    up                 Create and start containers
    version            Show version information and quit
    ```
