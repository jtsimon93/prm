# PRM
PRM is a free and open source software for the management of personal relationships. It's like a CRM but for your personal life. It's a tool to help you keep track of your relationships with everyone in your life. 

All data is stored locally on your machine and is not shared with anyone.

## Development
PRM is in the beginning stages of active development. If you would like to contribute, please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information.

## Features
- [x] View list of contacts, add, and view single contacts

## Planned Features
- [ ] Complete Contact Management
- [ ] Contact Notes
- [ ] Contact Reminders
- [ ] Contact Events
- [ ] Contact Tasks
- [ ] Contact Files
- [ ] Contact Tags

## License
PRM is licensed under the GNU General Public License v3.0. You can view the license [here](LICENSE).

### Qt
PRM is built using the Qt framework. You can download the Qt framework [here](https://www.qt.io/download).

### Building
To build PRM, you will need to have the Qt framework installed. You can download the Qt framework [here](https://www.qt.io/download).

#### Prerequisites

- CMake 3.28 or higher
- vcpkg (for dependency management)
- Qt 6.7.0
- Install sqlite-modern-cpp using vcpkg
- Install sqlite3 using vcpkg
- Set `CMAKE_TOOLCHAIN_FILE` to the vcpkg toolchain file
- Set `CMAKE_PREFIX_PATH` to the Qt installation directory
