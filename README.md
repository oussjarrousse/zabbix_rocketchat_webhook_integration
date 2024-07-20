# Zabbix RocketChat Webhook Integration

This script integrates Zabbix with RocketChat to automatically send notifications to a RocketChat channel using RocketChat webhooks.

The official Zabbix RocketChat integration, that requires a RocketChat user id, and a valid user access token, and the name of the channel  that  Zabbix should send messages to and it uses the RocketChat api to send messages on behalf  of that user from the Zabbix server. 

Unlike the official Zabbix RocketChat integration, this integration uses RocketChat webhooks facility.

## Installation

No installation is needed, just import the yml file in the Zabbix mediatypes.

## Usage

Configure the variables `rc_title_link`, `rc_url` and `rc_webhook_token` for this integration in Zabbix.
## Contributing

Contributions are welcome. Please fork this repository and open a pull request to add more features, fix bugs, or enhance the documentation.

## License

GPL 3.0
