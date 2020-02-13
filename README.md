![Current tag](https://img.shields.io/github/tag/thermistor/thermistor-ansible-yarn.svg)

# yarn

Install yarn from the yarn repo.

## Vars

Here are the defaults:

    yarn_repo_apt_key: 'https://dl.yarnpkg.com/debian/pubkey.gpg'
    yarn_repo: 'deb https://dl.yarnpkg.com/debian/ stable main'

## Examples

Here is the basic usage:

    - hosts: servers
      roles:
        - role: thermistor.yarn
