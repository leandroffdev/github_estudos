# Meu Repositório de estudos - Git e Github

## Objetivos da aula:

0. Configurar acesso via HTTPS e SSH
   - Acesso HTTPS
   a. digita no gitbash:
   b. git config --global user.name "nome do usuário github"
   c. git config --global user.email "email do usuario github"

   - Acesso SSH
   a. digita no gitbash:
   b. git config --global user.name "nome do usuário github"
   c. git config --global user.email "email do usuario github"
   d. ssh-keygen
   e. vai teclando enter
   f. va na pasta que foi salva as chaves (c:/users/nomeDoUsuario/.ssh)
   g. cat nomeDaChave.pub
   h. copia o conteudo da chave
   i. vai no github > conficurações > chaves ssh e GPG > Nova chave
   j. agora, é só copiar a url ssh em vez da url https do repositório
   k. no gitbash digita: git remote set-url origin "url ssh"
   l. git init
   m. git add .
   n. git commit -m "Mensagem"
   o. git push origin "url ssh"

1. Criar um repositório local e adiciona-lo ao github remoto; [ x ]
   a. cria um diretório local
   b. cria um repositório no github com o mesmo nome do local
   c. abre o gitbash no diretório local e digita:
   d. git init
   e. git branch -M main
   f. git add .
   g. git commit -m "Mensagem"
   h. git push origin "url https"
   i. git status

2. Clonar um repositório remoto para o nosso computador local; [ x ]
   a. vai no repositório remoto e copia a url dele.
   b. vai até o local desejado para receber o repositório remoto
   c. digita no gitbash:
   d. git clone "url do repositório remoto"

3. Fazer Alterações >> Adicionar | Commitar | Enviar arquivor; [ ]
4. Criar uma nova Branch; [ ]
5. Realizar um pull Request e Merge; [ ]
6. Criar nosso primeiro Fork; [ ]