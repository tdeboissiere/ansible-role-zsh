# Ansible role 'zsh'

An Ansible role for setting up zsh and oh-my-zsh. It will add the themes 
 'spaceship' and 'bullet-train' (used) as well as some useful configs.

## Requirements

## Role Variables
| Variable                       | Default                          | Comments (type)  |
| :---                           | :---                             | :---             |
| default_user | splatrat | zsh default user |
| userlist | | list of users and their homedir root |

## Dependencies
No role dependencies. Should work with any distro for which the `package` module
works and the package names for git/zsh are `git` and `zsh`. Feel free to hollar
if you run into exceptions here.

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: zsh
```

## Testing

## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
