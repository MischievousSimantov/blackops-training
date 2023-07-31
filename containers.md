**Intro to Containers**

-   Read about containers, their uses and how they achieve isolation.

    Answer the following questions:

    -   What is the difference between a container and a vm? When will I
        > want to use each one?

        > What is the difference between the isolation of the container
        > and the vm?

**The Dockerfile and building images**

-   Read about container images, docker, the dockerfile and the process
    of building images in docker.

    Answer the following questions:

    -   What is a image? What are layers in a image?

        > Can you only build images using docker,? If not give another
        > example.

        > What is the FROM in the docker file?

        > What is multistage build?

        > What is the difference between CMD and ENTRYPOINT?

**Basic Docker Commands**

-   Read about the following commands:

    -   Build

        > Run

        > Ps

        > Images

        > Exec

        > Logs

        > Stop

        > Start

        > Inspect

        > Info

        > Save

        > Load

**Advanced container layers**

-   Read about container layers, overlayfs, scratch container and docker
    images best practices.

    Ask the trainer for the dockerfile that requires fixing, first
    identify the errors in the dockerfile afterwards fix the identified
    issues so that the image still runs, DO NOT SEARCH FOR THE ORIGINAL
    IMAGE.

**OCI**

-   Read about the oci, Rodman, buildha.

    Answer the following questions:

    -   What are the differences between docker buildha and podman?

        > What is the difference between docker and docker-ce

**Container networking**

-   Read about each of the network drivers and explain what is each one,
    and when we will use each one:

    -   Bridge

        > Host

        > None

        > Overlay

**Container registries**

-   Read about container registries, docker hub, nexus, image tagging.

    Read about the following commands:

    -   Docker tag

        > Docker login

        > Docker push

        > Docker pull

    Answer the following questions:

    -   What is the difference between a local and a remote register?

        > To what registry do you connect when you type docker login?

    Create a instance of a nexus docker registry on your machine.

    Create a dockerfile that creates a image of the chat that you
    created and put it in the git repo.

    Tag the built image and push it to the nexus instance that you
    created

**Final drill**

-   Read about reverse proxies, explain why we use them and put the chat
    server behind a reverse proxy, put the configurations in git

    Read about docker compose and create a docker compose that sets up
    the whole chat environment including the reverse proxy
