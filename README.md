# Simple Python HTTP Server

This is a lightweight HTTP server written in Python using the `socket` module. It listens for incoming HTTP requests on port **8080** and serves static HTML files based on the request path

## Getting Started

### Prerequisites

- Python 3.x

### Running the Server

To run the server, `cd` into the cloned repo and open up a terminal. Run the following commond:

```bash
python3 main.py
```

On windows

```bash
python main.py
```

Upon Starting, the server will print:

```bash
http-server >> Listening on port 8080...
```

It will then wait for client connections.

Open a browser of choice and visit **localhost:8080** to see the contents of index.html.

Any other paths or unsupported method (e.g., POST) will return an error.

### Notes

- This server is for **educational and testing purposes only**. It lacks security features and is not suitable for production use
- Be sure to close the server with Ctrl+C when done

### Extra Notes
- There definetly isn't anything hidden in **localhost:8080/secret** 🫣
