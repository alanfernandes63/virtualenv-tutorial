# Pequeno tutorial falando sobre virtualenv python

Virtualenv é uma espécie de container ou um ambiente virtual onde ficarão isolados tudo que diz respeito a questão de sistema
operacional, versão do python, e bibliotecas instaladas. Evitando assim uma dor de cabeça para o desenvolvedor.

### Instalação da virtualenv no linux
para a instalação do virtualenv você deve possuir o python e o pip instalado em sua máquina, irei utilizar o pip3, mas lembrando que você deve utilizar a versão que está instalada em sua máquina, tendo estas duas dependências
abra o seu terminal e digite o seginte comando para instalar o virtualenv:
<br>
<code>pip3 install virtualenv</code>
<br>
### Criação da virtualenv
Ocorrendo tudo certo com a instalação da virtualenv você deve ir na raiz do seu projeto para criar sua virtualenv, estando na raiz o próximo passo é digitar o seguinte comando para a criação do virtualenv:
<br>
<code>virtualenv nome da virtualenv</code>
<br>
### Ativação da virtualenv
Para ativar a virtualenv basta colocar o seguinte comando:
<br>
### Instalação de dependências na virtualenv
O processo de instalação de dependências é o mesmo, sendo que a virtualenv deverá estar ativada vou instalar o django a nivel de exemplo, para instalação do django e só executar o seguinte código:
<br>
<code>pip3 install django</code>
<br>
<code>source nome da sua virtualenv/bin/activate</code>
### Desativando a virtualenv
Para desativar a virtualenv você precisará estar dentro do diretório do projeto e digitar o seguinte comando:
<br>
<code>deactivate</code>

