# ECP Coding Challenge

The sample code demonstrate how to build a simple Flask RESTful API with Docker-Compose.

## Requirements

To build this sample environment you will need [docker] and [docker compose].

## Deploy and Run

After cloning this repository, you can type the following command to start the simple app:

```sh
make install
```

Then simply visit [http://127.0.0.1:5000/info][app]

### Todos

 - Render the json output with HTML
 - Build testing framework

License
----

MIT

[docker]:  https://docs.docker.com/install/
[docker compose]: https://docs.docker.com/compose/install/
[python]: https://www.python.org/downloads/
[pip]: https://pypi.org/project/pip/
[app]: http://127.0.0.1:5000/info