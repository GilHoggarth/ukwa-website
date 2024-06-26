# UKWA Website holding page

To build the UKWA website holding page as a container, run:

```
podman build -t <TAG-NAME> .
```

_TAG-NAME will define the container service name and has no affect to the UKWA website._


To run the container image:

```
podman run -p 8090:80 -d <TAG-NAME>
```
