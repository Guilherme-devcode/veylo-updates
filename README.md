# Veylo — atualizações

Este repositório distribui somente os instaladores oficiais do Veylo para Windows. O código-fonte e os testes ficam em um repositório privado. O aplicativo consulta o [release mais recente](https://github.com/Guilherme-devcode/veylo-updates/releases/latest) e oferece o download quando a versão publicada supera a instalada.

As versões são montadas em um runner Windows a partir de um commit validado pelo CI do projeto privado. O instalador não é assinado com certificado comercial. Feche o aplicativo antes de instalar uma versão nova; os bancos locais permanecem em `%APPDATA%\Sale`.
