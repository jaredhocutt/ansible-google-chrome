# Google Chrome

This role handles configuring the Google Chrome repository and then install
Google Chrome.

## Requirements

The hosts you are targeting should have the following packages:

- python >= 2.6
- python-dnf

## Role Variables

None

## Dependencies

None

## Example Playbook


```yaml
- hosts: servers
  roles:
    - role: jaredhocutt.google_chrome
```

## License

MIT

## Author Information

Jared Hocutt (@jaredhocutt)
