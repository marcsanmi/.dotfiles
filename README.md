# .dotfiles config
## Handling File Conflicts with Stow
When stowing directories, you may encounter warnings if there are existing files that conflict with the ones being stowed. 
To seamlessly integrate existing files into your stow-managed directory, use the --adopt option with Stow. This command 
adopts the existing files into your dotfiles repository and replaces them with symlinks, resolving conflicts:

```
stow --adopt . 
```

Note: Before using --adopt, ensure to backup any important files to avoid accidental data loss.

