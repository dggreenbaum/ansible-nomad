## v1.0.0

- Installs Nomad on each node
- Installs example configuration for server and client
- Installs example init, systemd, and upstart scripts
- Correct versions
- Update Galaxy meta

## v1.0.1

- Remove unused variables
- Update documentation

## v1.0.2

- Enable and start nomad service
- Fixup initial configuration paths
- Update documentation

## v1.1.0

- Prepare role for Galaxy
- Add optional Docker installation support
- Update initial configuration
- Update documentation
- Update start scripts

## v1.1.1

- Switch to galaxy_tags
- Enable CI

## v1.1.2

- Tests run best when they exist!

## v1.1.3

- Fix package name vars

## v1.1.4

- Update supported versions
- Fix up unarchive task quoting

## v1.1.5

- Keyserver quoting

## v1.1.6

- Update OS packages
- Update signing key tasks

## v1.1.7

- Update default variables
- Update supported versions
- Update documentation — now w/ more header meta (h/t @dochang)

## v1.1.8

- Update doc meta

## v1.1.9

- Remove deprecated tasks
- Add conditionals to tasks

## v1.2.0

- Dropping native Docker subsystem support in favor of external role
- Attempting to run nomad as nomad user

## v1.2.1

- Renamed vars to be more in line with Nomad terminology
- Switched to merged config style with base, bootstrap, server, client

## v1.3.0

- Remove Docker majority of bits except for supporting packages, etc.
- Docker will only be installed for Vagrant based clusters via the
  Vagrant provisioner when environment variable `NOMAD_DOCKER_ENABLE="true"`
  is set
- Update start scripts to be smarter about node role
- Add cgroups packages on Debian/Ubuntu
- Run Nomad as root for now

## v1.3.1

- Update/validate CentOS 7 box
- Update documentation
- Update failure cases for CentOS

## v1.3.2

- Disable SELinux when Docker is used

## v1.3.3

- Correct var
- More SELinux config

## v1.4.0

- Nomad 0.5.0
- Automatic SHA determination
- Streamline and split out install, Docker, and SELinux tasks
- Remove deprecated task files
- Establish OS vars
- Update documentation

## v1.4.1

- Nomad 0.5.1
- Add NOMAD_VERSION environment variable
- Fix typo in default variables

## v1.4.2

- Checks for existing packages and summary files
- Nomad 0.5.2

## v1.4.3

- Nomad 0.5.3
