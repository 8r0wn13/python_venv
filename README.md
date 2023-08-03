# Python Virtual Environment

Virtual environments isolate your projects from other projects and system-wide packages.
You can install specific packages for that each project, without breaking other projects.

## Install, configure and start a virtual environment
The below is focussed on Linux and not on Windows.

First make sure virtualenv is installed:<br>
`pip install virtualenv`

Create a new virtual environment:<br>
`python -m venv <<name_virtual_environment>>`

Activate the virtual environment:<br>
`source <<name_virtual_environment>>/bin/activate`

To deactivate the environment:<br>
`deactivate`

To delete a virtual environment (make sure it is first deactivated):<br>
`rm -r <<name_virtual_environment>>`

### Virtual environments vs. other options
1. Buy a new pc/laptop --> very expensive
2. Create a virtual machine --> requires a lot of work to install the OS and applications needed
3. Containerization, like Docker and Kubernetes, can be powerful and are a good alternative
