# ansible-freenas

An Ansible role to manage FreeNAS via API

## Testing

I highly recommend testing prior to running against an existing environment. I
am not responsible for any loss data! This role is still under extensive testing.
To test a setup, I highly recommend using my [FreeNAS Vagrant box](https://github.com/mrlesmithjr/vagrant-box-templates) which is what is being used in developing this role.

## Requirements

### API Key
Create and API key and store it in a variable called ```truenas_api_key```.


## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

## Example Playbook

[tests/test.yml](tests/test.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- <mailto:mrlesmithjr@gmail.com>
