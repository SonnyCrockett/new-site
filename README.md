#new-site

**new-site** is a bash script I created to quickly setup file/folder structure for new sites.

It expects that you are using the following for your local environment:
> XAMPP  
> zshrc  
> LiveReload  
> Sass or some other CSS pre-processor

...and supports initializing/installing: git, svn, WordPress, ExpressionEngine or none of the above.

It will add a new entry to XAMPPs vhosts file as well as a new entry to your /etc/hosts file. It will also add a new alias to your .zshrc profile so you can quickly go to the site if using the command line.

You will have to tweak the paths to accomodate your setup.

If you use a different shell other than zsh, say bash, then swap out the `~/.zshrc` call and replace it with `~/.bash_profile` or whatever your shell's profile file is called and wherever it is located if not in user root.
