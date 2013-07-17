dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `bash` and  development environment as follows:

```sh
cd $HOME
git clone https://github.com/TudorCampean/dotfiles.git
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
```

See also http://github.com/startup-class/setup to install prerequisite
programs. 
