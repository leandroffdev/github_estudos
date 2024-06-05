# Meu Repositório de estudos - Git e Github

## Objetivos da aula:

0. Configurar acesso via HTTPS e SSH
   - Acesso HTTPS
   > digita no gitbash:  
   > git config --global user.name "nome do usuário github"  
   > git config --global user.email "email do usuario github"

   - Acesso SSH
   > digita no gitbash:  
   > git config --global user.name "nome do usuário github"  
   > git config --global user.email "email do usuario github"  
   > ssh-keygen  
   > vai teclando enter  
   > va na pasta que foi salva as chaves (c:/users/nomeDoUsuario/.ssh)  
   > cat nomeDaChave.pub  
   > copia o conteudo da chave  
   > vai no github > conficurações > chaves ssh e GPG > Nova chave  
   > agora, é só copiar a url ssh em vez da url https do repositório  
   > no gitbash digita: git remote set-url origin "url ssh"  
   > git init  
   > git add .  
   > git commit -m "Mensagem"  
   > git push origin "url ssh"

1. Criar um repositório local e adiciona-lo ao github remoto; [ x ]
   > cria um diretório local  
   > cria um repositório no github com o mesmo nome do local  
   > abre o gitbash no diretório local e digita:  
   > git init  
   > git branch -M main  
   > git add .  
   > git commit -m "Mensagem"  
   > git push origin "url https"  
   > git status

2. Clonar um repositório remoto para o nosso computador local; [ x ]
   > vai no repositório remoto e copia a url dele.  
   > vai até o local desejado para receber o repositório remoto  
   > digita no gitbash:  
   > git clone "url do repositório remoto"

3. Fazer Alterações >> Adicionar | Commitar | Enviar arquivor; [ x ]
   > git add .  
   > git commit -m "Mensagem"  
   > git push origin "url https"

4. Criar uma nova Branch e merge; [ ]
   > git branch  
   > git branch versao1  
   > git checkout versao1  
   > fazer alterações  
   > git add .  
   > git commit -m "Mensagem"  
   > git push origin versao1  
   > vai aparecer no github a solicitação de pull request  
     
    > para fazer o merge, volta p a branch main  
    > git checkout main  
    > git merge versao1
5. Realizar um Fork e pull Request; [ ]
   > para fazer um fork vai no repositório do github  
   > clica em fork. agora passará a aparecer no seu github  
   > após fazer alterações, se quiser fazer um pull request,  
   > no repositorio forkado clica em pull request e criar pull request
