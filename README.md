# 🛠️ Criação de arquivos .desktop no linux.

## 📚 Exemplo com o vscode.
° 1. Localizar o binárioaplc: .vscode_app/VSCode-linux-x64/code <- Coloquei o meu aqui, mas normalmente fica no diretório que foi extraído(Em Download por default).

° 2. Criar um arquivo .desktop em .local/share/applications/vscode.desktop <- Esse "vscode.desktop" vai ser o nome do arquivo, mas pode colocar o de acordo com seu binário.

° 3. Conteúdo para colocar dentro do arquivo, e editar do seu jeito:
```bash
[Desktop Entry] # Cabeçalho obrigatório, defini o inicio de uma entrada '.desktop'.
Name=Visual Studio code # Nome que será exibido no menu de aplicativos do sistema'
Comment=editor de código-fonte # Descrição curta do app, geralmente mostra esse mensagem ao passar o curso do mouse sobre o ícone.
Exec=/home/adyr/.vscode_app/VSCode-linux-x64/code # Caminho para o binário.
Type=Application # Diz ao sistema que isso é um arquivo executável.
StartupNotify=true # Animação de carregamento, cursor piscando por exemplo.
StartupWMClass=Code # Associa o lançador com a janela do aplicativo.
Categories=Development;IDE;TextEditor; # Define a categoria do aplicativo para ajudar na exibição do ícone.
Terminal=false # Define se o app precisa ser executado em um terminal, se for 'GUI' deixa em false.
```

## 🙋 Autor
0xReconDev
Estudante de Pentest | GitHub: @0xReconDev
