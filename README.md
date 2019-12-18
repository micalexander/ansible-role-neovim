# ansible-role-neovim

### Dependencies

This role depends on `ansible` as well as several ansible roles including:

 - `micalexander.python2` for python2 support
 - `micalexander.python3` for python3 support
 - `micalexander.ruby` for ruby support
 - `micalexander.node` for node support

If you don't want these language support modules installed you should use a different neovim role or submit a pull request to make the additional language support optional. 

### Usage

#### Install independently
`ansible-pull -U https://github.com/micalexander/ansible-role-neovim.git -K`

#### Include in playbook
```
roles:
 - micalexander.neovim
```
