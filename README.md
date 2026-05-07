Bem-vindo ao Github, eu sou Eduardo e vou te apresentar esse mundo vasto



Esse é um projeto para te ajudar a entender melhor o github

                                      COMEÇANDO COM OS COMANDOS DO GIT
                                   
      -->Inicialização e configuração
- git init → cria um repositório Git na pasta atual
- git clone URL → copia um repositório remoto
- git config --global user.name "Seu Nome" → define nome
- git config --global user.email "email@exemplo.com" → define email


      -->Ver estado do projeto
- git status → mostra arquivos modificados
- git log → histórico de commits
- git log --oneline → histórico resumido
- git diff → mostra alterações


      -->Adicionar e salvar mudanças
- git add arquivo → adiciona arquivo específico
- git add . → adiciona tudo
- git commit -m "mensagem" → cria commit


      -->Trabalhando com branches
- git branch → lista branches
- git branch nome → cria branch
- git checkout nome → muda de branch
- git switch nome → forma moderna de trocar branch
- git checkout -b nome → cria e troca
- git merge nome → junta branch atual com outra


      -->Repositório remoto (GitHub/GitLab)
- git remote -v → mostra remotos
- git push → envia commits
- git pull → baixa e atualiza
- git fetch → baixa sem aplicar


      -->Desfazer mudanças
- git restore arquivo → desfaz alterações locais
- git reset --hard HASH → volta para commit específico
- git revert HASH → desfaz commit criando outro
- git clean -fd → remove arquivos não rastreados


      -->Comandos muito úteis
- git stash → guarda mudanças temporariamente
- git stash pop → recupera mudanças guardadas
- git rm arquivo → remove arquivo do Git
- git mv antigo novo → renomeia arquivo
- git tag v1.0 → cria versão/tag

Agora que já falamos um pouco sobre os comandos do git, vamos entrar em um assunto, o que é o Github?

Github é o site/plataforma onde os repositórios do Git ficam hospedados, ou seja, onde tem um MUNDO de informações, e o Git, é onde a magia acontece (ferramenta de controle de versão)

                                      O que dá para fazer no Github?
                                      
Você guarda projetos na nuvem, você envia o seu código à um repositório online para que as pessoas também possam ver o seu código e também você ver o de outras pessoas
Você pode estudar códigos públicos, contribuir em outros projetos e baixar bibliotecas.

                                                Branch

                                Uma linha paralela de desenvolvimento.
                                           Muito usada para:

- criar funcionalidades
- testar mudanças
- corrigir bugs


                                              Diferença de Git para Github


                                          Git               |      GitHub                   
                                     ---------------------- | ------------------------ 
                                     Ferramenta local       | Plataforma online        
                                     Funciona no computador | Funciona na internet     
                                     Controle de versão     | Hospedagem e colaboração 

Ok, adorei o Github Eduardo é uma plataforma incrível, mas como eu faço para postar o meu repositório?

QUASE que esqueci do mais importante pequeno, bom vou fazer um passo a passo bem fácil de entender ok?

Primeiro, instale o Git (ou não da pra fazer pelo navegador também) no seu computador acessando o site oficial do Git. Depois da instalação, abra o terminal ou prompt de comando e verifique se o Git foi instalado corretamente digitando git --version.

Em seguida, crie uma conta no GitHub acessando o site oficial do GitHub e fazendo seu cadastro.

Depois disso, configure seu nome e email no Git, pois essas informações serão usadas nos commits. No terminal, use os comandos para definir seu nome e email globalmente.

Agora crie uma pasta para o seu projeto no computador. Entre nessa pasta pelo terminal e adicione algum arquivo, como um README.md ou qualquer arquivo do seu projeto.

Com a pasta pronta, inicialize o Git usando o comando git init. Isso transforma a pasta em um repositório Git.

Depois adicione os arquivos ao controle de versão usando git add . e crie o primeiro commit com git commit -m "Primeiro commit".

O próximo passo é criar um repositório no GitHub. Dentro do GitHub, clique em “New repository”, escolha um nome e crie o repositório.

Após criar o repositório, o GitHub mostrará uma URL do projeto. Copie essa URL e conecte seu projeto local ao GitHub usando o comando git remote add origin seguido da URL do repositório.

Depois envie o projeto para o GitHub usando git branch -M main e em seguida git push -u origin main.

Quando o envio terminar, seu projeto estará online no GitHub e poderá ser acessado pelo link do repositório.

Depois do primeiro envio, o fluxo normal de atualização será:
modificar arquivos, usar git add ., fazer um novo commit com git commit -m "descrição da alteração" e enviar novamente com git push.

De um jeito mais simplificado


1. Criar uma conta no GitHub.

2. Configurar nome e email no Git.

3. Criar uma pasta do projeto no computador.

4. Colocar os arquivos do projeto dentro dessa pasta.

5. Abrir o terminal na pasta do projeto.

6. Inicializar o Git com:
- git init

7. Adicionar os arquivos ao Git:
git add .

8. Criar o primeiro commit:
- git commit -m "Primeiro commit"

9. Criar um novo repositório no GitHub.

10. Copiar a URL do repositório criado.

11. Conectar o projeto local ao GitHub:
- git remote add origin URL_DO_REPOSITORIO

12. Definir a branch principal:
- git branch -M main

13. Enviar o projeto para o GitHub:
- git push -u origin main
- O repositório ficará online no GitHub.


           Depois disso, sempre que fizer alterações:
- adicionar mudanças com git add .
- criar novo commit com git commit -m "mensagem"
- enviar atualizações com git push

















































































