# Ansible Role: Plug

Install Plug (minimalist Vim plugin Manager) using Homebrew, and install any plugin listed in vim/config/plugins.vimrc 

## Requirements

Vim

## Role Variables

  vim_plug_repo: "https://github.com/junegunn/vim-plug.git"

The GitHub repository for vim-plug 

  vim_plug_dest: "{{ ansible_user_dir }}/.vim/autoload/plug.vim"

The path where Plug will be installed

  vim_plug_list: "{{ ansible_user_dir }}/.vim/config/plugins.virmc"

The path where PlugInstall will find the plugin list to install

## Dependencies

None.

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Olivier Oudry](http://a2r.io/)
