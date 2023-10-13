# ansible-role-linux-base

<!--toc:start-->
- [ansible-role-linux-base](#ansible-role-linux-base)
    - [Packages to install](#packages-to-install)
    - [User to activate zsh on](#user-to-activate-zsh-on)
<!--toc:end-->

### Packages to install
```
package_list:
  - name: curl
  - name: git
  - name: htop
```

### User to activate zsh on
```
ansible_user: "maccan"
```
