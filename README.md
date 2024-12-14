# Microcks playground

This project is a playground for testing [Microcks](https://microcks.io/).
As its website states, "[Microck is the] The open source, cloud native tool for
API Mocking and Testing."

This project intends to document how to set up and use Microcks to mock HTTP
APIs and speed up the development of API functionalities.
The majority of the content on this page comes from the
[Get Started](https://microcks.io/documentation/tutorials/getting-started/)
tutorial on the Microcks website.

## Launch Microcks

To launch Microrocks locally, you can use Docker by running this command.

```shell
docker run --name microcks -p 8585:8080 -it --rm quay.io/microcks/microcks-uber:latest-native
```

## Troubleshooting

To make the tutorial work on MacOS, you may need to configure hostname
resolution for DNS name `host.docker.internal`.
You can do it by adding the following entry in `/etc/hosts` file.

```none
# This enable host.docker.internal DNS resolution on
# MacOs.
127.0.0.1       host.docker.internal
```
