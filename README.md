# PteroPy

## WARNING: the library is under development and may not work as described below

~~PteroPy is a Python library that serves as an API wrapper for the Pterodactyl panel. It provides an easy and convenient way to interact with the Pterodactyl API and manage your game servers.~~

## Features

- ~~Authenticate and manage API tokens~~
- ~~Get information about servers, users, and nodes~~
- ~~Create, update, and delete servers~~
- ~~Start, stop, restart, and reinstall servers~~
- ~~Manage server files and directories~~
- ~~Execute commands on servers~~
- ~~And much more!~~

## Installation

~~To install PteroPy, simply use pip:~~

```bash
pip install PteroPy
```

## Usage

~~Here's a simple example of how to use PteroPy to interact with the Pterodactyl API:~~

```python
import PteroPy

# Create a client instance
client = PteroPy.Client(api_url='https://your-panel-url.com', api_key='your-api-key')

# Get information about a server
server_info = client.get_server_info(server_id='your-server-id')
print(server_info)

# Start the server
client.start_server(server_id='your-server-id')

# Execute a command on the server
output = client.send_command(server_id='your-server-id', command='say Hello, server!')
print(output)
```

~~For more detailed documentation and examples, please refer to the [official PteroPy documentation](https://github.com/LeaveHosting/PteroPy).~~

## Contributions

~~Contributions to PteroPy are always welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the [GitHub repository](https://github.com/LeaveHosting/PteroPy).~~

## License

~~PteroPy is licensed under the MIT License. See the [LICENSE](https://github.com/LeaveHosting/PteroPy/blob/main/LICENSE) file for more information.~~

## Acknowledgements

~~Special thanks to the Pterodactyl team for providing the amazing panel and API that inspired this library.~~

~~Feel free to reach out if you have any questions or need further assistance. Happy coding with PteroPy!~~
