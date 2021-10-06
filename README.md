# Maubot Manager

This repo contains files to run an instance of the [Maubot Manager](https://docs.mau.fi/maubot/) by Tulir.

Make sure to have Docker & Docker-Compose installed.

## Installation

- Clone the repository
- Copy/Rename the config file in ./data to config.yaml
- Edit the config file to your liking (For a basic setup, just change the password for the admin account)
- Start the manager with `docker-compose up -d`

## Usage

- You can access the webinterface at `http://IPADDRESS:29316/_matrix/maubot`
- Login with the maubot_admin credentials
- Setup your new/existing bot account as a client
- Upload your plugins as required
- Setup a new instance using your newly created client and uploaded plugin
- Configure the plugin as required
- Profit

## Information

- To update a plugin, just upload the new version. The instance restarts itself
- You can use a reverse proxy to enable TLS, if you want to make the frontend public 
