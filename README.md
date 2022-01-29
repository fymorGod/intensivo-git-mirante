*Guia prático - Manipulando o git*

### Instalação 

* https:://git-scm.com/download

# Cenários - Caso de uso

# Somos os Deuses do projeto
- [x] Você desejar criar pontos na história da produção do projeto
- [x] Você deseja verificar as mudanças feitas no seu projeto
- [x] Você deseja construir uma nova funcionalidade, porém sem estragar o projeto produção
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você agora precisa deletar a branch da nova funcionalidade, depois de aplicar no projeto

# Inicializar o projeto com o Git
	- git init
	- criar o arquivo a ser codificado
	- adicionar esse arquivo como um ponto na história do projeto
	- git add "nome do arquivo"
	- git commit -m " texto para referenciar o motivo da alteracao "
	- git log para verificar o que já foi feito
	- git status para caso haja alteração no arquivo indentificar
		que algo foi alterado.
	- git branch "nome da branch" - significa ramificação
	- git checkout para mudar de branch
	- git merge "nome da branch" para adicionar as atualizações ao projeto principal
	- git branch -D "nome da branch" para deletar a branch criada
# Processo pós criar repositório local
    - é preciso criar um repositório no github
    - git remote add origin https://github.com/fymorGod/intensivo-git-mirante.git
    - clonar algum projeto usando git clone
    - git commit -am " nome do arquivo " - faz com que preparamos o arquivo e já criamos o ponto no tempo
    - git checkout "codido da linha do tempo alterada" -- "nome do arquivo a ser resgatado
