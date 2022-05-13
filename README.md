<p align="center" width="100%">
    <img width="33%" src="https://github.com/camilaftin/be-academy/tree/main/gitegithub/readme_img">
</p>

# DevStart Paylivre - Aula 05 

Meu primeiro README com os comandos de Git e GitHub.

### 🚀 Sobre mim - o Git e o GitHub
Eu, o Git, sou um sistema de controle de versão de arquivos e meu <s>irmão</s> - GitHub - é uma plataforma onde você, pequeno gafanhoto, pode armazenar seus lindos projetos.

## 🛠 Comandos
Sem mais delongas!!! Sigam-me os <s>bons!</s> meus comandos:

Primeiro você deve ir para o diretório desse projeto. Ao "chegar" no seu diretório desejado usar o
```
   git init
```
 O comando cria um novo subdiretório chamado .git que contém todos os arquivos necessários de seu repositório. Neste ponto, nada do projeto é monitorado. Para começar a rastrear um novo arquivo, você deve usar o comando
 
 ```
   git add <arquivo> ou .
```
 Move uma alteração de untracked para staged, no caso de usar o nome do arquivo. Ao usar com **.**, moverá todos de uma vez. Executando o comando
 
 ```
   git status
```
Você pode ver que seu(s) arquivo(s) agora estão sendo rastreados e preparados para o *commit*

 ```
   git commit -m " "
```
O comando apresenta de forma mais rápida a mensagem que você deseja incluir, para tanto digitará por linha de comando. Caso contrário usará um editor, como o *vim*. Você acaba de criar seu primeiro *commit*!
Agora, você quer enviar todo o conteúdo para um repositório remoto, para isso deve usar:

 ```
   git push
```
O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto.

Contudo, um certo arquivo que te não serve mais precisa ser removido do Git, logo você precisa removê-lo dos seus arquivos rastreados: 

```
   git rm
```
O comando acima remove da área de *stage* e também do seu diretório. Outra coisa útil é querer manter o arquivo no diretório, mas removê-lo da sua área de *stage*. Para fazer isso, use a opção **--cached**

```
   git rm --cached <nome do arquivo>
```
Depois é só *comitar* novamente!


### *Branches* - O que é isso ????

Pode-se compreender como um ponteiro para um *commit*. A branch padrão é a *master*. 

Para mudar para uma branch existente, você executa o comando:

```
   git checkout <nome da branch>
```
Caso você deseje clonar a branch do github para a máquina local:

```
   git clone <url com https ou ssh>
```


