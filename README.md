# Ansible setup

## Pull from git 
```bash
ansible-pull -U git@github.com:Kristmh/ansible.git
```
## Install local
```bash
ansible-playbook local.yml
```

## Change to colemak dh iso keyboard

```bash
setxkbmap -model pc5 -layout us -variant colemak_dh_iso
```

