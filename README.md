# bluemail

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/bluemail)
[![General Workflow](https://github.com/rolehippie/bluemail/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/bluemail/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/bluemail/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/bluemail/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/bluemail/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/bluemail/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/bluemail)](https://github.com/rolehippie/bluemail/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.bluemail-blue)](https://galaxy.ansible.com/rolehippie/bluemail)

Ansible role to install bluemail email client.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [bluemail_keyring](#bluemail_keyring)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### bluemail_keyring

Path for the repository keyring

#### Default value

```YAML
bluemail_keyring: /usr/share/keyrings/bluemail-archive-keyring.gpg
```

## Discovered Tags

**_bluemail_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
