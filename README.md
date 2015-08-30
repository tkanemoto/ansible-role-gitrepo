# Ansible Role: Git-Repo

Installs Repo, a tool that helps to manage the many Git repositories, on any RHEL/CentOS or Debian/Ubuntu Linux system.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    gitrepo_install_path: "/usr/local/bin"

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - { role: tkanemoto.gitrepo }

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Takeshi Kanemoto](http://tkanemoto.ddns.net/).
