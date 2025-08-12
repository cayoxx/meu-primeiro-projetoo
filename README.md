# Plano de Recuperação

## Objetivo do Teste

O objetivo é recuperar um projeto perdido ou variantes na máquina usando GIT HUB.

## Ambiente do Teste

Utilizando o Windows, iremos abrir o GITHUB no navegador e acessar o projeto pelo link.

## Etapas de Backup

Para que a recuperação funcione, o projeto deve ser salvo (sincronizado) no GitHub regularmente com os seguintes comandos:

- git add .: Adiciona as alterações.

- git commit -m "mensagem": Salva as alterações localmente.

- git push: Envia as alterações salvas para o GitHub.


## Simulação de Falha

Para simularmos uma falha, é possível apagar a pasta do projeto da máquina, para não ter vestígios. Em situações reais pode ser com o disco corrompido, troca de máquina e entre outras.

## Procedimento de Recuperação

- Escolha o local que você irá importar o projeto, nesse lugar abra o TERMINAL;
- Digite "git clone {link do projeto}" e aperte ENTER
- Se tudo ocorrer bem, o projeto estará em sua máquina, mas será necessário acesso a internet para que dê certo.

## Critérios de Aceitação

- A pasta do projeto com todos os arquivos da última versão enviada ao GitHub for criada.

- O histórico de alterações (git log) estiver completo e intacto.

- For possível abrir e verificar a integridade dos arquivos do projeto.
