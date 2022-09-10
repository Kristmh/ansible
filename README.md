# ansible

## Install from cloned local

```bash
ansible-playbook -t dotfiles --ask-vault-pass local.yml
```

## Change to colemak dh iso keyboard

```bash
setxkbmap -model pc5 -layout us -variant colemak_dh_iso
```
