# A Perl Password Generator

Disclaimer: this program is not finished, only use it at your own risks.

## Future Features

1. Save password in a file (with a name) in a .password-store
   directory
2. Be able to find passwords with a simple command
3. Access them with dmenu
4. Encrypt files storing passwords
5. Make it work with dmenu
6. List them in tree-like manner
7. Add color to output password [done]

## How To Use It

1. Clone this repository into /home/$USER/.local/repo
2. Install dependencies: dmenu, tree
3. Make file executable: chmod u+x passgen.pl
4. Create a symlink: ln -s ~/.local/repos/passgen.pl ~/local/bin/passgen
