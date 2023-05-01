# vscode_config_user
Monokai + pluging config PHP

Extenciones 

  code --install-extension aswinkumar863.smarty-template-support
  code --install-extension ChakrounAnas.turbo-console-log
  code --install-extension chouzz.vscode-better-align
  code --install-extension esbenp.prettier-vscode
  code --install-extension MS-CEINTL.vscode-language-pack-es
  code --install-extension ms-vscode-remote.remote-containers
  code --install-extension ms-vscode-remote.remote-ssh
  code --install-extension ms-vscode-remote.remote-ssh-edit
  code --install-extension ms-vscode-remote.remote-wsl
  code --install-extension ms-vscode-remote.vscode-remote-extensionpack
  code --install-extension ms-vscode.live-server
  code --install-extension ms-vscode.remote-explorer
  code --install-extension ms-vscode.remote-server
  code --install-extension neilbrayfield.php-docblocker
  code --install-extension zobo.php-intellisense

Para listar las extenciones en power

Unix:
code --list-extensions | xargs -L 1 echo code --install-extension

Windows (PowerShell, e. g. using Visual Studio Code's integrated Terminal):
code --list-extensions | % { "code --install-extension $_" }
  
