# [Voltar](../index.md)

## Preparando o Ambiente

 # Índice
1. [Instalando o .net](#.net)
1. [Configurando o Visual Studio Code](#VS-Code)


# .net

Para instalar o .net core no ubuntu, rode os seguintes comandos:

Para adicionar uma chave da microsoft e registrar o repositorio, execute os seguintes comandos

OBS: em '19.10' abaixo, mude para a versão que está instalado em sua máquina.

```bash
wget https://packages.microsoft.com/config/ubuntu/19.10/packages-microsoft-prod.deb -O packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb
```

Após adicionar os repositórios, instale as dependências da aplicação.

```bash
sudo add-apt-repository universe
sudo apt-get update
sudo apt-get install apt-transport-https
sudo apt-get update
sudo apt-get install dotnet-sdk-3.1
```

Para ver as versões disponiveis, [consulte a documentação oficial](https://docs.microsoft.com/pt-br/dotnet/core/install/linux-package-manager-ubuntu-1910)


# VS Code

[Clique aqui para baixar o editor no site oficial](https://code.visualstudio.com/download)

Recomendação de extensões: 

C# Extensions - Clicando com o botão direito do mouse em cima de uma pasta na barra lateral, habilita a opção de criação de classe .net

C# - da microsoft
