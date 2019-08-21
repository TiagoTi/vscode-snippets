cd $HOME/projects/ && git clone git@github.com:TiagoTi/vscode-snippets.git
export VSCODE_SNIPPET_HOME=$HOME/.config/Code/User/snippets
rm -fr $VSCODE_SNIPPET_HOME
ln -s $HOME/projects/vscode-snippets $VSCODE_SNIPPET_HOME
