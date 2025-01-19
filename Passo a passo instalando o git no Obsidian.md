
Primeiro passo é entrar em configurações do Obsidian
Plugins não oficiais
instalar o plugin Git


imagem-obsidian
![[imagem-obsidian.png]]

o programa vai criar uma pasta no seus Documentos chamado obsidian Vault

importante antes de continuar criar uma conta no Github para ter um repositório para vincular
já na pagina inicial vai ter uma aba de repositórios, onde tem um botão azul new, para criar novo.

profile-github
![[profile-github.png]]

após criar, vai aparecer uma tela seguinte

lista-codigo-github
![[lista-codigos-github.png]]

Agora vamos baixando o git
https://git-scm.com/downloads

depois de instalar, vamos ate a pasta Obsidian Vault  dentro de meus documentos e clicar com botão direito na pasta irá abrir Open  Git Bash here.
use esses comandos aqui primeiro:

git config user.name "seu-usuario" 
git config user.email "seu-email@exemplo.com"

agora basta copiar os comandos descritos no github.

Qualquer erro me avisa

e pra finalizar vai abrir um bloco de notas salvar com o nome .gitignore
adicionar o conteudo:

.obsidian
.trash/
.DS_Store

isso é um documento que o github ira ignorar e não vai subir, são documentos e arquivos locais que você não desejar subir para o repo é só add na lista.



