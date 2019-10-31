# Pequeno tutorial falando sobre virtualenv python

Virtalenv é uma espécie de container ou um ambiente virtal onde ficarão isolados tudo que diz respeito a questão de sistema
operacional, versão do python, e bibliotecas instaladas. Evitando assim uma dor de cabeça para o desenvolvedor.

### Instalação da virtualenv no linux
para a instalação do virtualenv você deve possuir o python e o pip instalado em sua máquina, irei utilizar o pip3, mas lembrando
que você deve utilizar a versão que está instalada em sua máquina, tendo estas duas dependências
abra o seu terminal e digite o seginte comando para instalar o virtalenv:
<br>
<code>pip3 install virtualenv</code>
<br>
### Criação da virtualenv
Ocorrendo tudo certo com a instalação da virtalenv você deve ir na raiz do seu projeto para criar sua virtalenv, estando na raiz o próximo passo é digitar o seguinte comando para a criação do virtalenv:
<br>
<code>virtualenv nome da virtualenv</code>
<br>
### Ativação da virtualenv
Para ativar a virtualenv basta colocar o seguinte comando:
<br>
<code>souce nome da sua virtualenv/bin/activate</code>
### Desativando a virtualenv
Para desativar a virtualenv você precisará estar dentro do diretório do projeto e digitar o seguinte comando:
<br>
<code>deactivate</code>

