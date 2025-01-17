# Alfresco Extension for Docker Desktop

Experimental Docker Extension to deploy Alfresco Stack using the Docker Desktop interface

## Prerequisites

Runtime Requirements:

* [Docker Desktop 4.8.0 or later](https://www.docker.com/products/docker-desktop/) with Docker Extensions enabled

Development Recommendations:

* [React reference](https://reactjs.org)
* [Docker Extensions CLI](https://github.com/docker/extensions-sdk)

## Enable Docker Extensions

In Docker Desktop, go to `Preferences > Extensions` and check `Enable Docker Extensions`

## Running the extension

Since this Docker Extensions hasn't been yet published, it's required to build and deploy it locally from source code.

Run the following command to build and install the local extension:

```sh
make build-install
```

## Using the Extension

From the Docker Dashboard you can now navigate to the Extensions section.

It should now list **Alfresco** as one of the available extensions.

Click on **Run** button to run **Alfresco** in Docker and use http://localhost:8080/alfresco URL in your browser once the deployment is ready.

If you want to un-deploy Alfresco, click **Stop** button.
